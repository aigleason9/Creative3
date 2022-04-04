<template>
  <div class="home">
    <div class="overlay">

      <div class="welcome">
        <h1>Welcome to the bookstore!</h1>
        <h3>We're always getting new books, so please check back soon if you want a book that isn't currently available. Or contact us to request a particular book!</h3>
      </div>
            
    </div>
  </div>
</template>

<style scoped>

  .home {
    background-image: url(https://live.staticflickr.com/7294/9004993292_3d8f026110_b.jpg);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
    height: 83vh;
  }

  /* .overlay::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 1;
    background-color: black;
    opacity: 0.35;
  }

  .overlay > * {
      z-index: 100;
  } */

  .welcome {
    position: absolute;
    text-align: center;
    top: 50%;
    transform: translateY(-50%);
    margin-left: 30px;
    margin-right: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  h1, h3 {
    text-align: center;
    color: white;
    text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000;
  }

  h1 {
    margin-bottom:20px;
    font-size: 40px;
  }

  h3 {
    font-size: 38x;
  }
</style>
