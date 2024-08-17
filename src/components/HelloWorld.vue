<script setup>
</script>

<template>
  <div>
    <div class="container-1">
      <img class="logo" src="../assets/logo%20copy.png" alt="memento logo"/>
      <h1>Memento</h1>
      <p>Memorize your memories</p>
      <h3>Contacts</h3>
      <a href=tel:+37378105160>078 105 160</a>
      <a href="mailto:officialmementoapp@gmail.com">officialmementoapp@gmail.com</a>
      <div class="more">
        <span><a href="#call">Let's start</a></span>
        <hr/>
      </div>
    </div>
    <div class="callaction" id="call">
      <a target="_blank" href="https://forms.gle/agbACm29tbeyWxaL8">Devino <span>Early Adopter</span></a>
    </div>

    <div class="container-2" id="section-1">
      <h2>Problema</h2>
      <div class="grid">
        <div>
          <p>
            <span class="number">5.3 miliarde</span> de imagini făcute în <span class="time">24 ore</span>
          </p>
          <img class="arrow" src="../assets/Arrow%2002.png" alt="arrow"/>
          <p class="p-2">
            <span class="number">70%</span> nu sunt partajate
          </p>
        </div>
        <img src="../assets/Group%201.png" alt="diagrama"/>
      </div>
    </div>
    <div class="container-3">
      <img src="../assets/Frame%209.png" alt="diagrama"/>
      <p><span class="percentage">94%</span> <span class="plus">+</span>
        din toate imaginile sunt făcute de telefon
      </p>
    </div>
    <div class="container-4">
      <h2>Soluția</h2>
      <div>
        <p>Aplicație unde ții cont de toate amintirile tu și prietenii tăi</p>
        <img class="desk" src="../assets/Solutia.png"/>
        <img class="mobile" src="../assets/Solutia-mobile.png"/>
      </div>
    </div>
    <div class="container-5">
      <h2>
        Cum lucrează
      </h2>
      <div>
        <img class="desk" src="../assets/Frame%2027.png" alt="diagrama"/>
        <img class="mobile" src="../assets/mobile-frame27.png" alt="diagrama"/>
      </div>
    </div>
    <div class="container-6">
      <h2>Business model - freemium</h2>
      <div>
        <img src="../assets/premium-1.png" alt="abonaments premium"/>
        <img src="../assets/premium-2.png" alt="abonaments premium"/>
        <img src="../assets/premium-3.png" alt="abonaments premium"/>
      </div>
    </div>
    <div class="container-7">
      <h2>De ce suntem mai buni?</h2>
      <p>Desigur sunt foarte multe alternative care fac doar un singur lucru foarte bine, dar memento integreaza
        toate aceste optiuni intro aplicatie centralizata.</p>
      <div>
        <img src="../assets/Frame%2028.png"/>
      </div>
    </div>
    <div class="container-8">
      <h2>Intrare pe piață</h2>
      <div class="grid">
        <img src="../assets/clipboard-document-list.png"/>
        <img src="../assets/arrows-pointing-in.png"/>
        <img src="../assets/window.png"/>
        <h3>Beneficii pentru Early Adopters</h3>
        <h3>Marketing local</h3>
        <h3>Marketing pe rețele de socializare</h3>
      </div>
    </div>
    <div class="container-9">
      <h2>Roadmap</h2>
      <img src="../assets/Frame%2029.png"/>
    </div>
    <div class="container-10">
      <h2>Team</h2>
      <div class="grid">
        <div>
          <img src="../assets/grigore.png"/>
          <h3>Guzun Grigore</h3>
          <span>Java Developer</span>
        </div>
        <div>
          <img src="../assets/adelia.png"/>
          <h3>Braguța Adelia</h3>
          <span>React & Vue Developer</span>
        </div>
        <div>
          <img src="../assets/tudor.png"/>
          <h3>Bivol Tudor</h3>
          <span>Sales & Business</span>
        </div>
      </div>
    </div>
    <div class="callaction">
      <a target="_blank" href="https://forms.gle/agbACm29tbeyWxaL8">Devino <span>Early Adopter</span></a>
    </div>
  </div>
</template>

