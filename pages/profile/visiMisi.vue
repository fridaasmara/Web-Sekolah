<template>
    <div class="container">
        <h4 class="mt-5">Visi & <br> <span class="text-primary">Misi</span></h4>

        <div class="mt-5">
            <div class="card card-visi bg-light text-center rounded-4">
                <h5 class="fw-semibold mt-4">Visi</h5>
                <p class="mt-3 mb-4 first">Terwujudnya lulusan yang Cerdas, Aktif, Kompetitif, Adaptif dan Produktif berlandaskan Iman dan Takwa <br> (CAKAP BERIMTAK)</p>
            </div>
            <div class="card bg-light mt-5 rounded-4">
                <h5 class="fw-semibold text-center mt-4">Misi</h5>
                <ul class="list-group mt-3 mb-4 second">
                    <li class="list-group-item"><p>1. Menyiapkan Sumber Daya Manusia yang cerdas dan kompeten baik hardskill maupun softskill.</p></li>
                    <li class="list-group-item"><p>2. Meningkatkan dan mengembangkan aktifitas serta kreatifitas seluruh warga sekolah dalam berbagai kegiatan positif.</p></li>
                    <li class="list-group-item"><p>3. Mewujudkan manajemen pengelolaan yang efektif, efesien, transparan, akuntabel dan layanan prima.</p></li>
                    <li class="list-group-item"><p>4. Menumbuhkan dan mengembangkan potensi dan kemampuan Sumber Daya Manusia yang berdaya saing tinggi melalui berbagai kegiatan akademik maupun non akademik.</p></li>
                    <li class="list-group-item"><p>5. Menyelenggarakan berbagai program kegiatan dalam upaya meningkatkan Sumber Daya Manusia yang mampu menyesuaikan dengan perkembangan.</p></li>
                    <li class="list-group-item"><p>6. Mengembangkan sarana prasarana dan lingkungan sekolah yang menyenangkan sebagai wadah menumbuhkembangkan daya kreasi dan inovasi untuk menghasilkan produk teknologi tepat guna.</p></li>
                    <li class="list-group-item"><p>7. Membangun jiwa wirausaha yang handal melalui pembelajaran Teaching Factory (TEFA) dan Kelas Industri.</p></li>
                    <li class="list-group-item"><p>8. Menjalin dan mengembangkan kemitraan dengan Industri dan Dunia Kerja (IDUKA) serta lembaga lainnya yang relevan.</p></li>
                    <li class="list-group-item"><p>9. Menanamkan dan membudayakan sikap dan perilaku yang baik pada aktivitas di sekolah maupun dalam kehidupan sehari-hari.</p></li>
                </ul>
            </div>
        </div>
    </div>
</template>


<style scoped>
h4, h5, p {
    font-family: "Poppins", serif;
}

h4 {
    margin-left: 95px;
}

.card {
    background-color: transparent;
    backdrop-filter: blur(20px);
    border: 2px solid #ffff;
    width: 85%;
    margin: auto;
}

.card-visi {
    background-color: #1F60A0 !important;
    color: #ffff;
}

.list-group {
    border: none;
}

.list-group-item {
    border: none;
    margin-left: 0;
    background-color: transparent;
}

.first, .second {
    width: 85%;
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

    p {
        font-size: small;
        margin-top: 10px !important;
    }

    .list-group-item p {
        margin-top: 0 !important;
    }
}
</style>