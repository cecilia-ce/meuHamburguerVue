<template>
    <div id="main-image-div">
        <img id="image-main" src="/img/main-image.jpg" alt="mulher montando seu hamburguer">
    </div>
</template>

<script>
    export default{
        name: 'Banner'
    }
</script>
 
<style scoped>
    #main-image-div{
        /* height: 500px; */
        width: 40%;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #image-main{
        width: 100%;
    }

</style>