<style scoped>
h2 {
  padding-top: 96px;
  font-size: 64px;
  @media screen and (max-width: 800px) {
    font-size: 32px;
  }
}

.container-1 {
  position: relative;
  height: 100vh;
  display: flex;
  flex-direction: column;
  background: rgb(34, 34, 34);
  background: linear-gradient(137deg, rgba(34, 34, 34, 1) 4%, rgba(23, 184, 151, 1) 47%, rgba(247, 201, 72, 1) 100%);
  @media screen and (max-width: 800px) {
    height: 90vh;
  }

  .logo {
    padding-top: 80px;
    padding-left: 10vw;
    width: 350px;
    height: auto;
    padding-bottom: 16px;
    @media screen and (max-width: 800px) {
      padding-top: 180px;
      width: 250px;
    }
  }

  h1 {
    padding-left: 10vw;
    color: white;
    font-size: 128px;
    @media screen and (max-width: 800px) {
      width: 250px;
      font-size: 64px;
    }
  }

  p {
    padding-left: 10vw;
    color: white;
    font-size: 2vw;
    @media screen and (max-width: 800px) {
      font-size: 20px;
    }
  }

  h3, a {
    padding-left: 10vw;
    @media screen and (max-width: 800px) {
      font-size: 20px;
    }
  }

  h3 {
    padding-top: 64px;
    letter-spacing: 1px;
  }

  a {
    font-size: 18px;
    padding-top: 12px;
    color: #222222;
    text-decoration: none;
  }


  .more {
    cursor: pointer;

    span a {
      letter-spacing: 1px;
      color: white;
      font-size: 24px;
      position: absolute;
      bottom: 24px;
      right: 40px;
      transition: all 0.5s ease-in-out;
    }

    hr {
      position: absolute;
      bottom: 24px;
      right: 24px;
      border: none;
      background-color: #fff;
      height: 70px;
      width: 4px;
      animation: hr 3s ease-in-out infinite;
      transition: all 0.5s ease-in-out;
    }

    &:hover {
      span {
        color: #17B897;
      }

      hr {
        background-color: #17B897;
      }
    }
  }

}

@keyframes hr {
  0% {
    height: 30px;
  }

  50% {
    height: 70px;
  }
  100% {
    height: 30px;
  }
}

.container-2 {
  padding: 0 10vw;

  h2{
    padding-top: 0px;
  }
  .grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 128px;

    div {
      display: grid;

      p {
        padding-top: 48px;
        font-size: 48px;
        @media screen and (max-width: 800px) {
          font-size: 24px;
          padding-top: 24px;
        }

        .number {
          color: #17B897;
        }

        .time {
          color: #FF5555;
        }

      }

      .p-2 {
        padding-top: 0;
      }

      .arrow {
        justify-self: end;
        height: auto;
        width: 70px;
        right: 64px;
      }
    }

    img {
      width: 100%;
    }

    @media screen and (max-width: 800px) {
      grid-template-columns: 1fr;
      gap: 96px;
    }
  }
}

.container-3 {
  padding: 128px 10vw 0 10vw;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 128px;
  @media screen and (max-width: 800px) {
    grid-template-columns: 1fr;
    gap: 48px;
    padding: 96px 10vw 0 10vw;
  }

  img {
    width: 100%;
  }

  p {
    padding-top: 48px;
    font-size: 48px;
    @media screen and (max-width: 800px) {
      font-size: 32px;
      padding-top: 24px;
      grid-row: 1;
    }

    .percentage {
      font-size: 96px;
      color: #016457;
      @media screen and (max-width: 800px) {
        font-size: 48px;
      }
    }

    .plus {
      font-size: 96px;
      color: #17B897;
      @media screen and (max-width: 800px) {
        font-size: 48px;
      }
    }
  }
}

