<template>
    <div class="bg">
        <div class="container">
            <h4 class="mt-5">Konsentrasi <br> <span class="text-primary">Keahlian</span></h4>
            <div class="card rounded-2 mt-5">
                <div class="card-body p-2 mt-1">
                    <div class="row p-3">
                        <div class="col-4 text-center">
                            <img src="~/assets/img/icon/icon-tjkt.png" alt="">
                        </div>
                        <div class="col-8">
                            <h5 class="fw-semibold">Teknik Jaringan, Komputer dan Telekomunikasi (TJKT)</h5>
                            <p class="mt-4">Konsentrasi ini fokus pada perancangan, pengelolaan, dan pemeliharaan jaringan komputer serta teknologi telekomunikasi. Siswa dilatih untuk menguasai teknik instalasi jaringan, administrasi server, dan troubleshooting perangkat jaringan.</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card rounded-2 mt-4">
                <div class="card-body p-2 mt-1">
                    <div class="row p-3">
                        <div class="col-4 text-center">
                            <img src="~/assets/img/icon/icon-pplg.png" alt="">
                        </div>
                        <div class="col-8">
                            <h5 class="fw-semibold">Pengembangan Perangkat Lunak dan Gim (PPLG)</h5>
                            <p class="mt-4">Bidang ini mempersiapkan siswa untuk merancang, mengembangkan, dan mengelola perangkat lunak dan gim. Siswa akan belajar bahasa pemrograman, pengembangan aplikasi, desain gim, serta pengelolaan proyek teknologi.</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card rounded-2 mt-4">
                <div class="card-body p-2 mt-1">
                    <div class="row p-3">
                        <div class="col-4 text-center">
                            <img src="~/assets/img/icon/icon-tbsm.png" alt="">
                        </div>
                        <div class="col-8">
                            <h5 class="fw-semibold">Teknik dan Bisnis Sepeda Motor (TBSM)</h5>
                            <p class="mt-4">Konsentrasi ini mengajarkan keterampilan teknis dalam perbaikan, perawatan, dan modifikasi sepeda motor, serta pengetahuan bisnis dan kewirausahaan di bidang otomotif roda dua.</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card rounded-2 mt-4">
                <div class="card-body p-2 mt-1">
                    <div class="row p-3">
                        <div class="col-4 text-center">
                            <img src="~/assets/img/icon/icon-dkv.png" alt="">
                        </div>
                        <div class="col-8">
                            <h5 class="fw-semibold">Desain Komunikasi Visual (DKV)</h5>
                            <p class="mt-4">Bidang ini berfokus pada pengembangan kemampuan kreatif dalam desain grafis, ilustrasi, animasi, dan media komunikasi visual untuk berbagai kebutuhan industri kreatif.</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card rounded-2 mt-4">
                <div class="card-body p-2 mt-1">
                    <div class="row p-3">
                        <div class="col-4 text-center">
                            <img src="~/assets/img/icon/icon-toi.png" alt="">
                        </div>
                        <div class="col-8">
                            <h5 class="fw-semibold">Teknik Otomasi Industri (TOI)</h5>
                            <p class="mt-4">Konsentrasi ini mendalami teknologi otomasi di industri, meliputi pemrograman PLC, robotika, dan sistem kontrol otomatis untuk meningkatkan efisiensi dan produktivitas di sektor manufaktur.</p>
                        </div>
                    </div>
                </div>
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
    backdrop-filter: blur(5px);
    border: 2px solid #ffff;
    width: 85%;
    margin: auto;
}

img {
    width: 100px;
}

p {
    font-size: 15px;
}

.bg {
    background-image: url('~/assets/img/background2-transformed.png');
    background-position: center top;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    width: 100%;
}

@media only screen and (max-width: 600px) {
    p{
        font-size: small;
    }

    h5 {
        font-size: medium;
    }
    
    h4 {
        margin-left: 35px;
    }

    img {
        width: 50px;
    }
}

</style>