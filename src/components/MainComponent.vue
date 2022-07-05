<script></script>

<template>
  <div>HEJ</div>
  <h1>Aplikacja pogodowa</h1>
  <input 
    type="text" 
    placeholder="wpisz lokalizację"
    v-model="localeInfo"
  >


</template>
<script>
    export default{
      data(){
        return{
          localeInfo: "San Escobar"
        };
      },
      mounted(){
        console.log("hello")
        this.localeInfo="San Escobar"



      }
    }

</script>
<style>
h1 {
  color: aquamarine;
}
</style>
