<template>
  <div class="bg-green-550 h-screen">
    <div class="font-arial text-white text-8xl text-center font-bold pt-6">
      Oups ...
    </div>
    <div class="font-arial text-white text-6xl mx-2 text-center pt-6">
      La page que vous cherchez semble introuvable.
    </div>

    <div class="font-arial text-white text-xl mx-2 text-center pt-6">
      Code d’erreur : 404
    </div>

    <div class="flex justify-center">
      <RouterLink to="/profil">
        <button
          class="
            bg-white
            text-green-450 text-lg
            font-bold
            mt-10
            py-2
            px-20
            rounded-xl
          "
        >
          Retour à mon Profil
        </button>
      </RouterLink>
    </div>
    <div class="flex justify-center">
      <img
        class="w-screen lg:w-8/12 max-h-96 absolute bottom-0"
        src="/images/404Illustration.png"
        alt="illustration page 404"
      />
    </div>
  </div>
</template>

 
<script>
import GrandeCarteTerrainNotif from "../components/GrandeCarteTerrainNotif.vue";
export default {
  name: "Page404View ",
  components: { GrandeCarteTerrainNotif },
};
</script>
