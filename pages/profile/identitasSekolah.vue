<template>
    <div class="container">
        <h4 class="mt-5">Identitas <br> <span class="text-primary">Sekolah</span></h4>
            <div class="text-center">
                <img src="~/assets/img/LOGO-SMK4.png" alt="logo" class="mt-4">
            </div>
            <div class="card bg-light shadow rounded-4 mt-5">
                <table class="table m-3">
                    <tbody>
                        <tr>
                            <td>Nama Sekolah</td>
                            <td>:</td>
                            <td>SMK Negeri 4 Kota Tasikmalaya</td>
                        </tr>
                        <tr>
                            <td>NPSN</td>
                            <td>:</td>
                            <td>20276063</td>
                        </tr>
                        <tr>
                            <td>Alamat</td>
                            <td>:</td>
                            <td>Jl Depok RT 02 RW 05, Kelurahan Sukamenak, Kecamatan Purbaratu, <br> Kota Tasikmalaya, Provinsi Jawabarat</td>
                        </tr>
                        <tr>
                            <td>Telp/faks</td>
                            <td>:</td>
                            <td>(0265) 7528981</td>
                        </tr>
                        <tr>
                            <td>Email</td>
                            <td>:</td>
                            <td>info@smkn4-tsm.sch.id</td>
                        </tr>
                        <tr>
                            <td>Tahun Berdiri/Beroperasi</td>
                            <td>:</td>
                            <td>2010</td>
                        </tr>
                        <tr>
                            <td>Nomor SK Pendirian</td>
                            <td>:</td>
                            <td>420/9/SK-BPPT/2012</td>
                        </tr>
                        <tr>
                            <td>Tanggal SK Pendirian</td>
                            <td>:</td>
                            <td>06 Februari 2012</td>
                        </tr>
                        <tr>                            
                            <td>Kepemilikan</td>
                            <td>:</td>
                            <td>Pemerintah Daerah</td>
                        </tr>
                    </tbody>
                </table>
            </div>
    </div>
</template>

<script setup>
useHead({ title: "Identitas Sekolah - SMKN 4 Tasikmalaya" })

</script>

<style scoped>
h4, .table {
    font-family: "Poppins", serif;
}

h4 {
    margin-left: 95px;
}

img {
    width: 150px;
}

.card {
    background-color: transparent;
    backdrop-filter: blur(20px);
    border: 2px solid #ffff;
    width: 90%;
    margin: auto;
}

td {
    border-bottom: none;
    padding-left: 60px;
}

.text-primary {
    color: #1F60A0 !important;
}

@media only screen and (min-width: 600px) and (max-width: 890px) {
    h4 {
        margin-left: 30px;
    }

    td {
        border-bottom: none;
        padding-left: 30px;
    }

}

@media only screen and (max-width: 600px) {
    td {
        font-size: smaller;
        padding-left: 0;
    }

    h4 {
        margin-left: 35px;
    }

    img {
        width: 100px;
    }
}

</style>