<template>
  <div>
    <header>
      <HeadNav />
    </header>
    <main>
      <About />
      <Knowledge />
      <Projects />
      <Contact />
    </main>
    <footer>
      <FooNav />
    </footer>
  </div>
</template>

<script>
import HeadNav from '../components/shared/HeadNav.vue'
import About from '../components/homePage/About.vue'
import Knowledge from '../components/homePage/Knowledge.vue'
import Projects from '../components/homePage/Projects.vue'
import Contact from '../components/homePage/Contact.vue'
import FooNav from '../components/shared/FooNav.vue'

export default {
  components: {
    HeadNav, About, Knowledge, Projects, Contact, FooNav,
  }
}
</script>

<style lang="scss" scoped>
h1, h2 {
  color: #a75efa;
}

</style>