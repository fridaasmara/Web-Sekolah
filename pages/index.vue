<template>
    <div class="container-fluid p-0">

        <!--Carousel-->
        <div class="carousel">
            <div class="row">
                <div class="col">
                    <div class="text">
                        <h1>Selamat datang di Website Resmi</h1>
                        <h1 class="mt-2">SMK Negeri 4 Tasikmalaya</h1>
                    </div>
                    <div class="d-flex info">
                        <h5>Informasi Sekolah</h5>
                        <i class="bi bi-arrow-right"></i>
                    </div>
                </div>
            </div>
        </div>

        <!--Sambutan-->
            <div class="card bg-light">
                <div class="container mb-5">
                    <h4 class="mt-5">Sambutan <br> <span class="text-primary">Kepala Sekolah</span></h4>
                    <div class="row mt-5 justify-content-center">
                        <div class="col-5">
                            <h3>Kurniawan S.Pd, M.Pd</h3>
                            <p class="mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. In molestiae natus cumque odit doloremque atque a iste? Dolor iure eius asperiores nobis eum modi in perferendis, libero, expedita facilis repellendus?</p>
                            <p class="mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. In molestiae natus cumque odit doloremque atque a iste? Dolor iure eius asperiores nobis eum modi in perferendis, libero, expedita facilis repellendus?</p>
                        </div>
                        <div class="col-5">
                            <div class="card card-img bg-primary justify-content-center">
                                <img src="../assets/img/kepala-sekolah.png" alt="img">
                            </div>
                        </div>  
                    </div>
                </div>
            </div>

        <!--Konsentrasi Keahlian-->
            <div class="container">
                <h4 class="mt-5">Konsentrasi <br> <span class="text-primary">Keahlian</span></h4>
                <div class="flex-container mt-5">
                    <div class="row">
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="../assets/img/icon-tjkt.png" alt="img" class="mt-5">
                                <h5 class="fw-semibold">TJKT</h5>
                                <p>Teknik Jaringan, Komputer dan Telekomunikasi</p>
                            </div>
                        </div>
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="../assets/img/icon-pplg.png" alt="img" class="mt-5">
                                <h5 class="fw-semibold">PPLG</h5>
                                <p>Pengembangan Perangkat Lunak dan Gim</p>
                            </div>
                        </div>
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="../assets/img/icon-tbsm.png" alt="img" class="mt-5">
                                <h5 class="fw-semibold">TBSM</h5>
                                <p>Teknik dan Bisnis Sepeda Motor</p>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="../assets/img/icon-dkv.png" alt="img" class="mt-5">
                                <h5 class="fw-semibold">DKV</h5>
                                <p>Desain Komunikasi Visual</p>
                            </div>
                        </div>
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="../assets/img/icon-toi.png" alt="img" class="mt-5">
                                <h5 class="fw-semibold">TOI</h5>
                                <p>Teknik Otomasi Industri</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        <!--Artikel-->
        <div class="container">
            <h4 class="mt-5">Artikel <br> <span class="text-primary">Terbaru</span></h4>
            <span class="text-artikel">
                <p class="mt-3">Berita terbaru, cerita inspiratif dan informasi terkini seputar kegiatan serta prestasi sekolah kami.</p>
            </span>
            <div class="row artikel justify-content-center">
                <div class="col-5">
                    <div class="card rounded-4">
                        <img src="~/assets/img/school.jpeg" class="card-img-top p-2 rounded-4" alt="img-artikel">
                        <div class="card-body">
                            <p class="text-end">20 Desember 2024</p>
                            <h5 class="text-center mt-1">SMKN 4 Tasikmalaya Koneksikan Iduka dengan Pencari Kerja</h5>
                            <p class="mt-4">Baca Selengkapnya <span><i class="bi bi-arrow-right-circle text-black"></i></span></p>
                        </div>
                    </div>
                </div>
                <div class="col-5">
                    <div class="card rounded-4">
                        <img src="~/assets/img/school.jpeg" class="card-img-top p-2 rounded-4" alt="img-artikel">
                        <div class="card-body">
                            <p class="text-end">20 Desember 2024</p>
                            <h5 class="text-center mt-1">SMKN 4 Tasikmalaya Koneksikan Iduka dengan Pencari Kerja</h5>
                            <p class="mt-4">Baca Selengkapnya <span><i class="bi bi-arrow-right-circle text-black"></i></span></p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="text-center mt-5">
                <button class="btn btn-primary shadow">Artikel Lainnya</button>
            </div>
        </div>
        
    </div>
</template>

<style scoped>
.carousel {
    background-image: url('../assets/img/school.jpeg');
    background-size: cover;
    height: 500px;
    width: 100%;
}

.col {
    padding: 0;
}

.text {
    margin-left: 100px;
    margin-right: 0;
}

h1 {
    background-color: #1F60A0;
    width: fit-content;
    color: #ffff;
    font-family: "Poppins", serif;
    margin-top: 100px;
}

h6, h5, h4, h3, p, .btn {
    font-family: "Poppins", serif;

}

h5 {
    color: #ffff;
    margin-top: 120px;
}

i {
    color: #ffff;
    margin-top: 120px;
    margin-left: 10px;
}

.info {
    margin-left: 100px;
}

img {
    width: 200px;
}

h4 {
    margin-left: 95px;
}

.card-img {
    height: 300px;
    width: 80%;
    margin-left: 70px;
}

.card-img img {
    width: 95%;
    margin-bottom: 40px;
}

.card-item .card {
    width: 70%;
    height: 200px;
}

.flex-container {
    display: flex;
    flex-direction: column;
    gap: 20px; /* Space between rows */
}

.flex-container .row {
    display: flex;
    justify-content: center;
    gap: 20px; /* Space between cards */
}


.flex-container .card {
    background-color: transparent;
    backdrop-filter: blur(20px);
    border: 1px solid #ffff;
    /* padding: 20px; */
    text-align: center;
    flex: 1; /* Cards take equal space */
    max-width: 25%; /* Adjust card width */
}

.card-body h5 {
    margin-top: 30px;
    color: #000;
}

.card-body p {
    font-size: 15px;
}

.card-body img {
    width: 80px;
}

.text-artikel p {
    margin-left: 95px;
    max-width: 30%;
}

/* .img-artikel {
    background-image: url('../assets/img/school.jpeg');
    background-size: cover;
    height: 200px;
    width: 100%;
} */

.card-img-top {
    width: 100%;
    height: 250px;
}

.artikel .card {
    background-color: transparent;
    backdrop-filter: blur(20px);
    border: 2px solid #ffff;
}

</style>