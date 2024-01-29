<template>
  <header class="container mx-auto py-5 flex justify-between items-center">
    <div class="text-2xl font-serif font-semibold tracking-wider text-pink-300">
      <ElIconFullScreen class="mr-2 inline w-8"></ElIconFullScreen>
      <p class="inline">Asgindo Herbal</p>
    </div>
    <div class="flex">
      <ElButton link>HOME</ElButton>
      <ElButton link>ABOUT</ElButton>
      <ElButton link>FAQ</ElButton>
      <ElButton link>CONTACT</ElButton>
    </div>
  </header>
  <section>
      <NuxtPage />
  </section>
</template>