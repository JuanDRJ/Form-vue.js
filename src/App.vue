<template>
 
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <h1>{{msg}}</h1> -->
 <div id="estacion-platzi">
   <img src="https://static.platzi.com/media/user_upload/Page%201-d8d869f4-7130-4ae9-9907-2fa809bd136a.jpg" alt="estacion-platzi">
   <h2>Registro estación platzi</h2>
   <p>Nombre</p>
   <input type="text" name="" id="">
   <p>Apellido</p>
   <input type="text">
   <p>Cargo</p>
   <input type="text">

   <div class="button-container">
    <button>ENVIAR</button>
   </div>
 </div>

</template>

<script>


export default {
  name: 'App',
  data(){
    return{
      msg: "Helou World¿d",
    }
  },
  components: {
    
  }
}

</script>

<style>


@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

template{
  background-color: #dfdfdf;
}
#estacion-platzi{
  font-family: 'roboto';
  margin: 100px auto;
  width: 300px;
  display: flex;
  flex-direction: column;
  justify-items: center;
  color: #212121;
  border: #212121 2px;
}

#estacion-platzi h2{
  color: #00BFD6;
}

#estacion-platzi p{
  color: #FF9300;
  font-size: 12px;
}

#estacion-platzi input{
  border: none;
  border-bottom: 1px solid #FF9300;
  font-size: 15px;
}

#estacion-platzi input:{
  border: none;
  border-bottom: 1px solid #FF9300;
  font-size: 15px;
}

input[type=text]:focus {
  border: 1px solid red;
  outline: none;
}
.button-container{
  display: inline-flex;
  justify-content: flex-end;
}
#estacion-platzi button{
  background-color: #00BFD6;
  border:none;
  color: white;
  font-size: 16px;
  margin: 10px;
  height: 50px;
  width: 100px;
  font-weight: bold;
  border-radius: 4%;
  transition: 0m;

}

#estacion-platzi button:hover{
  background-color: #0a8492;
  transition: 500ms ease;
  

}



</style>
