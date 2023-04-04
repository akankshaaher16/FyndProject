<template>
    <div>
      <img class="logo" src="../assets/kids_logo.jpg" alt="logo" />
        <h1 style="color: #f29c39; font-size: 50px; ">Sign Up </h1>
        <center>
          <div class="register">
          <input type="text" placeholder="Enter Your Name">
          <input type="text" placeholder="Enter Student's Name">
          <input type="text" placeholder="Enter Email">
          <button id="signup">Sign Up</button>
        </div>
        </center>
    </div>
</template>

<script>
export default {
  name: 'App',
  
}
</script> 

<style>
.logo{
  width: 300px;
}
.register input{
  width: 300px;
  height: 40px;
  padding-left: 20px;
  display: block;
  margin-bottom: 30px;
  margin-right: auto;
  margin-left: auto;
  border: 1px solid orangered;
}
.register button{
  width: 150px;
  height: 40px;
  border:1px solid orangered ;
  color: #f29c39;
  cursor: pointer;
}
.register{
  border: 5px solid #f29c39;
  padding: 40px;
  width: 400px;
}

</style>




/* .footimg{
  display: grid;
  float: right;
  gap: 10px;
} */