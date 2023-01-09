<script setup>

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
                            <li>characters</li>
                            <li>comics</li>
                            <li>tv</li>
                            <li>games</li>
                            <li>collectibles</li>
                            <li>videos</li>
                            <li>fans</li>
                            <li>news</li>
                            <li>shop</li>
                        </ul>
                    </nav>
                </div>
            </div>
        </div>
    </header>

</template>

<style lang="scss" scoped>
header {
    height: 100px;
}

div img {
    width: 30%;
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