<template>
  <nav class="navbar">
    <div >
        <img class="img" alt="Wilbert logo" src="../assets/logo.png">
    </div>
    <div>
        <a href="./components/home.vue">Home</a>
        <a href="./components/products.vue">Products</a>
        <a href="./components/genesisgranite.vue">Genesis Granite</a>
        <a href="./components/aboutus.vue">About Us</a>
    </div>
  </nav>
</template>

<script>
   export default{

   }
</script>

<style>
    .navbar {
        width: 100%;
        background-color: white;
        overflow: auto;
    }

    .navbar a {

        padding: 3em;
        color: black;
        text-decoration: none;
        font-size: 17px;
        position: relative;
    }

    .navbar a:hover {
        background-color: rgb(120, 171, 236);
    }

    .active {
        background-color: #2449c4;
    }

    @media screen and (max-width: 500px) {
        .navbar a {
            float: none;
            display: block;
        }
    }
    .img {
        float: left;
        position: relative;
        height: 75px;
        width: auto;
    }
</style>