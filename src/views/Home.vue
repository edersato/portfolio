<template>
  <div>
    <header>
      <HeadNav />
    </header>
    <main>
      <Presentation />
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
import Presentation from '../components/homePage/Presentation.vue'
import About from '../components/homePage/About.vue'
import Knowledge from '../components/homePage/Knowledge.vue'
import Projects from '../components/homePage/Projects.vue'
import Contact from '../components/homePage/Contact.vue'
import FooNav from '../components/shared/FooNav.vue'

export default {
  components: {
    HeadNav, Presentation, About, Knowledge, Projects, Contact, FooNav,
  }
}
</script>

<style lang="scss">

@mixin heading {
  h1, h2, h3, h4, h5, h6 {
    color: #5ebcfa;
  }
}

@include heading()
</style>