<template>
    <div class="container">
        <h4 class="mt-5">Identitas <br> <span class="text-primary"> Kepala Sekolah</span></h4>
        <div class="text-center">
            <img src="~/assets/img/kepala-sekolah.png" alt="logo" class="mt-5 bg-primary rounded">
        </div>
        <div class="card shadow small mt-5">
            <!-- <div class="table-responsive"> -->
                <table class="table m-3">
                    <tbody>
                        <td>Nama</td>
                        <td>:</td>
                        <td>Kurniawan, S.Pd, M.Pd.</td>
                    </tbody>
                    <tbody>
                        <td>NIP</td>
                        <td>:</td>
                        <td>19720809 199702 1 002</td>
                    </tbody>
                    <tbody>
                        <td>Pangkat/Golongan</td>
                        <td>:</td>
                        <td>Pembina IV/b</td>
                    </tbody>
                    <tbody>
                        <td>No SK Pengangkatan</td>
                        <td>:</td>
                        <td>821.2/Kep.373-BKD/2020</td>
                    </tbody>
                    <tbody>
                        <td>Tanggal</td>
                        <td>:</td>
                        <td>10 Juli 2020</td>
                    </tbody>
                </table>
            <!-- </div> -->
        </div>
    </div>
</template>

Nama	:	
NIP	:	
Pangkat/Golongan	:	
No SK Pengangkatan	:	
Tanggal	:	

<style scoped>
h4, .table {
    font-family: "Poppins", serif;
}

h4 {
    margin-left: 95px;
}

img {
    width: 200px;
}

.small {
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

@media only screen and (max-width: 600px) {
    td {
        font-size: small;
        padding-left: 0;

    }

    h4 {
        margin-left: 35px;
    }

    img {
        width: 150px;
    }
}

</style>