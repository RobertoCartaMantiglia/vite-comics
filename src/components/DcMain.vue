<script>
export default {

}
</script>

<template>

    <main>
        <section class="jumbotron">

        </section>
        <section class="first-section">
            <div class="container">
                <div class="row align-center">
                    <div class="col-6 ">
                        <h2>content goes here!</h2>
                    </div>
                </div>
            </div>
        </section>
        <section class="second-section">
            <div class="container">
                <div class="row align-center">
                    <div class="col-12">

                    </div>
                </div>
            </div>
        </section>


    </main>

</template>

<style lang="scss" scoped>
main {
    // height: 300px;
    color: white;
    font-size: 2rem;
}

.first-section {
    background-color: #1c1c1c;
}

.second-section {
    background-color: #0282f9;
    height: 100px;
}

.jumbotron {
    height: 350px;
    background-image: url("../assets/imgs/jumbotron.jpg");
    background-repeat: no-repeat;
    background-size: cover;
}
</style>