<template>
  <div>
    <div class="h-20"></div>
  <div class="px-6 flex flex-col justify-center items-center"> 
    <h1 class="mb-0">Mulțumim pentru programare!</h1>
    <h2 class="mt-12 font-mwr">Un membru al echipei noastre te va contacta în cel mai scurt timp.</h2>
    <p class="mb-32">
      Click 
      <router-link :to="{name: 'Home'}" class="text-primary underline">aici</router-link>
      pentru a te reîntoarce la pagina principală.</p>
  </div>
  </div>
</template>

<script>
export default {
  components: {}
}
</script>