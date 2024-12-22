<template>
    <div class="container">
        <h4 class="mt-5">Guru & <br> <span class="text-primary">Staf TU</span></h4>
            <div class="row mt-5 d-flex justify-content-center">
                <div class=" col-6 col-sm-3">
                    <div class="card card-total rounded-4">
                        <div class="card-body">
                            <!-- <img src="../assets/img/icon-tjkt.png" alt="img" class="mt-5"> -->
                            <h5 class="fw-semibold">80 Orang</h5>
                            <p>Total Guru / Pendidik</p>
                        </div>
                    </div>
                </div>
                <div class="col-6 col-sm-3">
                    <div class="card card-total rounded-4">
                        <div class="card-body">
                            <!-- <img src="../assets/img/icon-tjkt.png" alt="img" class="mt-5"> -->
                            <h5 class="fw-semibold">5 Orang</h5>
                            <p>Total Guru BP / BK</p>
                        </div>
                    </div>
                </div>
                <div class="col-6 col-sm-3">
                    <div class="card card-total rounded-4">
                        <div class="card-body">
                            <!-- <img src="../assets/img/icon-tjkt.png" alt="img" class="mt-5"> -->
                            <h5 class="fw-semibold">15 Orang</h5>
                            <p>Total Staf TU</p>
                        </div>
                    </div>
                </div>
            </div>

            <!--Daftar Guru-->
            <div class="card card-guru mt-5">
                <h5 class="text-center mt-5">Daftar Guru / Pendidik</h5>
                <div class="row mt-4 justify-content-center mb-5">
                    <div class="col-6 col-sm-3">
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="mt-3">
                                <h5 class="fw-semibold mt-4">Nama Guru</h5>
                                <p>Guru Mapel</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-6 col-sm-3">
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="mt-3">
                                <h5 class="fw-semibold mt-4">Nama Guru</h5>
                                <p>Guru Mapel</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-6 col-sm-3">
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="mt-3">
                                <h5 class="fw-semibold mt-4">Nama Guru</h5>
                                <p>Guru Mapel</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!--Daftar Guru BP / BK-->
            <div class="card card-guru mt-4">
                <h5 class="text-center mt-5">Daftar Guru BP / BK</h5>
                <div class="row mt-4 justify-content-center mb-5">
                    <div class="col-6 col-sm-3">
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="mt-3">
                                <h5 class="fw-semibold mt-4">Nama Guru</h5>
                                <p>Guru BP / BK</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-6 col-sm-3">
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="mt-3">
                                <h5 class="fw-semibold mt-4">Nama Guru</h5>
                                <p>Guru BP / BK</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-6 col-sm-3">
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="mt-3">
                                <h5 class="fw-semibold mt-4">Nama Guru</h5>
                                <p>Guru BP / BK</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!--Daftar Staf TU-->
            <div class="card card-guru mt-4">
                <h5 class="text-center mt-5">Daftar Staf TU</h5>
                <div class="row mt-4 justify-content-center mb-5">
                    <div class="col-6 col-sm-3">
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="mt-3">
                                <h5 class="fw-semibold mt-4">Nama Guru</h5>
                                <p>Staf TU</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-6 col-sm-3">
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="mt-3">
                                <h5 class="fw-semibold mt-4">Nama Guru</h5>
                                <p>Staf TU</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-6 col-sm-3">
                        <div class="card rounded-4">
                            <div class="card-body">
                                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="mt-3">
                                <h5 class="fw-semibold mt-4">Nama Guru</h5>
                                <p>Staf TU</p>
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

/* .flex-container {
    display: flex;
    flex-direction: column;
    gap: 20px; /* Space between rows */
/* } */ 


.card-total {
    background-color: #1F60A0;
    /* padding: 20px; */
    text-align: center;
}

.card-total h5 {
    margin-top: 30px;
    color: #fff;
}

.card-total p {
    color: #fff;
    font-size: 15px;
}

.card-guru {
    width: 85%;
    margin: auto;
    text-align: center;
}

img {
    width: 100px;
}

/* .card-body img {
    width: 80px;
} */

@media only screen and (max-width: 600px) {
    h4 {
        margin-left: 35px;
    }

    .card-body h5, .card-body p {
        font-size: small;
    }

    .card {
        margin-top: 10px;
    }
    
}

</style>
