<template>
    <div id="container-sidebar">
        <img src="../assets/foto_avatar.jpg" alt="foto-avatar">
        <div id="container-nav">
            <ul>
                <a href="#container-banner" class="link-nav">
                    <fa :icon="['fas', 'house']" class="icon-nav" />
                    <li>Início</li>
                </a>
                <a href="#about" class="link-nav">
                    <fa :icon="['fas', 'circle-user']" class="icon-nav" />
                    <li>Sobre</li>
                </a>
                <a href="#resume" class="link-nav">
                    <fa :icon="['fas', 'address-card']" class="icon-nav" />
                    <li>Resumo</li>
                </a>
                <a href="#portfolio" class="link-nav">
                    <fa :icon="['fas', 'laptop-code']" class="icon-nav" />
                    <li>Portfólio</li>
                </a>
            </ul>
        </div>
        <div id="container-social-links-nav">
            <a href="https://github.com/allesonbarbosa" class="social-link">
                <fa :icon="['fab', 'github']"  class="icon-nav"/>
            </a>
            <a href="https://www.linkedin.com/in/alleson-de-moura-barbosa-193802210/" class="social-link">
                <fa :icon="['fab', 'linkedin']"  class="icon-nav"/>
            </a>
        </div>
    </div>
</template>

<script>
export default {
    name: 'SideBar'
}
</script>

<style scoped>
    #container-sidebar{
        width: 150px;
        height: 100vh;
        position: fixed;
        background: #325484;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
    }
    #container-sidebar img{
        width: 130px;
        border-radius: 50%;
        margin: 20px 0;
    }
    #container-nav ul{
        list-style: none;
    }
    #container-nav li{
        margin: 20px 0;
        font-size: 18px;
    }
    .link-nav{
        color: white;
        text-decoration: none;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    .link-nav:hover{
        cursor: pointer;
        color: #83B5CF;
    }
    .icon-nav{
        font-size: 30px;
    }
    #container-social-links-nav{
        display: flex;
        gap: 20px;
    }
    .social-link{
        color: white;
    }
    .social-link:hover{
        cursor: pointer;
        color: #83B5CF;
    }
</style>