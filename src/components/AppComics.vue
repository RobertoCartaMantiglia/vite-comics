<script>
export default {
    name: 'AppComics',
    props: [
        'comicsPath',
        'comicsPrice',
        'comicsSeries',
        'comicsPrice'
    ]
}
</script>

<template>
    <div class="col-2 p-3">
        <img :src="comicsPath" alt="path">
        <h4>{{ comicsSeries }}</h4>
        <p>{{ comicsPrice }}</p>
    </div>
</template>

<style lang="scss" scoped>

</style>