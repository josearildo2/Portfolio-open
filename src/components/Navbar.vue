<script setup>
    import usuario from '../assets/variaveis'
</script>

<template>

    <div class="navbar fixed top-0 left-0 z-50 bg-base-200 px-4">
        <div class="navbar-start">
            <!-- Navbar MOBILE -->
            <div class="dropdown mr-3">
                <div tabindex="0" role="button" class="lg:hidden btn btn-ghost -ml-2">
                    <font-awesome-icon size="lg" :icon="['fas', 'bars']"/>
                </div>
                <ul class="dropdown-content menu bg-base-100 rounded-box w-25 shadow">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#sobre">Sobre</a></li>
                    <li><a href="#experiencia">Experiência</a></li>
                </ul>
            </div>
            <div class="avatar">
                <div class="w-13 rounded-full">
                    <img src="../../public/images/default.png" alt="avatar">
                </div>
            </div>
            <a class="btn btn-ghost text-[16px] px-6">{{ usuario.nome }}</a>
        </div>

        <div class="navbar-end hidden lg:flex">
            <!-- Navbar DESKTOP -->
            <ul class="menu menu-horizontal">
                <li><a href="#home">Home</a></li>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#experiencia">Experiência</a></li>
            </ul>
        </div>
    </div>

</template>