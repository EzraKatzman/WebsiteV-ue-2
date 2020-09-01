<template>
  <div class="flex flex-col min-h-screen bg-gray-200 bg-shattered bg-fixed">
    <Hero class="hidden lg:block"/>
    <Navbar class="sticky top-0"/>
    <div class="flex-grow">
      <div class="xl:grid xl:grid-cols-5">
        <Bio class="xl:m-2"/>
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
import Hero from './components/Hero'
import Navbar from './components/Navbar'
import Projectdrop from './components/Projectdrop'
import Experiencedrop from './components/Experiencedrop'
import Bottombanner from './components/Bottombanner'
import Bio from './components/Bio'
import WorkWindow from './components/WorkWindow'
import ProjectWindow from './components/ProjectWindow'

export default {
  name: 'App',
  components: {
    Hero,
    Navbar,
    Projectdrop,
    Experiencedrop,
    Bottombanner,
    Bio,
    WorkWindow,
    ProjectWindow
  }
}
</script>

<style>
  @import "C:/Users/Ezkat/Desktop/Side Projects/WebsiteRedux/website/src/assets/css/tailwind.css";
</style>
