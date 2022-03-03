<template>
    <div id="container-footer">
        <div id="container-contacts">
            <div class="content-contacts">
                <fa :icon="['fas', 'location-dot']" class="icon-footer" />
                <p>Mauá - São Paulo</p>
            </div>
            <div class="content-contacts">
                <fa :icon="['fas', 'envelope']" class="icon-footer" />
                <p>allesonbarbosa@yahoo.com.br</p>
            </div>
            <div class="content-contacts">
                <fa :icon="['fas', 'phone']" class="icon-footer" />
                <p>(11) 98393-8205 - Whatsapp</p>
                <p>(11) 95670-8794 - Chamada</p>
            </div>
        </div>
        <div id="content-copyright">
            <p> © Todos os Direitos Reservados - Alleson Barbosa</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
    #container-footer{
        width: 100%;
        height: 250px;
        background: #83B5CF;
        padding: 40px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-around;
    }
    #container-contacts{
        display: flex;
        flex-direction: row;
        width: 100%;
    }
    .content-contacts{
        width: 33%;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 15px;
    }
    .icon-footer{
        font-size: 30px;
        color: #325484;
    }
    .content-contacts p{
        color: #555555;
        font-size: 18px;
    }
    #content-copyright{
        font-size: 18px;
        color: #555555;
    }
</style>