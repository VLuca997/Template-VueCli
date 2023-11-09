<script>


</script>

<template>
    <div class="container-box">
        <a href="http://www.google.com">
            <h1>Hello World</h1>
        </a>
    </div>
</template>

<style>
    
    .container-box {
        display: grid;
        place-items: center; /* Centra i figli sia orizzontalmente che verticalmente */
        height: 100vh; /* Imposta l'altezza al 100% della viewport height */
    }
    h1 {
        font-weight: bolder;
        text-align: center;
        font-size: 4rem;
        border: 1rem linear-gradient(55deg, #e0ff33,#33e0ff);
        border-radius: 16rem 0.5rem;
        padding: 2rem 3rem;
        background: linear-gradient(45deg, #f50202, #ffc533);
        box-shadow: 10px 15px 10px rgba(0, 0, 0, 0.5); /* Applica l'ombra */
        cursor: pointer;
    }
    a:hover{
        scale: 2;
        color: blue;

        
    }
    a{
        color: yellow;
        text-decoration: none;
    }
    
</style>