<template>
    <nav class="navbar">
        <div>
            <a href="">Request a Quote</a>
            <a href="">Pay an Invoice</a>
            <a href="">Customer Portal</a>
            <a href="">Contact</a>
        </div>
  </nav>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .navbar {
        width: 100%;
        background-color: lightgray;
        overflow: auto;
        position: fixed;
        top: 0;
        width: 100%;

    }

    .navbar a {
        float: right;
        text-align: justify;
        padding: .5em;
        color: black;
        text-decoration: none;
        font-size: 12px;
    }

    .navbar a:hover {
        background-color: rgb(120, 171, 236);
    }

    .active {
        background-color: #2449c4;
    }
</style>