<template>
    <div class="container-fluid p-0">

        <!--Carousel-->
        <div class="carousel p-3 diagonal-bg">
            <div class="row align-items-center">
                <div class="col-6">
                    <h1>SMK Negeri 4 Tasikmalya <br> <span class="pk fw-bold">Sekolah Pusat Keunggulan</span></h1>
                    <nuxt-link to="/profile/identitasSekolah" class="btn btn-first shadow mb-3">Informasi Sekolah</nuxt-link>
                </div>
                <div class="col-6 text-end">
                    <img src="../assets/img/student.png" alt="student" class="img-fluid">
                </div>
            </div>
        </div>

        <!--Data-->
            <div class="row data m-4 justify-content-center">
                <div class="card card-data rounded-0 shadow col-md-2 col-3">
                    <div class="text-center m-3">
                        <i class="bi bi-person-workspace text-light fs-1"></i>
                        <p class="fs-5 fw-semibold text-light mt-2 mb-0 total">82 Orang</p>
                        <p class="text-light m-0 deskripsi">Guru / Pendidik</p>
                    </div>
                </div>
                <div class="card card-data rounded-0 shadow col-md-2 col-3">
                    <div class="text-center m-3">
                        <i class="bi bi-people-fill text-light fs-1"></i> 
                        <p class="fs-5 fw-semibold text-light mt-2 mb-0 total">1500 Orang</p>
                        <p class="text-light m-0 deskripsi">Siswa</p>
                    </div>
                </div>
                <div class="card card-data rounded-0 shadow col-md-2 col-3">
                    <div class="text-center m-3">
                        <i class="bi bi-person-badge text-light fs-1"></i> 
                        <p class="fs-5 fw-semibold text-light mt-2 mb-0 total">10 Orang</p>
                        <p class="text-light m-0 deskripsi">Staf TU</p>
                    </div>
                </div>
                <div class="card card-data rounded-0 shadow col-md-2 col-3">
                    <div class="text-center m-3">
                        <i class="bi bi-lightbulb text-light fs-1"></i>
                        <p class="fs-5 fw-semibold text-light mt-2 mb-0 total">18</p>
                        <p class="text-light m-0 deskripsi">Ekstrakurikuler</p>
                    </div>
                </div>
            </div>

        <!--Sambutan-->
            <div class="card rounded-4 shadow bg-light">
                <div class="container mb-5">
                    <h4 class="mt-5">Sambutan <br> <span class="text-primary">Kepala Sekolah</span></h4>
                    <div class="row sambutan mt-4 justify-content-center">
                        <div class="col-md-4 mt-4">
                            <div class="card rounded-4 card-img justify-content-center shadow">
                                <img src="../assets/img/kepalasekolah.png" alt="kepsek" class="img-kepsek mt-2">
                            </div>
                        </div>  
                        <div class="col-md-6 p-4">
                            <h3>Kurniawan S.Pd, M.Pd</h3>
                            <p class="mt-4">Assalamualaikum Warahmatullahi Wabarakatuh</p>
                            <p class="mt-4">Segala puji dan syukur kita panjatkan kehadirat Allah SWT, semoga kita semua ada dalam lindungan-Nya. Dan atas perkenan-Nya pula kami dapat menghadirkan website SMK Negeri 4 Tasikmalaya ini. Kami berharap dengan adanya website di SMK Negeri 4 Tasikmalaya ini para pengunjung dapat mengenal lebih jauh tentang sekolah kami sehingga dapat mempererat tali silaturrahmi antara sekolah dengan masyarakat demi kemajuan kita bersama. Tiada gading yang tak retak, website kami ini masih dalam proses pengembangan, masih banyak kekurangan yang harus kami perbaiki. Kritik dan sarannya yang membangun sangat kami harapkan untuk pengembangan ke depan.</p>
                            <p class="mt-4">Akhirnya, saya mengucapkan terimakasih yang sebesar-besarnya kepada semua pihak yang tidak dapat disebutkan satu segala bantuan dan persatu atas fasilitasnya yang telah diberikan semoga semua yang kita lakukan bermanfaat bagi masyarakat.</p>
                            <p class="mt-4">Wassalamu'alaikum Warahmatullahi Wabarakatuh.</p>
                        </div>
                    </div>
                </div>
            </div>

        <!--Konsentrasi Keahlian-->
        <div class="bg">
            <div class="container">
                <h4 class="">Konsentrasi <br> <span class="text-primary">Keahlian</span></h4>
                <div class="jurusan mt-5">
                    <div class="row m-3 justify-content-center gap-4">
                        <div class="card col-md-3 rounded-4">
                            <div class="card-body">
                                <img src="../assets/img/jurusan/tjkt.png" alt="img" class="mt-5">
                                <h5 class="fw-semibold">TJKT</h5>
                                <p>Teknik Jaringan, Komputer dan Telekomunikasi</p>
                            </div>
                        </div>
                        <div class="card col-md-3 rounded-4">
                            <div class="card-body">
                                <img src="../assets/img/jurusan/pplg.png" alt="img" class="mt-5">
                                <h5 class="fw-semibold">PPLG</h5>
                                <p>Pengembangan Perangkat Lunak dan Gim</p>
                            </div>
                        </div>
                        <div class="card col-md-3 rounded-4">
                            <div class="card-body">
                                <img src="../assets/img/jurusan/tbsm.png" alt="img" class="mt-5">
                                <h5 class="fw-semibold">TBSM</h5>
                                <p>Teknik dan Bisnis Sepeda Motor</p>
                            </div>
                        </div>
                    </div>
                    <div class="row m-3 mt-4 justify-content-center mb-5 gap-4">
                        <div class="card col-md-3 rounded-4">
                            <div class="card-body">
                                <img src="../assets/img/jurusan/dkv.png" alt="img" class="mt-5">
                                <h5 class="fw-semibold">DKV</h5>
                                <p>Desain Komunikasi Visual</p>
                            </div>
                        </div>
                        <div class="card col-md-3 rounded-4">
                            <div class="card-body">
                                <img src="../assets/img/jurusan/toi.png" alt="img" class="mt-5">
                                <h5 class="fw-semibold">TOI</h5>
                                <p>Teknik Otomasi Industri</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
            

        <!--Berita-->
        <div class="container">
            <h4 class="mt-5">Berita <br> <span class="text-primary">Terbaru</span></h4>
            <span class="text-berita">
                <p class="mt-3">Berita terbaru, cerita inspiratif dan informasi terkini seputar kegiatan serta prestasi sekolah kami.</p>
            </span>
            <div class="row m-2 berita justify-content-center">
                <div class="col-md-5">
                    <div class="card mt-3 rounded-4">
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
                    <div class="card mt-3 rounded-4">
                        <img src="~/assets/img/artikel/expocreannnova.jpg" class="card-img-top p-2 rounded-4" alt="img-artikel">
                        <div class="card-body">
                            <p class="text-end">Senin 27 Feb 2023</p>
                            <h5 class="text-center mt-1">Siswa SMKN 4 Tasikmalaya Adu Inovasi dan Kreativitas di Expo Creanova</h5>
                            <a href="https://radartasik.id/2023/03/02/siswa-smkn-4-tasikmalaya-adu-inovasi-dan-kreativitas-di-expo-creanova/" target="_blank"><p class="mt-4">Baca Selengkapnya <span><i class="bi bi-arrow-right-circle text-black"></i></span></p>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="text-center mt-5">
                <nuxt-link to="../berita" class="btn btn-berita shadow">Berita Lainnya</nuxt-link>
            </div>
        </div>
        
    </div>
