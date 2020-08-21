<template>
  <div class="flex flex-col min-h-screen bg-shattered bg-fixed">
    <Navbar/>
    <div class="flex-grow">
      <Bio/>
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

export default {
  name: 'App',
  components: {
    Navbar,
    Projectdrop,
    Experiencedrop,
    Bottombanner,
    Bio
  }
}
</script>

<style>
  @import "C:/Users/Ezkat/Desktop/Side Projects/WebsiteRedux/website/src/assets/css/tailwind.css";
</style>
