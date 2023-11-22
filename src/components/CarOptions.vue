<template>
  <h2>Auto - Options API</h2>
  <p>Marca: {{ brand  }}</p>
  <p>Modelo: {{ model  }}</p>
  <p>Potencia: {{ power  }}</p>

  <button @click="upPower(40)" > Aumentar </button>
  <button @click="downPower(20)"> Disminuir </button>
</template>

<script>
export default {
  
  data(){
    return{
      brand: "Seat",
      model: "Leon",
      power: "50",
    }
  },
  methods:{
    upPower(){
      this.power++;
    },
    downPower(){
      this.power--;

    }
  }
};


</script>
<style >
  
</style>