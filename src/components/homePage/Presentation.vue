<template>
  <section>
      <img src="../../assets/photo01.jpg" alt="">

      <div>
        <h5>Olá, eu sou</h5>
        <h1>Eder Sato</h1>
        <h3>Desenvolvedor Front End</h3>

        <div class="icons">
          <a href="https://www.linkedin.com/in/eder-da-rosa-sato/">
            <b-icon icon="linkedin" opacity="0.8" font-scale="2" variant="primary"></b-icon>
          </a>
          <a href="https://github.com/edersato/">
            <b-icon icon="github" opacity="0.8" font-scale="2" variant="white"></b-icon>
          </a>
          <a href="mailto:edersato@gmail.com">
            <b-icon icon="envelope" opacity="0.8" font-scale="2" variant="white"></b-icon>
          </a>
        </div>

        <b-button class="m-4" size="lg">Saiba Mais</b-button>
      </div>

  </section>
</template>

<style lang="scss" scoped>

section {
  display: flex;
  justify-content: center;
  align-items: center;

  margin: 1em;
  padding: 4em;
  border: 1px solid aquamarine;

  img {
    clip-path: circle(38%);
    width: 25em;
    margin: 1em;
  }

  h1 {
    font-size: 4em;
    text-align: right;
  }

  h5 {
    text-align: right;
  }

  button {
    background-color: #4591c4;

    &:hover {
        background-color: #4591c4;
        transition: 1s;
        position: relative;
        top: 8px;
    }
  }
}

.icons {
  padding-top: 2em;

  a {
    padding: 1em;

    &:hover {
      font-size: 1.1em;
    }
  }
}
</style>
