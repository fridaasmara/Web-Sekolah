<template>
    <div class="container">
        <h4 class="mt-5">Artikel <br> <span class="text-primary">Terbaru</span></h4>
            <span class="text-artikel">
                <p class="mt-3">Berita terbaru, cerita inspiratif dan informasi terkini seputar kegiatan serta prestasi sekolah kami.</p>
            </span>
        <div class="row justify-content-center">
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
    </div>
</template>

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

</style>