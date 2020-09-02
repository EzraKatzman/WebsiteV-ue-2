<template>
  <div class="flex flex-col min-h-screen bg-teal-300">
    <Navbar class="sticky top-0"/>
    
    <div class="hidden lg:block h-screen w-full text-center ">
      <HeroContent class="inline-block transform translate-y-full w-half"/>
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
  @import "C:/Users/Ezkat/Desktop/Side Projects/WebsiteRedux/website/src/assets/css/tailwind.css";
</style>
