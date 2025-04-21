<script lang="ts" setup>


</script>

<template>
  <main class="grid lg:grid-cols-2 place-items-center pt-16 pb-8 md:pt-4" style="font-family: 'Rubik', sans-serif;">
    <div class="p-16 lg:order-1 hidden lg:block rounded-md">
      <img
        class="rounded-full translate-x-20 transition-transform transform hover:scale-110"
        src="~/assets/img/rocket2.avif"
        alt="HVDevs Logo"
        loading="eager"
        format="webp"
        width="720"
        height="720"
      />
    </div>

    <div>
      <h1 class="text-5xl lg:text-6xl xl:text-7xl lg:tracking-tight">
        Te ayudamos a darle vida a tus proyectos
      </h1>
      <p class="text-lg mt-4 text-slate-800 font-light max-w-xl">
        Desde la Patagonia Argentina, <span class="font-semibold">High Valley Developers</span> emerge como un socio estratégico para empresas que buscan soluciones de software de alto impacto. Nos especializamos en el desarrollo de aplicaciones web y móviles, utilizando tecnologías de punta y metodologías ágiles para garantizar resultados excepcionales.
      </p>
      <div class="mt-6 flex flex-col sm:flex-row gap-3">
        <LandingLink
          href=""
          target="_blank"
          rel="noopener"
          >Saber mas</LandingLink
        >
        <LandingLink
          size="lg"
          styleName="outline"
          rel="noopener"
          href=""
          target="_blank"
          >Nuestros Productos</LandingLink
        >
      </div>
    </div>
  </main>
</template>
