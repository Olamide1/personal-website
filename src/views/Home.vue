<template>
  <div class="container is-fullhd">
   <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="#">
    <p class="title is-size-1"><!-- i am  -->Lamide.</p>
    </a>

    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false"  data-target="navMenu">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div class="navbar-menu" id="navMenu">
    <div class="navbar-end">
    <div class="navbar-item">
      <router-link to="/about">About me</router-link>
    </div>
    <div class="navbar-item">
      <a href="https://ear1.com/theakomolafe" target="_blank">Contact me</a>
    </div>
    <div class="navbar-item">
      <a href="https://chats.landbot.io/v3/H-980334-Z96UMYAUAXLRZOEL/index.html" target="_blank">My resume</a>
    </div>
    <div class="navbar-item">
        <div class="buttons">
          <button class="button is-dark">
            <strong>🌖</strong>
          </button>
        </div>
    </div>
  </div>
  </div>
</nav>
    

  <section class="hero is-medium has-text-centered">
  <div class="hero-body">
   <img src="https://blush.design/api/download?shareUri=dBgbvJC7M&c=Hair_0%7E030067_Skin_0%7Eaf5b27_Top_0%7E870cf7&w=300&h300&fm=png" alt="photo"> 
      <p class="title is-size-1">
        Hola, Lamide here.
</p>
    <p class="subtitle is-size-3">
      the Jay-Z of product.
    </p>
    <p class="block is-size-4">I enjoy talking about user experience, customer acquisition, documentation and monetization. 
      I have had experiences as a software engineer, product startup founder, and now as a full time product manager.</p>
          <a href="https://ear1.com/theakomolafe" target="_blank" class="button is-dark">Talk to me</a>

  </div>
</section>


<div class="has-text-justified">
  <section class="section is-medium">
  <h1 class="title is-size-1">My philosophy</h1>
  <h2 class="subtitle is-size-4">
    I build using a simple <strong>Philosophy</strong>, they're simple and they are-
  </h2>

  <div class="columns">
  <div class="column card">
          <p class="card-header-title is-size-2">Simplicity</p>
  <div class="card-content">
    <div class="content is-size-4">
    </div>
  </div>
</div>

 <div class="column card">
             <p class="card-header-title is-size-2">Intuitiveness</p>

  <div class="card-content">
    <div class="content is-size-4">
            The product has to be able to answer potential questions customers might have. 
            For products to be intuitive, they have to be simple. Simple enough to tell 
            customers/users what they need to do before they are prompted to.
    </div>
  </div>
</div>


 <div class="column card">
                <p class="card-header-title is-size-2">Emotiveness</p>

  <div class="card-content">
    <div class="content is-size-4">
      Comes from the little things- celeberating tiny goals like your first completed set 
      of steps in the funnel. Simulating and triggering emotions like happiness, a sense of accomplishment etc.
    </div>
  </div>
</div>
  </div>

</section>
</div>


<footer class="footer">
  <div class="content has-text-centered">
    <p>
      <strong>Made with 💚  by Olamide Akomolafe.</strong>
    </p>

    <div class="columns">
      <a href="https://twitter.com/theakomolafe" target="_blank" class="column">Twitter</a>
      <a href="https://linkedin.com/in/theakomolafe" class="column" target="_blank">Linkedin</a>
      <a href="https://instagram.com/theakomolafe" class="column" target="_blank">IG</a>
    </div>
  </div>
</footer>
  </div>
</template>

<script>
// @ is an alias to /src
document.addEventListener('DOMContentLoaded', () => {

  // Get all "navbar-burger" elements
  const $navbarBurgers = Array.prototype.slice.call(document.querySelectorAll('.navbar-burger'), 0);

  // Check if there are any navbar burgers
  if ($navbarBurgers.length > 0) {

    // Add a click event on each of them
    $navbarBurgers.forEach( el => {
      el.addEventListener('click', () => {

        // Get the target from the "data-target" attribute
        const target = el.dataset.target;
        const $target = document.getElementById(target);

        // Toggle the "is-active" class on both the "navbar-burger" and the "navbar-menu"
        el.classList.toggle('is-active');
        $target.classList.toggle('is-active');

      });
    });
  }

});
export default {
  name: 'Home',
  components: {
    
  }
}
</script>
