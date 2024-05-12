<script setup>
import TeamMember from './components/TeamMember.vue';

const person1 = {
  name: "Lana Byrd",
  designation: "CEO",
  des: "Bonnie drives the technical strategy of the flowbite platform and brand.",
  avater: "https://flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/bonnie-green.png",
};
</script>

<template>
  <main class="bg-gray-50 dark:bg-gray-900 w-full">
    <section class="mx-auto container">
      <section class="bg-white dark:bg-gray-900">
        <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16 lg:px-6">
          <div class="mx-auto max-w-screen-sm text-center mb-8 lg:mb-16">
            <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">
              Our Team
            </h2>
            <p class="font-light text-gray-500 lg:mb-16 sm:text-xl dark:text-gray-400">
              Explore the whole collection of open-source web components and elements built with the
              utility classes from Tailwind
            </p>
          </div>
          <div class="grid gap-8 mb-6 lg:mb-16 md:grid-cols-2">


            <TeamMember
              name="Lana Byrd"
              designation="CEO"
              des=" Bonnie drives the technical strategy of the flowbite platform and brand."
              avater="//flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/bonnie-green.png"
            />
            
            <TeamMember
              name="Jese Leos"
              designation="CTO"
              des="Jese drives the technical strategy of the flowbite platform and brand."
              avater="//flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/jese-leos.png"
            />

            <TeamMember
              name="Jese Leos"
              designation="CTO"
              des="Jese drives the technical strategy of the flowbite platform and brand."
              avater="//flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/joseph-mcfall.png"
            />

            <TeamMember  v-bind="person1" />


          </div>
        </div>
      </section>
    </section>
  </main>
</template>

<style scoped>




</style>
