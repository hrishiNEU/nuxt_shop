<template>
    <div>
        <Head>
            <Title>
                Nuxt Dojo | {{product.title}}
            </Title>
            <Meta name='description' content="production.description"/>
        </Head>

        <ProductDetails :product="product" />
    </div>
</template>

<script setup>
    const { id } = useRoute().params
    const uri = 'https://fakestoreapi.com/products/' + id

    //fetch the product

    const {data:product} = await useFetch(uri, {key: id})

    if(!product.value){
        throw createError({statusCode: 404, statusMessage:'Product Not found...', fatal:true})
    }

    definePageMeta({
        layout: 'products'
    })
</script>

<style scoped>

</style>