<template>
    <a href="#about" class="button">
      <!-- <img src="~/assets/down-arrow.png" class="down-arrow"> -->
      <img src="~/static/down-arrow.png" class="down-arrow">
    </a>
</template>

<style>
  .button {

    height: 50px;
    width: 50px;
    background-color: #252322;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: background 0.3s ease;
  }

  .button:hover {
    background-color: #4b4846;
  }

  .down-arrow {
    height: 15px;
    display: flex;

  }


</style>
