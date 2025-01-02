<template>
    <div class="container-fluid p-0 mt-5">
        <div class="card">
            <div class="container mt-5">
                <div class="row justify-content-center one">
                    <div class="col-md-5">
                        <h5>Alamat</h5>
                        <hr>
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3957.2131636317426!2d108.25189907404213!3d-7.32993997208793!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e6f59eeb6bda36f%3A0xa9e724a275da6c2d!2sSMK%20Negeri%204%20Tasikmalaya!5e0!3m2!1sid!2sid!4v1734660682140!5m2!1sid!2sid" width="600" height="450"  loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                    </div>
                    <div class="col-md-4">
                        <h5>Kontak</h5>
                        <hr>
                        <a href="tel:++62265312059">
                            <div class="d-flex">
                                <i class="bi bi-telephone"></i>                                
                                <h6>0265312059</h6>
                            </div>
                        </a>
                        <a href="mailto:info@smkn4-tsm.sch.id">
                            <div class="d-flex">
                                <i class="bi bi-envelope"></i>
                                <h6>info@smkn4-tsm.sch.id</h6>
                            </div>
                        </a>
                        <h5 class="mt-5">Media <span class="text-primary">Sosial</span></h5> 
                        <hr>
                        <div class="d-flex sosmed">
                            <a href="https://www.facebook.com/4smkn/" target="_blank"><i class="bi bi-facebook"></i></a>
                            <a href="https://www.instagram.com/smkn4tsmofficial?igsh=N3k1MTlyeXo4cW9q" target="_blank"><i class="bi bi-instagram"></i></a>
                            <a href="https://www.tiktok.com/@smkn4tasikmalaya?is_from_webapp=1&sender_device=pc" target="_blank"><i class="bi bi-tiktok"></i></a>
                            <a href="https://www.youtube.com/@smkn4tasikmalayamediaoffic704" target="_blank"><i class="bi bi-youtube"></i></a>
                        </div>               
                    </div>
                    <div class="col-md-2">
                        <h5>Link <span class="text-primary">Lainnya</span></h5>
                        <hr>
                        <ul class="list-group">
                            <li class="list-group-item"><a href="https://www.kemdikbud.go.id/" target="_blank">Kemdikbud</a></li>
                            <li class="list-group-item"><a href="https://dapo.dikdasmen.kemdikbud.go.id/" target="_blank">Dapodiknasmen</a></li>
                            <li class="list-group-item"><a href="https://psmk.kemdikbud.go.id/" target="_blank">PSMK</a></li>
                            <li class="list-group-item"><a href="https://disdik.jabarprov.go.id/" target="_blank">Disdik Jabar</a></li>
                        </ul>
                    </div>
                </div>
                <div class="row mt-5">
                    <div class="col">
                        <hr>
                        <p class="text-center">© {{ year }}. SMK Negeri 4 Tasikmalaya. <br> All rights reserved.</p>
                        <hr>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
let year = new Date().getFullYear() 
</script>

<style scoped>
iframe {
    width: 90%;
    height: 350px
}


h5, .list-group-item, h6, p {
    font-family: "Poppins", serif;

}

.list-group-item {
    border: none;
    margin-left: 0;
}

h6 {
    margin-top: 5px;
    margin-left: 10px;
}

.sosmed i {
    margin-right: 20px;
}

i {
    font-size: 20px;
}

.one hr {
    width: 80%;
}

a {
    color: #000 !important;
    text-decoration: none;
}

.text-primary {
    color: #1F60A0 !important;
}

@media only screen and (min-width: 600px) and (max-width: 890px) {
    iframe {
        width: 80%;
        height: 200px
    }

    .list-group-item, h6 {
        font-size: smaller;
    }

    h5 {
        font-size: medium;
    }
}

@media only screen and (max-width: 600px) {
    iframe {
        width: 80%;
        height: 250px
    }

    h5 {
        font-size: medium;
        margin-top: 30px;
    }

    .one {
        margin-left: 20px;
    }

    .list-group-item, h6 {
        font-size: small;
    }

    p {
        font-size: small;
    }
}


</style>