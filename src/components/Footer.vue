<script setup>
    import { ref } from 'vue'
    import usuario from '../assets/variaveis'

    const socials = ref(usuario.redes_sociais)
</script>

<template>
    <footer class="text-center bg-base-200 space-y-2 py-2">
        <div class="flex justify-center gap-3 text-xl">
            <a
                v-for="social in socials" :key="social"
                :href="social.endereco" target="_blank"
                class="hover:text-primary transition"
            >
                <font-awesome-icon :icon="['fab', social.name]" />
            </a>
        </div>
        <div>
            © {{ usuario.ano }} - {{ usuario.projeto }} por {{ usuario.nome }}
        </div>
    </footer>
</template>