<template>
    <div class="container">
        <h4 class="mt-5">Prestasi</h4>
        <div class="row m-3 justify-content-center">
            <div class="col-md-3">
                <div class="card bg-light rounded-4">
                    <img src="~/assets/img/prestasi/lksotomotif.jpg" class="card-img-top p-2 rounded-4" alt="img-artikel">
                    <div class="card-body text-center p-2 mt-1 mb-2">
                        <h5 class="mt-3">Juara 1</h5>
                        <p class="mt-3 fw-normal">LKS Otomotif Tingkat Kota Tasikmalaya Bidang Lomba Motorcyrcle Repair & Maintenance</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card bg-light rounded-4">
                    <img src="~/assets/img/prestasi/silatpd.jpg" class="card-img-top p-2 rounded-4" alt="img-artikel">
                    <div class="card-body text-center p-2 mt-1 mb-2">
                        <h5 class="mt-3">Juara Umum 2</h5>
                        <p class="mt-3 fw-normal">Tingkat SLTA Pada Kejuaraan Silat Perisai Diri Wali Kota Tasikmalaya Cup Tahun 2023</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card bg-light rounded-4">
                    <img src="~/assets/img/prestasi/02snatletik.jpg" class="card-img-top p-2 rounded-4" alt="img-artikel">
                    <div class="card-body text-center p-2 mt-1 mb-2">
                        <h5 class="mt-3">Juara 3</h5>
                        <p class="mt-3 fw-normal">Atletik (Panca Lomba) Putra O2SN SMK Tingkat Jawa Barat 2024</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
useHead({ title: "Prestasi - SMKN 4 Tasikmalaya" })

</script>


<style scoped>
.card-img-top {
    width: 100%;
    height: 240px;
    object-fit: cover; /* Menyesuaikan gambar dengan ukuran card */
    object-position: center; /* Fokus gambar di tengah */

}

.card {
    background-color: transparent;
    backdrop-filter: blur(20px);
    border: 2px solid #ffff;
}

h4, h5, p {
    font-family: "Poppins", serif;
}

h4 {
    margin-left: 95px;
}

p {
    font-size: 15px;
}

@media only screen and (min-width: 600px) and (max-width: 890px) {
    h4 {
        margin-left: 30px;
    }

    .card-img-top {
        height: 150px;
    }
    
}

@media only screen and (max-width: 600px) {
    p{
        font-size: smaller;
    }

    h5 {
        font-size: medium;
    }
    
    h4 {
        margin-left: 35px;
    }

    .card-img-top {
        height: 250px;
    }

    .card {
        margin-top: 20px;
    }
}

</style>