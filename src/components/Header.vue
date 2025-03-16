<template>
   <header>
        <div class="header">
            <img :src="logoSabby" alt="">
        </div>
   </header>
</template>
<script setup>
    import logoSabby from '/public/Images/logoSabby.png';
</script>
<style  scoped>
    header{
        width: 100%;
        height: 120px;
        background-color: #000;
        .header{
            width: 80%;
            height: 100%;
            margin: auto;
            /* background-color: red; */
            display: flex;
            align-items: center;
            img{
                width: 100px;
            }
        }
    }
</style>
