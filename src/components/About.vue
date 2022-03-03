<template>
    <section id="about">
        <div id="content-about-info">
            <h2>Sobre</h2>
            <h1>Vou falar um pouco sobre mim:</h1>
            <p>Tecnólogo de Automação Industrial por formação sempre gostei de programação 
            desde a época da faculdade onde aprendi linguagens básicas como C e C++. 
            No ano de 2021 resolvi me aprofundar na área, onde o que era ser apenas um hobby 
            se tornou uma paixão. Atualmente sou aluno do DevClub e estou estudando e 
            conhecendo linguagens front-end e back-end. Meu objetivo nesse ano de 2022 é conseguir
            meu emprego como programador.
            </p>
        </div>
        <div id="content-about-row">
            <div id="container-perfil-info">
                <h2>Perfil</h2>
                <ul>
                    <li>
                        <b>Nome:</b>
                        <p>Alleson de Moura Barbosa</p>
                    </li>
                    <li>
                        <b>Nascimento:</b>
                        <p>10 de Janeiro de 1994</p>
                    </li>
                    <li>
                        <b>Cargo:</b>
                        <p>Freelancer, Full-Stack Developer</p>
                    </li>
                    <li>
                        <b>Website:</b>
                        <p>https://alleson-barbosa.netlify.app/</p>
                    </li>
                    <li>
                        <b>Email:</b>
                        <p>allesonbarbosa@yahoo.com.br</p>
                    </li>
                </ul>
            </div>
            <div id="container-skills-info">
                <h2>Skills</h2>
                <ul>
                    <li>
                        <h3>HTML</h3>
                        <div class="bar-progress" id="bar-80-percent">
                            <p>80%</p>
                        </div>
                    </li>
                    <li>
                        <h3>CSS</h3>
                        <div class="bar-progress" id="bar-80-percent">
                            <p>80%</p>
                        </div>
                    </li>
                    <li>
                        <h3>JavaScript</h3>
                        <div class="bar-progress" id="bar-70-percent">
                            <p>70%</p>
                        </div>
                    </li>
                    <li>
                        <h3>ReactJs</h3>
                        <div class="bar-progress" id="bar-65-percent">
                            <p>65%</p>
                        </div>
                    </li>
                    <li>
                        <h3>VueJs</h3>
                        <div class="bar-progress" id="bar-50-percent">
                            <p>50%</p>
                        </div>
                    </li>
                    <li>
                        <h3>NodeJs</h3>
                        <div class="bar-progress" id="bar-50-percent">
                            <p>50%</p>
                        </div>
                    </li>
                    <li>
                        <h3>Git e Github</h3>
                        <div class="bar-progress" id="bar-70-percent">
                            <p>70%</p>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'About'
}
</script>

<style scoped>
    #about{
        margin: 0 auto;
        width: 70vw;
        display: flex;
        flex-direction: column;
        gap: 60px;
        padding: 40px;
    }
    #about h2{
        color: #83B5CF;
        font-size: 25px;
        letter-spacing: 2px;
        text-transform: uppercase;
    }
    #about h1{
        color: #325484;
        font-size: 40px;
    }
    #content-about-info{
        text-align: center;
    }
    #content-about-info h1{
        margin-bottom: 20px;
    }
    #content-about-info p{
        font-size: 18px;
        color: #888888;
        text-align: justify;
    }
    #content-about-row ul{
        list-style: none;
    }
    #content-about-row li{
        font-size: 20px;
    }
    #content-about-row{
        margin: 0 auto;
        display: flex;
        flex-direction: row;
    }
    #container-perfil-info{
        width: 35vw;
    }
    #container-perfil-info li{
        margin: 20px 0;
    }
    #container-perfil-info p{
        color: #888888;
    }
    #container-skills-info{
        width: 35vw;
    }
    #container-skills-info h2{
        margin-bottom: 15px;
    }
    #container-skills-info li{
        margin-bottom: 10px;
    }
    #container-skills-info h3{
        font-size: 22px;
    }
    .bar-progress p{
        color: white;
        font-size: 16px;
        padding-left: 10px;
    }
    .bar-progress{
        height: 20px;
        background: #325484;
        border-radius: 5px;
    }
    #bar-80-percent{
        width: 80%;
    }
    #bar-70-percent{
        width: 70%;
    }
    #bar-65-percent{
        width: 65%;
    }
    #bar-50-percent{
        width: 50%;
    }
</style>