<script setup>
const features = [
  {
    title: "Hosting & SEO",
    description:
      "Alojamiento web confiable y certificado SSL para tu proyecto online. Traé tu web y mejora tu posicionamiento en buscadores web.",
    icon: "ic:baseline-cloud",
  },

  {
    title: "Web a Medida",
    description:
      "Creamos landing pages impactantes y aplicaciones web potentes para optimizar tus procesos.",
    icon: "gg:website",
  },

  {
    title: "Venta & Gastronomía",
    description:
      "Plataformas e-commerce y herramientas digitales para la gestion de restaurantes. Crea tus productos y vendelos con nosotros.",
    icon: "famicons:cart",
  },

  {
    title: "Turnos Médicos",
    description:
      "Te ayudamos a crear tu sistema online para la gestión eficiente de turnos en clínicas y consultorios.",
    icon: "jam:medical",
  },

  {
    title: "Gestión Integral",
    description:
      "Soluciones empresariales para la gestión HSE y RRHH, recibos digitales y gestión de flota en tu empresa.",
    icon: "ci:settings",
  },

  {
    title: "Features a Medida",
    description:
      "Integramos plataformas de pago y añadimos las características que faltan a tu software para una funcionalidad completa.",
    icon: "proicons:box-add",
  },

];
</script>

<template>
  <div class="mt-16 md:mt-0" style="font-family: 'Rubik', sans-serif;">
    <h2 class="text-4xl lg:text-5xl font-regular lg:tracking-tight">
      Todo lo que necesitas para empezar tu proyecto
    </h2>
    <p class="text-lg mt-4 text-slate-700 font-thin">
      Soluciones de software innovadoras y a tu medida: esto es lo que podemos hacer por vos.
    </p>
  </div>

  <div id="feat" class="grid sm:grid-cols-2 md:grid-cols-3 mt-10 gap-10" style="font-family: 'Rubik', sans-serif;">
    <div v-for="item of features" class="flex gap-4 items-start rounded-md hover:bg-slate-200 p-3">
      <div class="mt-1 bg-black rounded-full flex justify-center items-center w-10 h-10 shrink-0">
        <Icon class="text-white" :name="item.icon" size="24"/>
      </div>
      <div>
        <h3 class="font-normal text-lg">{{ item.title }}</h3>
        <p class="text-slate-500 mt-2 leading-relaxed font-light">
          {{ item.description }}
        </p>
      </div>
    </div>
  </div>
</template>
