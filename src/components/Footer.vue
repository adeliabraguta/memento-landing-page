<script setup>

</script>

<template>
  <div class="container">
    <div class="contacts">
      <h3>Contacts</h3>
      <a href=tel:+37378105160>078 105 160</a>
      <a href="mailto:officialmementoapp@gmail.com">officialmementoapp@gmail.com</a>
    </div>
    <img src="../assets/logo%20black.png"/>
  </div>
</template>

<style scoped>
.container {
  background-color: #FFF3C4;
  padding: 2vw 10vw;
  display: flex;
  justify-content: space-between;
  @media screen and (max-width: 800px) {
    flex-direction: column;
  }
  .contacts {
    display: flex;
    flex-direction: column;
    justify-content: center;

    h3, a {
      @media screen and (max-width: 800px) {
        font-size: 20px;
      }
    }

    h3 {
      letter-spacing: 1px;
    }

    a {
      font-size: 18px;
      padding-top: 12px;
      color: #222222;
      text-decoration: none;
    }
  }

  img {
    height: 150px;
  }
}
</style>
