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
      /* domyślne dane - ładowane na początku*/
      data(){
        return{
          localeInfo: "San Escobar"
        };
      },
      mounted(){
        console.log("hello");
        console.log(this)
        this.localeInfo= "hejo";



      }
    }

</script>
<style>
h1 {
  color: aquamarine;
}
</style>
