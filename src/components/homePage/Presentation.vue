<template>
  <section>
    <img src="../../assets/photo01.jpg" alt="" />

    <div>
      <h4>Olá, eu sou</h4>
      <h1>Eder Sato</h1>
      <h3>Desenvolvedor Front End</h3>

      <div class="icons">
        <a href="https://www.linkedin.com/in/eder-da-rosa-sato/">
          <b-icon
            icon="linkedin"
            opacity="0.8"
            font-scale="2"
            variant="primary"
          ></b-icon>
        </a>
        <a href="https://github.com/edersato/">
          <b-icon
            icon="github"
            opacity="0.8"
            font-scale="2"
            variant="white"
          ></b-icon>
        </a>
        <a href="mailto:edersato@gmail.com">
          <b-icon
            icon="envelope"
            opacity="0.8"
            font-scale="2"
            variant="white"
          ></b-icon>
        </a>
      </div>
      <b-button class="m-4" size="lg">Saiba Mais</b-button>
    </div>
  </section>
</template>

<style lang="scss" scoped>
section {
  display: flex;
  justify-content: space-evenly;
  align-items: center;

  

  margin: 1em;
  padding: 4em;
  border: 1px solid #4591c4;

  img {
    clip-path: circle(38%);
    width: 25em;
    margin: 1em;
  }

  h1 {
    font-size: 4em;
    text-align: right;
  }

  h3 {
    color: white;
  }

  h4 {
    text-align: right;
    color: white;
  }

  button {
    background-color: #4591c4;
    border: #4591c4;
    width: 100%;

    &:hover {
      background-color: #2e688f;
      transition: 1s;
    }
  }
}

.icons {
  padding-top: 2em;

  a {
    padding: 1em;

    &:hover {
      font-size: 1.05em;
    }
  }
}
</style>
