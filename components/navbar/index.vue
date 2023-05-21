<template>
  <div class="h-full min-h-full	 mr-2 flex flex-col space-y-4 navbar absolute top-0 bg-nord1 w-24 " >
    <NuxtLink class=" mt-4" to="/" id="home"
      ><icon
        class="bg-nord2  rounded-md text-nord9 w-4/5"
        name="fa6-solid:house"
        size="5em"
    /></NuxtLink>
    <a href="https://discord.com/users/688804133674811473" id="discord">
      <icon
        class="bg-nord2  rounded-md text-nord9 w-4/5"
        name="fa6-brands:discord"
        size="5em"
      />
    </a>
    <a href="https://t.me/krokiets" id="telegram">
      <icon class="bg-nord2  rounded-md text-nord9 w-4/5" name="fa6-brands:telegram" size="5em" />
    </a>
    <NuxtLink class="mt-10" to="/stuff" id="stuff">
      <icon class="bg-nord2  rounded-md text-nord9 w-4/5" name="fa-solid:box-open" size="5em" />
    </NuxtLink>
  </div>

</template>
<style src="./navbar.css"></style>
