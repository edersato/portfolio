<template>
  <div>
    <b-navbar toggleable="md" type="dark" variant="transparent">
      <b-navbar-brand href="#">Eder da Rosa Sato</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#about">Sobre</b-nav-item>
          <b-nav-item href="#knowledge" >Conhecimentos</b-nav-item>
          <b-nav-item href="#projects" >Projetos</b-nav-item>
          <b-nav-item href="#contact" >Contato</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>

#nav-collapse {
    justify-content: right;
    font-size: 1.2rem;
}

nav {
  padding: 5px 30px;

  a {
    font-weight: 400;
    text-decoration: none;
    transition: .3s ease-in;

    &:hover {
      transition: .2s;
      font-weight: bolder;
      letter-spacing: .5px;

      &::before {
        content: "►";
      }
    }
  }
}

</style>