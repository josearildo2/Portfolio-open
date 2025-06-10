<script setup>
    import usuario from '../assets/variaveis'
</script>

<template>
    <footer class="text-center bg-base-200 space-y-2 py-2">
        <div class="flex justify-center gap-3 text-xl">
            <a
                :href="usuario.github" target="_blank"
                class="hover:text-primary transition"
            >
                <font-awesome-icon :icon="['fab', 'github']" />
            </a>
            <a 
                :href="usuario.linkedin" target="_blank"
                class="hover:text-primary transition"
            >
                <font-awesome-icon :icon="['fab', 'linkedin']" />
            </a>
        </div>
        <div>
            © {{ usuario.ano }} - {{ usuario.projeto }} por {{ usuario.nome }}
        </div>
    </footer>
</template>