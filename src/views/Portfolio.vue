<script setup>
    import { ref } from "vue"
    import usuario from "../assets/variaveis"

    const skills = ref(usuario.hard_skills)
</script>

<template>

    <!-- Home -->
    <section id="home" class="min-h-screen flex flex-col justify-center items-center mb-5">
        <h1 class="text-4xl font-bold mb-5 px-4">Bem vindo ao meu Portfólio</h1>
        <p class="text-xl max-w-5xl text-justify px-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse quaerat reprehenderit, vero iusto itaque odit nisi iste possimus quia omnis odio, rerum quisquam saepe, delectus nesciunt? Ut amet voluptatibus ad!</p>
    </section>

    <!-- Sobre -->
    <section id="sobre" class="min-h-screen flex flex-col justify-center items-center bg-base-200 mb-2">
        <h2 class="text-3xl font-bold px-4 mb-5">Sobre</h2>
        
        <div class="flex flex-col lg:flex-row  w-full max-w-7xl gap-6">
            <div class="lg:w-1/2 text-xl text-justify space-y-4 px-4">
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores aliquam quo earum esse dolor nobis
                     ipsa recusandae assumenda temporibus rerum cumque, perspiciatis beatae accusantium ea debitis unde eum ducimus aperiam.
                </p>
            </div>

            <div class="hidden lg:flex">
                <div class="divider lg:divider-horizontal"></div>
            </div>

            <div class="flex flex-col lg:hidden p-6">
                <div class="divider divider-vertical"></div>
            </div>

            <div class="lg:w-1/2 flex flex-wrap gap-2 justify-center px-4 items-center mb-5">
                <button type="button" class="btn btn-disabled" v-for="skill in skills" :key="skill">
                    {{ skill }}
                </button>
            </div>
        </div>
    </section>

    <!-- Experiência Profissional -->
    <section id="experiencia" class="min-h-screen flex flex-col justify-center items-center mb-5">
        <h2 class="text-3xl font-bold px-4 mb-5">Experiência Profissional</h2>
        <ul class="timeline timeline-snap-icon max-md:timeline-compact timeline-vertical max-w-7xl px-4 mb-3">
            <li>
                <div class="timeline-middle">
                    <font-awesome-icon :icon="['fas', 'circle-check']" />
                </div>
                <div class="timeline-start mb-10 md:text-end">
                    <time class="font-mono italic">2025</time>
                    <div class="text-lg font-black">First Macintosh computer</div>
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Soluta ab rerum id accusamus sint! Voluptatem, rem natus tempore aspernatur dignissimos optio cumque necessitatibus fugit fuga expedita, doloremque quidem amet voluptatibus.
                </div>
                <hr />
            </li>
            <li>
                <hr />
                <div class="timeline-middle">
                    <font-awesome-icon :icon="['fas', 'circle-check']" />
                </div>
                <div class="timeline-end md:mb-10">
                    <time class="font-mono italic">2020</time>
                    <div class="text-lg font-black">iMac</div>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore dolorum maxime excepturi voluptatibus tempora quo odit fugiat, laborum, praesentium quia 
                    aut reiciendis ipsum sequi dolor dolorem est! Dolores, incidunt modi.
                </div>
                <hr />
            </li>
            <li>
                <hr />
                <div class="timeline-middle">
                    <font-awesome-icon :icon="['fas', 'circle-check']" />
                </div>
                <div class="timeline-start mb-10 md:text-end">
                    <time class="font-mono italic">2015</time>
                    <div class="text-lg font-black">iPod</div>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. At quibusdam eos voluptatum quisquam nesciunt temporibus accusamus iste rerum laborum dolor adipisci esse, 
                    dolorem eius, ullam veritatis harum impedit eum? Repellendus? 
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum eum natus voluptatum ad quia labore eius dignissimos! Beatae assumenda inventore blanditiis ipsum 
                    reprehenderit, quasi, repudiandae porro officiis explicabo, distinctio voluptatibus.
                </div>
                <hr />
            </li>
            <li>
                <hr />
                <div class="timeline-middle">
                    <font-awesome-icon :icon="['fas', 'circle-check']" />
                </div>
                <div class="timeline-end md:mb-10">
                    <time class="font-mono italic">2010</time>
                    <div class="text-lg font-black">iPhone</div>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vel doloremque, officia dicta mollitia obcaecati consequuntur? Tempora distinctio 
                    voluptatibus sapiente eligendi ab reiciendis rerum minima debitis, in nostrum, sunt quam.
                </div>
                <hr />
            </li>
            <li>
                <hr />
                <div class="timeline-middle">
                    <font-awesome-icon :icon="['fas', 'circle-check']" />
                </div>
                <div class="timeline-start mb-10 md:text-end">
                    <time class="font-mono italic">2005</time>
                    <div class="text-lg font-black">Apple Watch</div>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti dicta eveniet numquam a distinctio perferendis. Excepturi, 
                    sapiente amet voluptate laboriosam veritatis illum praesentium assumenda dignissimos nesciunt sequi. A, natus praesentium.
                </div>
            </li>
        </ul>
    </section>

</template>