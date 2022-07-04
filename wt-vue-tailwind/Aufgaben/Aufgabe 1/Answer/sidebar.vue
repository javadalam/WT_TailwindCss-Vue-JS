
<script>
import anmelden from "./anmelden.vue";
export default {
    components:{
        anmelden,
    }
}
</script>

<template>
    <div class="relative flex min-h-screen">
    <div
      class="bg-cyan-600 text-white w-64 space-y-6 ">
      <a href="" class=" "> <span class="">Home</span> </a>

      <nav>
        <a href="/" class=" flex  "> <span class="">Dashbord</span> </a>

        <a href="/" class=" flex"> <span class="">Team</span> </a>
        
        <a href="/" class=" flex "> <span class="">Project</span> </a>

        <a href="/" class="flex"> <span class="">Calender</span> </a>

      </nav>
      
    </div>
    <anmelden />
  </div>
</template>

