
<script>
import anmelden from "./anmelden.vue"
import IconCalender from "./icons/IconCalender.vue"
import IconDashboard from "./icons/IconDashboard.vue"
import IconHome from "./icons/IconHome.vue"
import IconProject from "./icons/IconProject.vue"
import IconTeam from "./icons/IconTeam.vue"
import IconProject1 from "./icons/IconProject.vue"
export default {
    components:{
        anmelden,
        IconCalender,
        IconDashboard,
        IconHome,
        IconTeam,
        IconProject,
        IconProject1,
    }
}
</script>

<template>
   <div class="relative flex min-h-screen">
    <div
      class="bg-cyan-600 text-cyan-100 w-64 space-y-6 px-2 py-4"
      
    >
      <a href="" class="flex items-center space-x-2 px-4">
     <IconHome />
        <span class="text-2xl font-extrabold text-white">Home</span>
      </a>

      <nav>
        <a href="/" class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 ">
          <IconDashboard />
          <span class="text-white group-hover:text-cyan-300">Dashbord</span>
        </a>

        <a href="/" class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300">
          <IconTeam />
          <span class="text-white group-hover:text-cyan-300">Team</span>
        </a>
        
        <a href="/" class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300">
         <IconProject />
          <span class="text-white group-hover:text-cyan-300">Project</span>
        </a>

        <a href="/" class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-300">
         <IconCalender />
         <span class="text-white group-hover:text-cyan-300">Calender</span>
        </a>

      </nav>
    </div>
    <anmelden />
  </div>
    
  
</template>


