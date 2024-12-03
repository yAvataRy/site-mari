<template>
  <nav class="font-Playfair">
    <ul class="flex flex-col md:flex-row md:space-x-4">
      <li>
        <NuxtLink to="/" class="link">Principal</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/about" class="link">Meus serviços</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/projects" class="link">O que os clientes falam</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/contato" class="link">Contato</NuxtLink>
      </li>
    </ul>
  </nav>
</template>

<style scoped>
.link {
  @apply p-1 hover:bg-gray-200 dark:hover:bg-gray-800 text-2xl md:text-base
}
</style>