.container-4 {
  padding: 48px 10vw 96px 10vw;
  margin-top: 96px;
  background-color: #C6F7E9;
  @media screen and (max-width: 800px) {
    margin-top: 48px;
    height: auto;
    padding: 64px 10vw;
  }

  h2 {
    font-size: 64px;
    @media screen and (max-width: 800px) {
      font-size: 32px;
    }
  }

  p {
    padding-top: 48px;
    font-size: 24px;
    text-align: center;
    @media screen and (max-width: 800px) {
      padding-top: 32px;
    }
  }

  .desk {
    padding-top: 16px;
    width: 100%;
    @media screen and (max-width: 800px) {
      display: none;
    }
  }

  .mobile {
    display: none;
    @media screen and (max-width: 800px) {
      display: initial;
      width: 100%;
    }
  }
}

.container-5 {
  padding: 0 10vw 96px 10vw;
  background-color: #FFF3C4;

  div {
    display: grid;
    justify-content: center;
    align-items: center;
  }

  h2 {
    font-size: 64px;
    @media screen and (max-width: 800px) {
      font-size: 32px;
    }
  }

  .desk {
    padding-top: 24px;
    height: 500px;
    width: auto;
    @media screen and (max-width: 800px) {
      display: none;
    }
  }

  .mobile {
    display: none;
    @media screen and (max-width: 800px) {
      display: initial;
      width: 100%;
    }
  }
}

.container-6 {
  padding: 0 10vw;

  div {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    @media screen and (max-width: 800px) {
      grid-template-columns: 1fr;
    }
    img {
      cursor: pointer;
      padding-top: 48px;
      width: 100%;
      transition: all 0.5s ease;
      @media screen and (max-width: 800px) {
        padding-top: 12px;
      }
      &:hover {
        transform: translateY(-30px);
      }
    }
  }
}

.container-7 {
  padding: 0 10vw;

  p {
    padding-top: 16px;
    font-size: 24px;
    @media screen and (max-width: 800px) {
      font-size: 24px;

    }
  }

  div {
    display: grid;
    justify-content: center;
    align-items: center;
    align-content: center;
    justify-items: center;

    img {
      padding-top: 64px;
      height: 70vh;
      @media screen and (max-width: 800px) {
        padding-top: 32px;
        height: auto;
        width: 100%;
      }
    }
  }
}

.container-8 {
  padding: 0 10vw;

  .grid {
    padding-top: 24px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    justify-items: center;
    column-gap: 96px;
    @media screen and (max-width: 800px) {
      font-size: 24px;
      grid-template-columns: 1fr 1fr 1fr;
      justify-items: center;
      column-gap: 24px;
      img {
        height: 50px;
      }
    }

    h3 {
      color: #17B897;
      @media screen and (max-width: 800px) {
        font-size: 16px;
      }
    }

    img {
      height: 150px;
      @media screen and (
        max-width: 800px) {
        height: 50px;
      }
    }
  }
}

.container-9 {
  padding-top: 128px;

  h2 {
    padding: 0 10vw;
  }

  img {
    padding-top: 16px;
    width: 100%;
  }
}

.container-10 {
  padding: 0 10vw 96px 10vw;

  .grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    column-gap: 12px;
    @media screen and (max-width: 800px) {
      font-size: 24px;
      grid-template-columns: 1fr;
      gap: 24px;
    }

    div {
      display: flex;
      flex-direction: column;
      align-items: center;

      h3 {
        padding-top: 12px;
        font-size: 24px;
      }

      span {
        color: #626262;
      }

      img {
        padding-top: 36px;
        width: 100%;
      }
    }
  }
}

.callaction {
  text-align: center;
  color: white;
  font-size: 30px;
  display: flex;
  justify-content: center;
  padding: 48px;
}

.callaction a {
  text-decoration: none;
  color: white;
  cursor: pointer;
  padding: 12px 18px;
  width: fit-content;
  border-radius: 13px;
  background: rgb(34, 34, 34);
  background: linear-gradient(137deg, rgba(34, 34, 34, 1) 4%, rgba(23, 184, 151, 1) 47%, rgba(247, 201, 72, 1) 100%);
  transition: all 0.5s ease;
  animation: call 3s ease-in-out infinite;
  &:hover{
    animation-play-state: paused;
  }
}

@keyframes call {
  0% {
    transform: scale(1.0);
  }

  50% {
    transform: scale(1.1);
  }

  100% {
    transform: scale(1.0);
  }
}
</style>
