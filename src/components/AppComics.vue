<script>
export default {
    name: 'AppComics',
    props: [
        'path',
        'comicsPrice',
        'series',
        'price'
    ]
}
</script>

<template>
    <div class="col-2 p-3">
        <img :src="path" alt="path">
        <h4></h4>
    </div>
</template>

<style lang="scss" scoped>

</style>