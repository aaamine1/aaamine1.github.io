<template>
  <div class="navbar">
    <div class="logo-home" id="top">
      <a href="https://github.com/aaamine1/aaamine1.github.io" class="logo-top" target="_blank">aaamine*</a>
    </div>
    <div class="navigation-links">
      <ul >
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li> <a href="#projects">Projects</a></li>
      </ul>
    </div>
  </div>



</template>


<style>
/* General styling for the whole div */
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

/* Styling the top-left "logo" */
  .logo-top {
    font-size: 6rem;
    text-decoration: none;
    color: #252322;
    padding: 40px;
    font-family: "JMH Typewriter Dry";
    font-weight: 700;
  }

  .logo-top:hover {
    text-decoration: none;
    color: white;
  }


/* Side link styling */
  .navigation-links ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin: 0;
  }

  .navigation-links li {
    text-decoration: none;
    font-size: 2.5rem;
    padding: 40px;
    font-family: "JMH Typewriter Dry";
    font-weight: 700;


  }

  .navigation-links li a {
    color: #252322;
  }

  .navigation-links li a:hover {
    opacity: 0.8;
    text-decoration: none;
  }


  /* MEDIA QUERIES  */

  @media(max-width: 1300px) {
    .navigation-links li {
        padding: 15px;
    }
  }

  @media(max-width: 1180px) {
    .navigation-links {
    display: none;


  }

  @media(max-width: 768px) {
    .navbar {
    display: flex;
    justify-content: center;
    }
  }

  @media(max-width: 560px) {
    .logo-top{
      font-size: 3.5rem;
    }
  }
}
</style>