</template>

<style scoped>
.diagonal-bg {
  position: relative;
  overflow: hidden;
  background: linear-gradient(to bottom right, transparent 50%, rgb(31, 96, 160) 50%);
  border-radius: 10px; /* Opsional untuk sudut melengkung */
}

.diagonal-bg .row {
  position: relative;
  z-index: 2; /* Konten di atas background */
}

.diagonal-bg::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(to bottom right, transparent 50%, rgb(31, 96, 160) 50%);
  z-index: 1;
}

.carousel img {
    width: 450px;
}


.bg {
    background-image: url('../assets/img/background-transformed.png');
    background-position: center top;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    padding-top: 5rem;
    width: 100%;
}

.container {
    padding-top: 0; /* Optional: Adjust padding if needed */
}

.col {
    padding: 0;
}

.text {
    margin-left: 100px;
    margin-right: 0;
}

h1 {
    width: fit-content;
    font-family: "Poppins", serif;
    margin-left: 50px;
}

h6, h5, h4, h3, p, .btn {
    font-family: "Poppins", serif;
}

h5 {
    color: #ffff;
    margin-top: 120px;
}

.berita i {
    color: #ffff;
    margin-top: 120px;
    margin-left: 10px;
}

.info {
    margin-left: 100px;
}

h4 {
    margin-left: 95px;
}

