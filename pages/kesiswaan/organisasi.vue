<template>
    <div class="container">
        <h4 class="mt-5">Organisasi <br> <span class="text-primary">SIswa</span></h4>
        <div class="row m-3 mt-5 justify-content-center">
            <div class="col-6 col-md-4">
                <div class="card bg-light rounded-4">
                    <img src="~/assets/img/logo/mpk.png" class="card-img-top rounded-2 mt-3" alt="img-artikel">
                    <div class="card-body text-center p-2 mb-3 mt-3">
                        <h6>MPK</h6>
                    </div>
                </div>
            </div>
            <div class="col-6 col-md-4">
                <div class="card bg-light rounded-4">
                    <img src="~/assets/img/logo/osis.png" class="card-img-top rounded-2 mt-3" alt="img-artikel">
                    <div class="card-body text-center p-2 mb-3 mt-3">
                        <h6>OSIS</h6>
                    </div>
                </div>
            </div>
            <div class="col-6 col-md-4">
                <div class="card bg-light rounded-4">
                    <img src="~/assets/img/logo/pub.png" class="card-img-top rounded-2 mt-3" alt="img-artikel">
                    <div class="card-body text-center p-2 mb-3 mt-4">
                        <h6>PUB</h6>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
useHead({ title: "Organisasi - SMKN 4 Tasikmalaya" })

</script>


<style scoped>
h4, h6, .btn {
    font-family: "Poppins", serif;
}

h4 {
    margin-left: 95px;
}

.card {
    background-color: transparent;
    backdrop-filter: blur(20px);
    border: 2px solid #ffff;
}

.btn {
    font-size: 12px;
    width: 150px;
    border: 2px solid #ffff;

}

.card-img-top {
    width: 150px;
    margin: auto;
}

.text-primary {
    color: #1F60A0 !important;
}

@media only screen and (min-width: 600px) and (max-width: 890px) {
    h4 {
        margin-left: 30px;
    }

    .card-img-top {
        width: 45%;
    }
   
}

@media only screen and (max-width: 600px) {
    h4 {
        margin-left: 35px;
    }

    .card {
        margin-top: 20px;
    }

    .card-img-top {
        width: 50%;
    }

    h6 {
        font-size: small;
    }
}

</style>