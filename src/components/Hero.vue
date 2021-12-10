<template>
    <div>
        <h2>Jumbo description</h2>
    </div>
</template>

<script>
    export default {
    name: 'Hero'
    }
</script>


<style scoped>
    div{
        position: relative;
        margin: auto;
        width: 800px;
        height: 500px;
        background-color: #fff;
        background-image: url(https://picsum.photos/800/500);
        border-radius: 30px;
        border: 5px solid rgba(0,0,0,0.6);
        filter: grayscale(0.3) brightness(0.8);
        transition: filter 0.3s;
        cursor: pointer;
    }

    div:hover{
        filter: none;
    }

    h2{
        position: absolute;
        bottom: 15px;
        left: 35px;
        background-color: rgba(0,0,0,0.6);
        color: #fff;
        padding: 10px 20px;
        border-radius: 10px;
    }
</style>