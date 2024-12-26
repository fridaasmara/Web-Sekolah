<template>
    <div class="container">
        <h4 class="mt-5">Guru & <br> <span class="text-primary">Staf TU</span></h4>
            <div class="row mt-5 d-flex justify-content-center">
                <div class=" col-6 col-sm-3">
                    <div class="card card-total rounded-4">
                        <div class="card-body">
                            <h5 class="fw-semibold">1500 Orang</h5>
                            <p>Total Peserta Didik</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row mt-5 d-flex justify-content-center">
                <div class="col-6 col-sm-3">
                    <div class="card card-total rounded-4">
                        <div class="card-body">
                            <h5 class="fw-semibold">15 Rombel</h5>
                            <p>Kelas X (Sepuluh)</p>
                        </div>
                    </div>
                </div>
                <div class="col-6 col-sm-3">
                    <div class="card card-total rounded-4">
                        <div class="card-body">
                            <h5 class="fw-semibold">15 Rombel</h5>
                            <p>Kelas XI (Sebelas)</p>
                        </div>
                    </div>
                </div>
                <div class="col-6 col-sm-3">
                    <div class="card card-total rounded-4">
                        <div class="card-body">
                            <h5 class="fw-semibold">15 Rombel</h5>
                            <p>Kelas XII (Dua Belas)</p>
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
