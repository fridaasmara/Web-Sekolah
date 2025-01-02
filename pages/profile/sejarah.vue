<template>
    <div class="container">
        <h4 class="mt-5">Sejarah <br> <span class="text-primary">Sekolah</span></h4>

        <div class="card bg-light rounded-4 mt-5">
            <div class="row mt-5">
                <div class="col text-center">
                    <img src="~/assets/img/sejarahsmkn4.jpg" alt="img" class="rounded-4">
                </div>
            </div>
            <div class="p-5">
                <div class="first">
                    <h5 class="fw-semibold">Latar Belakang</h5>
                    <p class="mt-4">Sejalan dengan Program Pemerintah dibidang pendidikan Menengah Kejuruan pada saat itu yakni pemerataan akses ditambah pula dengan banyaknya keinginan masyarakat yang mengharapkan adanya SMK Negeri di daerah Kecamatan Purbaratu Kota  Tasikmalaya, terutama untuk menampung tamatan dari SLTP yang ingin melanjutkan ke SMK maka beberapa tokoh masyarakat, unsur pejabat pemerintah di Kecamatan Purbaratu Kota Tasikmalaya mengusulkan kepada pemerintah Kota Tasikmalaya dan Pemerintah Provinsi Jawa Barat, agar berdirinya SMK Negeri di Kecamatan Purbaratu Kota Tasikmalaya.</p>
                </div>
            
                <div class="second">
                    <h5 class="mt-5 fw-semibold">Mulai Berdiri</h5>
                    <p class="mt-4">Setelah melalui perjuangan yang sangat panjang dari berbagai pihak khususnya Disdik Kota Tasikmalaya dan pihak-pihak terkait lainnya sesuai prosedur dan ketentuan yang berlaku pada waktu itu dengan mengucapkan syukur Alhamdulillah akhirnya pada tahun pelajaran 2010/2011 SMK Negeri 4 Tasikmalaya mulai berdiri, pada awalnya membuka Kompetensi Keahlian Teknik Komputer dan Jaringan dengan pendaftar peserta Didik Baru pada waktu itu berjumlah 44 orang. Pada awalnya tempat belajar menumpang di SMP Negeri 17 Kota Tasikmalaya, dan sekolah induknya adalah SMK Negeri 2 Kota Tasikmalaya, Untuk Tenaga pendidik dan Tenaga Kependidikan masih dibantu sepenuhnya oleh kedua sekolah tersebut.</p>
                    <p class="mt-4">Pada tahun 2012 keluarlah surat Izin Pendirian berdasarkan keputusan kepala Badan Pelayanan Perizinan Terpadu Kota Tasikmalaya No. 420/9/SK-BPPT/2012 Tanggal 06 Februari 2012.</p>
                </div>
            </div>
        </div>

    </div>
</template>

<script setup>
useHead({ title: "Sejarah - SMKN 4 Tasikmalaya" })

</script>

<style scoped>
h4, h5, p {
    font-family: "Poppins", serif;
}

h4 {
    margin-left: 95px;
}

img {
    width: 80%;
}

.card {
    background-color: transparent;
    backdrop-filter: blur(20px);
    border: 2px solid #ffff;
    width: 85%;
    margin: auto;
}

.text-primary {
    color: #1F60A0 !important;
}

@media only screen and (min-width: 600px) and (max-width: 890px) {
    h4 {
        margin-left: 30px;
    }

}

@media only screen and (max-width: 600px) {
    p {
        font-size: smaller;
    }
    
    h4 {
        margin-left: 35px;
    }

    h5 {
        font-size: medium;
    }
}

</style>