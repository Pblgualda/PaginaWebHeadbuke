<script  setup>

</script>

<template>
    <div class="sobre-nosotros">
        <h1>Sobre Nosotros</h1>
        <p></p>
    </div>
    <div class="miembros">
        <div class="miembro">
            <img src="/img/Xabi.png" alt="Miembro 1" class="miembro-img">
            <h3>Pablo Gualda Parra</h3>
            <p>Fundador de Headbuke</p>
            <p>Guionista de videojuegos</p>
            <p>Desarrollador de videojuegos</p>
        </div>
        <div class="miembro">
            <img src="/img/Xabi.png" alt="Miembro 2" class="miembro-img">
            <h3>Javier Morente Parra</h3>
            <p>Co-fundador de Headbuke</p>
            <p>Guionista de videojuegos</p>
            <p>Desarrollador de videojuegos</p>
        </div>
        <div class="miembro">
            <img src="/img/Marcos.png" alt="Miembro 3" class="miembro-img">
            <h3>Marcos Velasco Acosta</h3>
            <p>Co-fundador de Headbuke</p>
            <p>Game tester</p>
        </div>
    </div>
</template>
<style scoped>
.sobre-nosotros {
    text-align: center;
    margin: 40px 0;
}

h1
{
    margin-bottom: 20px;
    color: black;
}
.miembros {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}
.miembro {
    text-align: center;
    margin: 20px;
}
.miembro-img {
    width: 20rem;
    height: 30rem;
    border-radius: 10%;
    margin-bottom: 10px;
    object-fit: cover;
}
</style>