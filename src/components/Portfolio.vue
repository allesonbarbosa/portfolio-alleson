<template>
    <section id="portfolio">
        <div id="title-portfolio">
            <h2>Portfolio</h2>
            <h1>Estes são alguns dos meus projetos:</h1>
        </div>
        <div class="dashboard-portfolio">
            <div class="item-portfolio" id="item-login">
                <img src="../assets/projeto_01.png" alt="foto-projeto">
                <div class="item-portfolio-info">
                    <h1>Login Interface</h1>
                    <p>Tela de Login utilizando apenas HTML e CSS.</p>
                    <a href="https://github.com/allesonbarbosa/login-interface">Confira</a>
                </div>
            </div>
            <div class="item-portfolio" id="item-code-burger">
                <img src="../assets/projeto_02.png" alt="foto-projeto">
                <div class="item-portfolio-info">
                    <h1>Code Burger</h1>
                    <p>Sistema de pedidos de uma haburgueria utilizando ReactJs e Nodejs.</p>
                    <a href="https://github.com/allesonbarbosa/code-burger-order-interface">Confira</a>
                </div>
            </div>
            <div class="item-portfolio" id="item-pokedex">
                <img src="../assets/projeto_03.png" alt="foto-projeto">
                <div class="item-portfolio-info">
                    <h1>Pokedex</h1>
                    <p>Projeto de uma Pokedex consumindo uma API pública com os Pokemons separados por tipo.</p>
                    <a href="https://pokedex-alleson.netlify.app/">Confira</a>
                </div>
            </div>
            <div class="item-portfolio" id="item-mosqueteiros">
                <img src="../assets/projeto_04.png" alt="foto-projeto">
                <div class="item-portfolio-info">
                    <h1>Site Mosqueteiros Futsal</h1>
                    <p>Landing page para um time de Futsal da minha cidade que faço parte.</p>
                    <a href="https://mosqueteiros-futsal.netlify.app/">Confira</a>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Portfolio'
}
</script>

<style scoped>
    #title-portfolio{
        text-align: center;
        margin: 30px 0;
    }
    #title-portfolio h2{
        color: #83B5CF;
        font-size: 25px;
        letter-spacing: 2px;
        text-transform: uppercase;
        margin-bottom: 20px;
    }
    #title-portfolio h1{
        color: #325484;
        font-size: 40px;
    }
    .dashboard-portfolio{
        width: 800px;
        height: 800px;
        margin: 0 auto;
        display: flex;
        flex-direction: row;
        justify-content: center;
        gap: 20px;
    }
    .item-portfolio{
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 250px;
        border: 2px solid #83B5CF;
        border-radius: 8px;
    }
    #item-login{
        height: 750px;
    }
    #item-code-burger{
        height: 500px;
        position: relative;
    }
    #item-pokedex{
        height: 450px;
    }
    #item-mosqueteiros{
        height: 450px;
    }
    .item-portfolio-info{
        background: #83B5CF;
        width: 100%;
        height: 100%;
        text-align: center;
        margin-top: 15px;
    }
    .item-portfolio-info h1{
        color: #325484;
        font-size: 25px;
    }
    .item-portfolio-info p{
        color: #444444;
        font-size: 16px;
        margin: 30px 0;
    }
    .item-portfolio-info a{
        color: #325484;
        background-color: white;
        text-decoration: none;
        text-align: center;
        text-transform: uppercase;
        letter-spacing: 2px;
        padding: 15px;
        border: 4px solid;
        border-radius: 14px;
    }
    .item-portfolio-info a:hover{
        cursor: pointer;
        color: white;
        background-color: #325484;
        transition: 0.5s;
    }
</style>