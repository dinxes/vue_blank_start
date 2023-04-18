<template>

    <h1> {{message}} </h1>
	<h2> {{message_two}} </h2>
  
</template>

<script>
export default {
  data(){
    return {
      message: 'DINX 1',
      message_two: 'Perlo 2',

    }
  }

}
</script>



<style scoped>
body{

  box-sizing: border-box;
  
}

.spacer{
  margin-top: 100px;
}

.background {
  background: rgb(176, 15, 98);
  background: radial-gradient(circle, rgba(84, 98, 98, 0.286) 0%, rgb(254, 254, 254) 100%); 
  width: 100%;
  height: 100%;
  position: fixed;
  z-index: -1;
  box-sizing: border-box;
  left: 0;
  top: 0;
}
</style>
