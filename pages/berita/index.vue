<template>
    <div class="container">
        <h4 class="mt-5">Berita <br> <span class="text-primary">Terbaru</span></h4>
            <span class="text-artikel">
                <p class="mt-3">Berita terbaru, cerita inspiratif dan informasi terkini seputar kegiatan serta prestasi sekolah kami.</p>
            </span>
        <div class="row m-3 justify-content-center">
            <div class="col-md-5">
                <div class="card mt-3 bg-light rounded-4">
                    <img src="~/assets/img/artikel/iduka.jpg" class="card-img-top p-2 rounded-4" alt="img-artikel">
                    <div class="card-body">
                        <p class="text-end">Kamis, 12 Okt 2023</p>
                        <h5 class="text-center mt-1">SMKN 4 Tasikmalaya Koneksikan Iduka dengan Pencari Kerja</h5>
                        <a href="https://radartasik.id/2023/10/12/smkn-4-tasikmalaya-koneksikan-iduka-dengan-pencari-kerja/" target="_blank"><p class="mt-4">Baca Selengkapnya <span><i class="bi bi-arrow-right-circle text-black"></i></span></p>
                        </a>
                    </div>
                </div>
            </div>
            <div class="col-md-5">
                <div class="card mt-3 bg-light rounded-4">
                    <img src="~/assets/img/artikel/honda.jpeg" class="card-img-top p-2 rounded-4" alt="img-artikel">
                    <div class="card-body">
                        <p class="text-end">Senin, 20 Mei 2024</p>
                        <h5 class="text-center mt-1">Honda Resmikan Safety Riding Lab di SMKN 4 Tasikmalaya, Ciptakan Bibit Keselamatan di Jawa Barat</h5>
                        <a href="https://www.pikiran-rakyat.com/otomotif/pr-018109177/honda-resmikan-safety-riding-lab-di-smkn-4-tasikmalaya-ciptakan-bibit-keselamatan-pada-gen-z?page=all" target="_blank"><p class="mt-4">Baca Selengkapnya <span><i class="bi bi-arrow-right-circle text-black"></i></span></p>
                        </a>
                    </div>
                </div>
            </div>
            <div class="col-md-5">
                <div class="card mt-3 bg-light rounded-4">
                    <img src="~/assets/img/artikel/expocreannnova.jpg" class="card-img-top p-2 rounded-4" alt="img-artikel">
                    <div class="card-body">
                        <p class="text-end">Senin 27 Feb 2023</p>
                        <h5 class="text-center mt-1">Siswa SMKN 4 Tasikmalaya Adu Inovasi dan Kreativitas di Expo Creanova</h5>
                        <a href="https://radartasik.id/2023/03/02/siswa-smkn-4-tasikmalaya-adu-inovasi-dan-kreativitas-di-expo-creanova/" target="_blank"><p class="mt-4">Baca Selengkapnya <span><i class="bi bi-arrow-right-circle text-black"></i></span></p>
                        </a>
                    </div>
                </div>
            </div>
            <div class="col-md-5">
                <div class="card mt-3 bg-light rounded-4">
                    <img src="~/assets/img/artikel/kerjasama.jpg" class="card-img-top p-2 rounded-4" alt="img-artikel">
                    <div class="card-body">
                        <p class="text-end">Kamis, 2 Mar 2023</p>
                        <h5 class="text-center mt-1">Sinergi Bagi Negeri, DAM Kerjasama dengan SMKN 4 Tasikmalaya Terapkan KTBSM Sepeda Motor Astra Honda</h5>
                        <a href="https://jabar.tribunnews.com/2023/03/02/sinergi-bagi-negeri-dam-kerjasama-dengan-smkn-4-tasikmalaya-terapkan-ktbsm-sepeda-motor-astra-honda" target="_blank"><p class="mt-4">Baca Selengkapnya <span><i class="bi bi-arrow-right-circle text-black"></i></span></p>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
useHead({ title: "Berita - SMKN 4 Tasikmalaya" })

</script>


<style scoped>
.card-img-top {
    width: 100%;
    height: 250px;
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

.text-artikel p {
    margin-left: 95px;
    max-width: 30%;
}

a {
    color: #000 !important;
    text-decoration: none;
}


@media only screen and (min-width: 600px) and (max-width: 890px) {
    h4, .text-artikel p {
        margin-left: 30px;
    }

    .card-img-top {
        width: 100%;
        height: 170px;
    }

    p, a {
        font-size: small;
    }

    h5 {
        font-size: medium;
    }
}

@media only screen and (max-width: 600px) {
    h4 {
        margin-left: 35px;
    }

    .card-img img {
        width: 100%;
        margin-left: 5px;
        margin-top: 35px !important;
    }

    .text-artikel p {
        margin-left: 35px;
        max-width: 50%;
        font-size: small;
    }

    .card-img-top {
        width: 100%;
        height: 200px;
    }

    p, a {
        font-size: small;
    }

    h5 {
        font-size: medium;
    }

    .berita i {
        margin-left: 5px;
    }
}


</style>