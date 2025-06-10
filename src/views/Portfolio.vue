<script setup>
    import usuario from '../assets/variaveis'
</script>

<template>

    <!-- Home -->
    <section id="home" class="min-h-screen flex flex-col justify-center items-center">
        <h1 class="text-4xl font-bold mb-5 px-4">Bem vindo ao meu Portfólio</h1>
        <p class="text-xl max-w-5xl text-justify px-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse quaerat reprehenderit, vero iusto itaque odit nisi iste possimus quia omnis odio, rerum quisquam saepe, delectus nesciunt? Ut amet voluptatibus ad!</p>
    </section>

    <!-- Sobre -->
    <section id="sobre" class="min-h-screen flex flex-col justify-center items-center bg-base-200">
        <h2 class="text-3xl font-bold px-4 mb-5">Sobre</h2>
        <p class="text-xl justify-center px-4 max-w-5xl text-justify">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Illo consequuntur omnis magnam reiciendis tempore placeat. Ipsa unde dolor veniam autem culpa dignissimos asperiores, nobis odio perferendis ullam quaerat, molestiae iure.</p>
    </section>

    <!-- Projetos -->
    <section id="projetos" class="min-h-screen flex flex-col justify-center items-center">
        <h2 class="text-3xl font-bold px-4 mb-5">Projetos</h2>
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