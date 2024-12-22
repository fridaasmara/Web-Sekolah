<template>
    <div class="container">
        <h4 class="mt-5">Prestasi</h4>
        <div class="row mt-5 justify-content-center">
                <div class="col-10 col-md-5">
                    <div class="card rounded-4">
                        <img src="~/assets/img/school.jpeg" class="card-img-top p-2 rounded-4" alt="img-artikel">
                        <div class="card-body">
                            <p class="text-end">20 Desember 2024</p>
                            <h5 class="text-center mt-1">Prestasi 1</h5>
                        </div>
                    </div>
                </div>
                <div class="col-10 col-md-5">
                    <div class="card rounded-4">
                        <img src="~/assets/img/school.jpeg" class="card-img-top p-2 rounded-4" alt="img-artikel">
                        <div class="card-body">
                            <p class="text-end">20 Desember 2024</p>
                            <h5 class="text-center mt-1">Pretasi 2</h5>
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
        height: 200px;
    }

    .card {
        margin-top: 20px;
    }
}

</style>