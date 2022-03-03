<template>
    <section id="resume">
        <div id="content-title-resume">
            <h2>Resumo</h2>
            <h1>Minhas Qualificações:</h1>
        </div>
        <h2>Experiência Profissional:</h2>
        <div class="content-resume">
            <div class="timeline-header">
                <h3>Developer Freelancer</h3>
                <p>2021 - Presente</p>
            </div>
            <div class="timeline-icon-content">
                <fa :icon="['fas', 'suitcase']" class="timeline-icon" />
            </div>
            <div class="timeline-info">
                <p>Sou desenvolvedor Full Stack em ReactJS e NodeJs.
                    Experiência em criação de formulários, login screen e clone
                    de projetos utilizando o Figma. Possuo alguns projetos que são realizados
                    no curso DevClub e alguns pequenos projetos pessoais, como um card digital de contatos
                    e um site para um time de Futsal da minha cidade.
                </p>
            </div>
        </div>
        <h2>Histório Acadêmico:</h2>
        <div class="content-resume">
            <div class="timeline-header">
                <h3>DevClub</h3>
                <p>2021 - Presente</p>
            </div>
            <div class="timeline-icon-content">
                <fa :icon="['fas', 'graduation-cap']" class="timeline-icon" />
            </div>
            <div class="timeline-info">
                <p>O DevClub é curso online com vídeoaulas para quem quer sair do completo
                    zero e se tornar programador. Atualmente sou aluno do DevClub e estou estudando 
                    e conhecendo as seguintes tecnologias:
                    <br>
                    <br>
                    - HTML5, CSS3 e Flexbox e JavaScript;
                    <br>
                    <br>
                    - Versionamento de código (Git e Github);
                    <br>
                    <br>
                    - No Front-end: ReactJs, JSX, ferramentas como React Hooks (Use State, 
                    Use Effect, etc), styled components, consumo de API com axios, criação 
                    e navegação de rotas com React Router DOM (Link, Use History);
                    <br>
                    <br>
                    - No Back-end: Node, utilização dos códigos HTTP, ferramentas como express, 
                    uuid, Middlewares, Insomnia e nodemon.
                    <br>
                    <br>
                    Atualmente estou estudando VueJs (inclusive toda está página foi feita com esse framework) 
                    e me aprofundando em Back-end com Docker, EsLint,
                    Prettier, Sequelize e Banco de Dados.
                </p>
            </div>
        </div>
        <div class="content-resume">
            <div class="timeline-header">
                <h3>FATEC Adib Moisés Dib - Tecnólogo em Automação Industrial</h3>
                <p>2014 - 2018</p>
            </div>
            <div class="timeline-icon-content">
                <fa :icon="['fas', 'graduation-cap']" class="timeline-icon" />
            </div>
            <div class="timeline-info">
                <p>Na faculdade tive aulas de lógica de programação onde
                    aprendi algoritmos primitivos: constantes, variáveis,
                    expressões, etc. Além de estruturas sequenciais, de
                    seleção e de repetição;
                </p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Resume'
}
</script>

<style scoped>
    #resume{
        background: #83B5CF;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 20px;
    }
    #resume h2{
        color: #325484;
        margin: 30px 0;
    }
    #content-title-resume h2{
        font-size: 25px;
        text-align: center;
        text-transform: uppercase;
        letter-spacing: 2px;
        color: #325484;
    }
    #content-title-resume h1{
        font-size: 40px;
        text-align: center;
        color: white;
    }
    .timeline-header{
        width: 20vw;
    }
    .timeline-header h3{
        font-size: 22px;
    }
    .timeline-header p{
        font-size: 18px;
        color: #444444;
    }
    .timeline-info{
        width: 30vw;
    }
    .timeline-info p{
        color: #444444;
    }
    .timeline-icon-content{
        width: 10vw;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .timeline-icon{
        font-size: 35px;
        color: white;
        text-align: center;
        background: #325484;
        border-radius: 50%;
        padding: 20px;
    }
    .content-resume{
        display: flex;
        flex-direction: row;
        margin-top: 50px;
        align-items: flex-start;
    }
</style>