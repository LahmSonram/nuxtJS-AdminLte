<template>
  <div>
    <NavBar />
    <SideBar />
    <nuxt class="content-wrapper" />
    <Footer />
  </div>
</template>
<script>
import NavBar from '../components/page/NavBar'
import SideBar from '../components/page/SideBar'
import Footer from '../components/page/Footer'
export default {
  components: {
    NavBar, SideBar, Footer
  }
}
</script>
