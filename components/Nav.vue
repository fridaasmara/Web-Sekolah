<template>
    <nav class="navbar navbar-expand-lg bg-light shadow p-3">
        <div class="container-fluid">
            <nuxt-link to="/" class="d-flex tohome">
                <img src="../assets/img/LOGO-SMK4.png" alt="logo" class="logo">
                <h4 class="navbar-brand mt-2">SMKN 4 Tasikmalya</h4>
            </nuxt-link>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <nuxt-link to="/" class="nav-link active" aria-current="page">Beranda</nuxt-link>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Profil
                        </a>
                        <ul class="dropdown-menu">
                            <li><nuxt-link to="/profile/identitasSekolah" class="dropdown-item">Identitas Sekolah</nuxt-link></li>
                            <li><nuxt-link to="/profile/sejarah" class="dropdown-item">Sejarah</nuxt-link></li>
                            <li><nuxt-link to="/profile/visiMisi" class="dropdown-item">Visi & Misi</nuxt-link></li>
                            <li><nuxt-link to="/profile/kepalaSekolah" class="dropdown-item">Kepala Sekolah</nuxt-link></li>
                            <li><nuxt-link to="/profile/guruStaf" class="dropdown-item">Guru & Staf</nuxt-link></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Kurikulum
                        </a>
                        <ul class="dropdown-menu">
                            <li><nuxt-link to="/kurikulum/konsentrasiKeahlian" class="dropdown-item">Konsentrasi Keahlian</nuxt-link></li>
                            <li><nuxt-link to="/kurikulum/prestasi" class="dropdown-item">Prestasi</nuxt-link></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Kesiswaan
                        </a>
                        <ul class="dropdown-menu">
                            <li><nuxt-link to="/kesiswaan/organisasi" class="dropdown-item">Organisasi</nuxt-link></li>
                            <li><nuxt-link to="/kesiswaan/ekskul" class="dropdown-item">Ekstrakurikuler</nuxt-link></li>
                        </ul>
                    </li> 
                    <li class="nav-item">
                        <nuxt-link to="/galeri" class="nav-link" aria-current="page">Galeri</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="/berita" class="nav-link" aria-current="page">Berita</nuxt-link>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

.logo {
    width: 3rem;
}

h4 {
    margin-left: 10px;
    font-family: "Poppins", serif;
}

.nav-item {
    font-family: "Poppins", serif;
    margin-right: 10px;
    font-size: 15px;

}

.nav-link {
    color: #000;
}

.dropdown-item {
    font-size: 15px;
}

.tohome {
    text-decoration: none !important;
}

@media only screen and (max-width: 600px) {
    h4 {
        margin-left: 0;
    }
}

</style>