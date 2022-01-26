<template>

      <Hero />

      <About />
     

     <Services />

     <Blog />

     <Contact />
 
</template>

<script>
// @ is an alias to /src
import Hero from '@/components/Home/Hero.vue'
import About from '@/components/Home/About.vue'
import Services from '@/components/Home/Services.vue'
import Blog from '@/components/Home/Blog.vue'
import Contact from '@/components/Home/Contact.vue'

export default {
  name: 'Home',
  components: {
    About, Hero, Services, Blog, Contact
  }
}
</script>

<style scoped>
.hero{
  background-image:url(img/hero.jpg);
}
</style>