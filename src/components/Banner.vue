<template>
    <section id="container-banner">
        <div id="container-intro">
            <h2>Portfólio</h2>
            <h1>Alleson Barbosa</h1>
            <p>Full-Stack Developer</p>
            <a id="button-scroll-about" href="#about">
                Saiba Mais
                <fa :icon="['fas', 'angle-down']"/>
            </a>
            <div id="container-social-links-intro">
                <a href="https://github.com/allesonbarbosa" class="social-link-intro">
                    <fa :icon="['fab', 'github']"  class="icon-intro"/>
                </a>
                <a href="https://www.linkedin.com/in/alleson-de-moura-barbosa-193802210/" class="social-link-intro">
                    <fa :icon="['fab', 'linkedin']"  class="icon-intro"/>
                </a>
            </div>
        </div>
    </section>
</template>

<script>

export default {
    name: 'Banner'
}
</script>

<style scoped>
    #container-banner{
        width: calc(100vw - 165px);
        height: 100vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        background-image: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.8)), url(../assets/foto_banner.jpg);
        background-size: cover;
        background-repeat: no-repeat;
        background-position: 150px 0px;
        background-attachment: fixed;
    }
    #container-intro{
        width: 90%;
        height: 600px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    #container-intro h2{
        font-size: 32px;
        text-transform: uppercase;
        letter-spacing: 2px;
        color: #325484;
    }
    #container-intro h1{
        font-size: 84px;
        color: #83B5CF;
    }
    #container-intro p{
        font-size: 25px;
        color: white;
        letter-spacing: 2px;
    }
    #button-scroll-about{
        height: 60px;
        width: 180px;
        color: white;
        text-decoration: none;
        text-align: center;
        text-transform: uppercase;
        letter-spacing: 3px;
        padding: 15px;
        margin-top: 40px;
        border: 1px solid;
        border-radius: 14px;
        transition: 0.5s;
    }
    #button-scroll-about:hover{
        cursor: pointer;
        color: #83B5CF;
    }
    #container-social-links-intro{
        display: flex;
        gap: 40px;
        position: absolute;
        top: 90vh;
    }
    .icon-intro{
        font-size: 45px;
    }
    .social-link-intro{
        color: white;
    }
    .social-link-intro:hover{
        cursor: pointer;
        color: #83B5CF;
    }
</style>