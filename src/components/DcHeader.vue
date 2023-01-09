<script>
export default {
    data() {
        return {
            navItems: [
                {
                    text: 'Characters'
                },
                {
                    text: 'Comics'
                },
                {
                    text: 'Movies'
                },
                {
                    text: 'TV'
                },
                {
                    text: 'Games'
                },
                {
                    text: 'Collectibles'
                },
                {
                    text: 'Videos'
                },
                {
                    text: 'Fans'
                },
                {
                    text: 'News'
                },
                {
                    text: 'Shop'
                },
            ]
        }
    }
}
</script>

<template>

    <header class="p-3">
        <div class="container">
            <div class="row just">
                <div class="col-3">
                    <img src="../assets/imgs/dc-logo.png" alt="dc-logo">
                </div>
                <div class="col-8">
                    <nav>
                        <ul class="d-flex">
                            <li v-for="navItem in navItems">{{ navItem.text }}</li>

                        </ul>
                    </nav>
                </div>
            </div>
        </div>
    </header>

</template>

<style lang="scss" scoped>
header {
    height: 120px;
}

div img {
    width: 30%;
    align-self: center;
}

nav ul {
    list-style-type: none;


    li {
        padding: 1rem;
        text-transform: uppercase;
        align-items: center;
    }

}
</style>