<template>
    <div class="jumbo">
        <h1>Benvenuto</h1>
        <button>Accedi</button>
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
        height: 700px;
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

    button {
        position: absolute;
        top: 62%;
        left: 50%;
        transform: translate(-50%, -50%);
        padding: 0.5rem 1rem;
        border: none;
        border-radius: 10px;
        font-weight: bolder;
        background-color: aquamarine;
    }
</style>