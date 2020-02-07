<template>
  <div class="container mx-auto p-20">
        <avatar inline username="vue avatar fr"
        background-color="#A0AEC0"
         :size="100"
        >
          
        </avatar>
    <h2 class="text-6xl font-black text-center">Exemple vue-avatar</h2>

    <h2 class="text-xl font-medium text-center">Exemple par defaut</h2>
    <div class="flex mb-4">
      <div class="w-1/4 bg-gray-500 mx-2 p-2 rounded flex flex-row ">
        <div class=""><avatar username="Mve Michel"></avatar></div>
        <div class=" ml-5 font-bold text-gray-700 text-lg items-center flex ">Mve Michel</div>
      </div>
      <div class="w-1/4 bg-gray-400 mx-2 p-2 rounded flex flex-row ">
        <div class=""><avatar username="Ondo Bibang Paulin"></avatar></div>
        <div class=" ml-5 font-bold text-gray-700 text-lg items-center flex ">Ondo Bibang Paulin</div>
      </div>
      <div class="w-1/4 bg-gray-500 mx-2 p-2 rounded flex flex-row ">
        <div class=""><avatar username="Jean Daniel"></avatar></div>
        <div class=" ml-5 font-bold text-gray-700 text-lg items-center flex ">Jean Daniel</div>
      </div>
      <div class="w-1/4 bg-gray-400 mx-2 p-2 rounded flex flex-row ">
        <div class=""><avatar username="amadou "></avatar></div>
        <div class=" ml-5 font-bold text-gray-700 text-lg items-center flex ">amadou </div>
      </div>
    </div>


    <h2 class="text-xl font-medium text-center mt-10">Exemple avec propriétés</h2>
    <div class="flex mb-4 ">
      <div class="w-1/4 bg-gray-500 mx-2 p-2 rounded flex flex-row ">
        <div class=""><avatar inline
            username="Amaury-Tobias Quiroz"
            background-color="#FFC107"
            :size="100"
            rounded
            :lighten="20"></avatar></div>
        <div class=" ml-5 font-bold text-gray-700 text-lg items-center flex ">Mve Michel</div>
      </div>
      <div class="w-1/4 bg-gray-400 mx-2 p-2 rounded flex flex-row ">
        <div class=""><avatar username="Ondo Bibang Paulin"></avatar></div>
        <div class=" ml-5 font-bold text-gray-700 text-lg items-center flex ">Ondo Bibang Paulin</div>
      </div>
      <div class="w-1/4 bg-gray-500 mx-2 p-2 rounded flex flex-row ">
        <div class=""><avatar username="Jean Daniel"></avatar></div>
        <div class=" ml-5 font-bold text-gray-700 text-lg items-center flex ">Jean Daniel</div>
      </div>
      <div class="w-1/4 bg-gray-400 mx-2 p-2 rounded flex flex-row ">
        <div class=""><avatar username="amadou "></avatar></div>
        <div class=" ml-5 font-bold text-gray-700 text-lg items-center flex ">amadou </div>
      </div>
    </div>

  </div>
</template>

<script>
//impoter vue-avatar
import Avatar from 'vue-avatar'
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    Avatar
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
