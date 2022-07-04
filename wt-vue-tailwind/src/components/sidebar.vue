<script >
import { ref } from "vue";
export default {
  setup() {
    const showSidebar = ref(false);

    return {
      showSidebar,
    };
  },
};

</script>

<template>

 <div class="relative flex min-h-screen">

    <!-- Aufgabe 1 -->
    
      <div class="bg-cyan-600 text-cyan-100 w-64 space-y-6 px-2 py-4 absolute inset-y-0 left-0 md:relative md:-translate-x-0 transform -translate-x-full transition duration-200 ease-in-out"
      :class="{ 'relative -translate-x-0': showSidebar }" >
      
      <a href="" class="flex items-center space-x-2 px-4">
        <i class="bi bi-house"></i>
        <span class="text-2xl font-extrabold text-white">Home</span>
      </a>

      <nav>
        <a href="/" class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 ">
          <i class="bi bi-bookmark-dash"></i>
          <span class="text-white group-hover:text-cyan-300">Dashbord</span>
        </a>

        <a href="/" class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300">
          <i class="bi bi-people "></i>
          <span class="text-white group-hover:text-cyan-300">Team</span>
        </a>
        
        <a href="/" class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300">
         <i class="bi bi-file-earmark-code"></i>
          <span class="text-white group-hover:text-cyan-300">Project</span>
        </a>

        <a href="/" class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-300">
         <i class="bi bi-calendar"></i>
         <span class="text-white group-hover:text-cyan-300">Calender</span>
        </a>

      </nav>
      </div>
         
    
      <div class="flex-1 bg-green-300">

        <div class="bg-white shadow px-2">
        <button
          @click="showSidebar = !showSidebar"
          class="font-extrabold text-cyan-600"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-8 w-8"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            stroke-width="2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M4 6h16M4 12h8m-8 6h16"
            />
          </svg>
        </button>
      </div>

        <div class="pt-8"> Content </div> 
      </div>
  </div>
 
    
</template>

<style>

</style>