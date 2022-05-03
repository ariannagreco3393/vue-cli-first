<template>
    <div class="jumbo">
        <h1>Benvenuto</h1>
    </div>
</template>

<script>
export default {
  name: 'jumboTron',
}
</script>

<style scoped>
    .jumbo {
        margin: auto;
        position: relative;
        background-image: url(https://i.picsum.photos/id/10/2500/1667.jpg?hmac=J04WWC_ebchx3WwzbM-Z4_KC_LeLBWr5LZMaAkWkF68);
        height: 800px;
        background-position: center;
    }
   
    h1 {
        color: white;
        font-size: 60px;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
</style>