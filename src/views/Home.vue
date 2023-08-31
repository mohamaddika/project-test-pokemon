<template>
  <div class="container mx-auto p-10 mt-14">
    <div class="grid grid-cols-4 gap-6 ">
      <div v-for="item in listPokemon" :key="item.id" class="w-56 h-72 bg-white border border-gray-200 rounded-l-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <div class="p-7">
          <span class="text-gray-600 font-semibold">#{{ item.id }}</span>
          <img src="https://id.portal-pokemon.com/play/resources/pokedex/img/pm/cf47f9fac4ed3037ff2a8ea83204e32aff8fb5f3.png">
          <div class="text-center">
          <span class=" text-red-600 font-semibold text-2x1">{{ item.name }}</span>
          <div class="pt-2 ">
            <span class="bg-lime-500 text-white text-base font-medium mr-3 px-3 py-1.5 rounded text-center">Grass</span>
            <span class="bg-purple-700 text-white text-base font-medium mr-3 px-3 py-1.5 rounded text-center">Poison</span>
          </div>
          </div>
        </div>
      </div>
    </div>
    </div>
</template>
<script>
export default {
  computed: {
    listPokemon(){
      return this.$store.state.pokemon.dataPokemon;
    }
  }
}
</script>