.card-img {
    height: 250px;
    width: 85%;
    margin: auto;
    /* margin-left: 70px; */
}

.sambutan p {
    font-size: 13px;
}

.card-img img {
    width: 95%;
    margin-left: 10px;
    margin-bottom: 58px;
}

.card-item .card {
    width: 70%;
    height: 200px;
}

.jurusan .card {
    background-color: transparent;
    backdrop-filter: blur(5px);
    border: 3px solid #ffff;
    text-align: center;
}

.card-body h5 {
    margin-top: 30px;
    color: #000;
}

.card-body p {
    font-size: 15px;
}

.card-body img {
    width: 100px;
}

.text-berita p {
    margin-left: 95px;
    max-width: 30%;
}

.card-img-top {
    width: 100%;
    height: 250px;
}

.berita .card {
    background-color: transparent;
    backdrop-filter: blur(20px);
    border: 2px solid #ffff;
}

a {
    color: #000 !important;
    text-decoration: none;
}

.btn-first {
    color: #ffff !important;
    width: 200px;
    margin-top: 80px;
    margin-left: 50px;
}

.btn {
    color: #ffff !important;
    width: 200px;
    background-color: #1F60A0;
}

.card-data,.card-img {
    background-color: #1F60A0;
}

.pk {
    color: #1F60A0;
}

@media only screen and (min-width: 600px) and (max-width: 890px) {
    .card-data .total {
        font-size: small !important;
    }

    .card-data .deskripsi {
        font-size: smaller !important;
    }

    h4, .text-berita p {
        margin-left: 30px;
    }

    .card-img {
        height: 200px;
        margin: auto;
    }

    .card-img img {
        width: 100%;
        margin-left: 5px;
        margin-top: 65px !important;
    }

    .card-body h5 {
        color: #000;
    }

    .card-body p {
        font-size: small;
    }

    .card-body img {
        width: 70px;
    }

    .card-img-top {
        width: 100%;
        height: 170px;
    }

    .berita p, .berita a {
        font-size: small;
    }

    .berita h5 {
        font-size: medium;
    }

    .berita i {
        margin-left: 5px;
    }

}


@media only screen and (max-width: 600px) {
    .carousel h1 {
        font-size: medium !important;
        margin-top: 30px;
        margin-left: 30px;
    }

    .btn-first {
        margin-left: 30px;
        margin-top: 30px;
        font-size: 10px;
        width: 120px;
    }

    .card-data .total {
        font-size: 8px !important;
    }

    .card-data .deskripsi {
        font-size: 6px !important;
    }

    .card-data i {
        font-size: 10px;
    }

    h4 {
        margin-left: 35px;
    }

    .card-img {
        height: 170px;
        width: 50%;
        margin: auto;
    }

    .sambutan h3 {
        font-size: 20px;
    }

    .sambutan p {
        font-size: 15px;
    }

    .card-img img {
        width: 100%;
        margin-left: 5px;
        margin-top: 35px !important;
    }

    .text-berita p {
        margin-left: 35px;
        max-width: 50%;
        font-size: small;
    }

    .card-img-top {
        width: 100%;
        height: 200px;
    }

    .berita p, .berita a {
        font-size: small;
    }

    .berita h5 {
        font-size: medium;
    }

    .berita i {
        margin-left: 5px;
    }

    .btn-berita {
        margin-left: 0;
        margin-top: 0 !important;
        font-size: small;
        width: 130px;
    }

}
 
</style>