<script>
export default {

}
</script>

<template>

    <footer>
        <section class="first-section">
            <div class="container">
                <div class="row align-center">
                    <div class="col-6 d-flex">
                        <div class="col-4">
                            <ul>
                                <li>
                                    <h3>DC COMICS</h3>
                                </li>
                                <li>Characters</li>
                                <li>Movies</li>
                                <li>Tv</li>
                                <li>Games</li>
                                <li>Videos</li>
                                <li>News</li>

                                <li class="mt-4">
                                    <h3>SHOP</h3>
                                </li>
                                <li>Shop Dc</li>
                                <li>Shop Collectibles</li>
                            </ul>
                        </div>
                        <div class="col-4">
                            <ul>
                                <li>
                                    <h3>DC</h3>
                                </li>
                                <li>Terms of Use</li>
                                <li>Privacy Policy</li>
                                <li>Add choiches</li>
                                <li>Advertising</li>
                                <li>Jobs</li>
                                <li>Subscriptions</li>
                                <li>Talent Workshop </li>
                                <li>CSPC</li>
                                <li>Ratings</li>
                                <li>Shop Help</li>
                                <li>Contact Us</li>
                            </ul>
                        </div>
                        <div class="col-4">
                            <ul>
                                <li>
                                    <h3>Sites</h3>
                                </li>
                                <li>DC</li>
                                <li>DC Magazine</li>
                                <li>DC Kids</li>
                                <li>DC Power Visa</li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-6 dc-logo-container">

                    </div>
                </div>
            </div>
        </section>
        <section class="second-section">
            <div class="container">
                <div class="row align-center">
                    <div class="col-6">
                        <button class="p-2">
                            Sign-up now!
                        </button>
                    </div>
                    <div class="col-6 d-flex">
                        <h3 class="text-prymary">FOLLOW US!</h3>
                        <ul class="d-flex">
                            <li>
                                <img src="../assets/imgs/footer-facebook.png" alt="">
                            </li>
                            <li>
                                <img src="../assets/imgs/footer-periscope.png" alt="">
                            </li>
                            <li>
                                <img src="../assets/imgs/footer-pinterest.png" alt="">
                            </li>
                            <li>
                                <img src="../assets/imgs/footer-youtube.png" alt="">
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
    </footer>

</template>

<style lang="scss" scoped>
footer {

    ul {
        list-style-type: none;
        padding-left: 0;
        margin-top: 0.5rem;
        padding-top: 1.5rem;
        padding-bottom: 1rem;
    }

    .first-section {

        background-image: url("../assets/imgs/footer-bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;

        h3 {
            color: white;
            font-size: 1.2rem;
            font-weight: 700;
        }


        li {
            color: #737d80;
            font-size: 0.9rem;
        }

        .dc-logo-container {
            background-image: url("../assets/imgs/dc-logo-bg.png");
            background-repeat: no-repeat;
            background-size: contain;
            background-position: center;

        }
    }

    .second-section {
        height: 100px;
        background-color: #303030;

        button {
            margin-top: 2rem;
            background: none;
            color: white;
            text-transform: uppercase;
            border: 1px solid #0282f9;
            font-weight: bolder;
        }

        h3 {
            margin-top: 2rem;
            color: #0282f9;
            font-weight: 700;
        }

        li {
            margin-left: 1.5rem;
        }
    }
}
</style>