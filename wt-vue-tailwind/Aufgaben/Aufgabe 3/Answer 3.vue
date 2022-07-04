
<!-- Aufgabe 3 -->

<script>
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

    
    
       <div class="bg-cyan-600 text-cyan-100 w-64 space-y-6 px-2 py-4 absolute inset-y-0 left-0 md:relative md:-translate-x-0 transform -translate-x-full transition duration-200 ease-in-out"
      :class="{ 'relative -translate-x-0': showSidebar }">
         
         
      </div>
         
    
      <div class="flex-1">
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