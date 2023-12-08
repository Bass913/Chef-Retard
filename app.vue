<script setup lang="ts">
useHead({
  title: "Chef Retard : Cuisinez avec Saveur, Même en Mode Express !",

  meta: [
    {
      name: "description",
      content:
        "Découvrez l'univers délicieux de Chef Retard, où la cuisine rapide et savoureuse devient un art. Trouvez des recettes faciles pour les chefs pressés, des astuces de préparation et des idées créatives pour des repas délicieux en un temps record. Relevez le défi culinaire du quotidien avec nos solutions gourmandes, spécialement conçues pour ceux qui ont peu de temps mais beaucoup de goût !",
    },
  ],
  bodyAttrs: {
    class: "test",
  },
  script: [{ innerHTML: "console.log('Hello world')" }],
});
</script>
<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
