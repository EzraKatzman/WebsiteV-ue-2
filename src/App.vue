<template>
  <div class="flex flex-col min-h-screen bg-shattered bg-fixed">
    <Navbar/>
    <div class="flex-grow">
      <div class="lg:grid lg:grid-cols-5">
        <Bio/>
        <WorkWindow class="hidden lg:block col-span-2"/>
        <ProjectWindow class="hidden lg:block col-span-2"/>
      </div>
    </div>
    <Experiencedrop class="lg:hidden"/>
    <Projectdrop class="lg:hidden"/>
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

export default {
  name: 'App',
  components: {
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
