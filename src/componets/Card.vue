<template>
    
    <div>
        <img v-bind:src="url" v-bind:alt="nombre">
        <h1>{{ nombre }}</h1>
        <p>{{ descripcion }}</p>
        <h6>{{ precio }}</h6>
        <a v-bind:src="url" target="_blank">Comprar</a>
    </div>

</template>

<script>
    export default{
        props:{
            url:{
                String,
            },
            nombre:{
                String,
            },
            descripcion:{
                String,
            },
            precio:{
                String,
            },
        },
    };
</script>

<style scoped>

    
    div{
        display: inline-block;
        text-align: center;
        border: .5px solid #000000;
        padding: 1%;
        border-radius: 15px;
        margin: 4px;
        width: 360px;
        height: 360px;
        
    }
    img{
        width: 8rem;
        height: 8rem;
        padding: 0.5rem;
        background: rgb(0, 0, 0);
    }
    a{
        
        text-decoration: none;
        color: snow;
        background: #FFAC41;
        padding: 0.3rem;
        border-radius: 5px;
        border: 1px solid #f2f2f2;
    }
</style>