<template>
  <div class="flex flex-col min-h-screen bg-gray-100 md:bg-gradient-to-r from-teal-200 to-gray-300">
    <Navbar class="sticky top-0"/>

    <div class="hidden lg:block h-screen w-full text-center ">
      <!-- Element to trick the browser in to centering the HeroContent -->
      <span class="hidden sm:inline-block sm:align-middle sm:h-full"></span>&#8203;
      <HeroContent class="inline-block sm:w-half"/>
    </div>
    
    <div class="flex-grow">
      <div class="xl:grid xl:grid-cols-4">
        <Bio class="lg:hidden"/>
        <WorkWindow class="hidden md:block col-span-2 xl:m-2"/>
        <ProjectWindow class="hidden md:block col-span-2 xl:m-2"/>
      </div>
    </div>
    <Experiencedrop class="md:hidden"/>
    <Projectdrop class="md:hidden"/>
    <Bottombanner/>
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Projectdrop from './components/Projectdrop'
import Experiencedrop from './components/Experiencedrop'
import Bottombanner from './components/Bottombanner'
import Bio from './components/Bio'
import WorkWindow from './components/WorkWindow'
import ProjectWindow from './components/ProjectWindow'
import HeroContent from './components/HeroContent'

export default {
  name: 'App',
  components: {
    Navbar,
    Projectdrop,
    Experiencedrop,
    Bottombanner,
    Bio,
    WorkWindow,
    ProjectWindow,
    HeroContent
  }
}
</script>

<style>
  @import "C:/Users/Ezkat/Desktop/Projects/WebsiteRedux/website/src/assets/css/tailwind.css";
</style>
