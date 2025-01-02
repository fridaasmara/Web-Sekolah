<template>
    <div class="container">
        <h4 class="mt-5">Galeri</h4>
            
        <!--HUT RI-->
        <div class="mt-5 mb-5">
            <div class="card bg-light card-big text-center rounded-4">
                <h5 class="fw-semibold mt-5">Upacara Peringatan HUT RI Ke-79</h5>
                <hr class="mt-3">
                <div class="row justify-content-center m-3">
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/hutri/hutri1.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/hutri/hutri2.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/hutri/hutri3.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/hutri/hutri4.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/hutri/hutri5.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/hutri/hutri6.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!--MPLS-->
        <div class="mt-5 mb-5">
            <div class="card bg-light card-big text-center rounded-4">
                <h5 class="fw-semibold mt-5">MPLS 2024</h5>
                <hr class="mt-3">
                <div class="row justify-content-center m-3">
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/mpls2024/mpls1.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/mpls2024/mpls2.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/mpls2024/mpls3.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/mpls2024/mpls4.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/mpls2024/mpls5.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/mpls2024/mpls6.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!--PORSENI-->
        <div class="mt-5 mb-5">
            <div class="card bg-light card-big text-center rounded-4">
                <h5 class="fw-semibold mt-5">PORSENI 2024</h5>
                <hr class="mt-3">
                <div class="row justify-content-center m-3">
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/porseni/porseni1.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/porseni/porseni2.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/porseni/porseni3.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/porseni/porseni4.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/porseni/porseni5.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                    <div class="col-6 col-md-4">
                        <div class="card mt-3">
                            <img src="~/assets/img/galeri/porseni/porseni6.png" alt="img" class="card-img-top">
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>

<script setup>
useHead({ title: "Galeri - SMKN 4 Tasikmalaya" })

</script>


<style scoped>
h4, h5 {
    font-family: "Poppins", serif;
}

h4 {
    margin-left: 95px;
}

.card-big {
    background-color: transparent;
    backdrop-filter: blur(20px);
    border: 2px solid #ffff;
    width: 85%;
    margin: auto;
}

hr {
    width: 50%;
    margin: auto;
}


@media only screen and (min-width: 600px) and (max-width: 890px) {
    h4 {
        margin-left: 30px;
    }
}

@media only screen and (max-width: 600px) {
    h4 {
        margin-left: 35px;
    }

    h5 {
        font-size: medium !important;
    }

}

</style>