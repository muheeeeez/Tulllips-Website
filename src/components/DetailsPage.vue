<template>
  <div class="container">
    <div class="heading-container">
      <h1 class="heading">
        <span>Design.</span>
        Develop. Deploy.
      </h1>
    </div>
    <div class="main">
      <h1>
        Tullips is a platform for Designers and Developers; giving them the
        resources needed to get inspiration and create amazing stuffs
      </h1>
    </div>
    <div class="button-container">
      <button class="start-button">Start Creating</button>
      <div class="pink-shadow">
        <button class="demo-button">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="1em"
            viewBox="0 0 384 512"
          >
            <!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
            <path
              d="M73 39c-14.8-9.1-33.4-9.4-48.5-.9S0 62.6 0 80V432c0 17.4 9.4 33.4 24.5 41.9s33.7 8.1 48.5-.9L361 297c14.3-8.7 23-24.2 23-41s-8.7-32.2-23-41L73 39z"
            />
          </svg>
          Get a Demo
        </button>
      </div>
    </div>
    <div class="info"><p>BACKED BY THE BEST TECH TEAMS IN THE WORLD</p></div>
    <div class="image-container">
      <div class="row">
        <img src="\src\img\Netflix_Logo.png" alt="Image" class="flex-item" />
        <img src="\src\img\Microsoft_Logo.png" alt="Image" class="flex-item" />
        <img src="\src\img\YouTube_Logo.png" alt="Image" class="flex-item" />
        <img src="\src\img\Adobe_Logo.png" alt="Image" class="flex-item" />
      </div>
      <div class="row">
        <img src="\src\img\Medium_Logo.png" alt="Image" class="flex-item" />
        <img src="\src\img\Spotify_Logo.png" alt="Image" class="flex-item" />
        <img src="\src\img\Twitch_Logo.png" alt="Image" class="flex-item" />
        <img src="\src\img\Discord_Logo.png" alt="Image" class="flex-item" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.heading-container {
  text-align: center;
  font-size: 85px;
  font-weight: 700;
  line-height: normal;
  background-clip: text;
  font-family: "Poppins", sans-serif;
  height: 270px;
}
.heading-container span {
  background: linear-gradient(90deg, #b642df 0%, rgba(250, 81, 172, 0.72) 100%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.main {
  width: 65%;
  color: #5b5b5b;
  margin: auto;
  font-style: normal;
  text-align: center;
  font-family: "Inter", "san-serif";
  font-weight: 400;
  font-size: 20px;
  line-height: 36px;
}
.button-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  margin-top: 70px;
  margin-bottom: 50px;
}
.start-button {
  padding: 10px 40px;
  justify-content: center;
  align-items: center;
  gap: 8px;
  border-radius: 4px;
  background: #000;
  color: #fff;
  font-family: "Inter", "san-serif";
  text-align: center;
  font-weight: 500;
  font-size: 15px;
  cursor: pointer;
}
.demo-button {
  padding: 10px 40px;
  justify-content: center;
  align-items: center;
  gap: 8px;
  border-radius: 4px;
  background: transparent;
  color: #000;
  font-family: "Inter", "san-serif";
  text-align: center;
  font-weight: 500;
  font-size: 15px;
  border: 1.3px solid #b642df;
  box-shadow: 0px px 0px 0px hsl(284, 71%, 57%);
  cursor: pointer;
  line-height: 30px;
}
.info {
  color: #5b5b5b;
  font-family: "Inter", "san-serif";
  font-size: 11px;
  font-weight: 600;
  text-align: center;
}
.image-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  /* height: 100vh; */
  margin: 0;
  gap: 16px;
}

.row {
  display: flex;
  flex-wrap: wrap;
  flex: 1;
  justify-content: center;
  gap: 36px;
}
.pink-shadow{
  box-shadow:0px 0px 60px 0px  #b642df;
}
.flex-item {
  margin: 10px;
  max-width: calc(100vw - 20px);
  flex: 1 0 auto;
  box-sizing: border-box;
}
@media screen and (min-width: 100px) and (max-width: 1300px) {
  .heading-container {
    font-size: 20px;
    height: min-content;
  }
  .main {
    width: 100vw;
    text-align: start;
    font-size: 15px;
  }
  .button-container {
    gap: 30px;
  }

  .start-button,
  .demo-button {
    padding: 10px 40px;
    font-size: 15px;
  }
}
</style>