<template>
    <div class="fishing">
        <div class="form">
        <h1>Choose a fishing spot you want to fish</h1>
        <br/>
        <h2><a href="/OceanFish">Ocean fish</a></h2>
        <h2><a href="/RiverFish">River fish</a></h2>
        <h2><a href="/MountainFish">Mountain fish</a></h2>
        <h2><a href="/DesertFish">Desert fish</a></h2>
        <h2><a href="/GingerIsland">Ginger island fish</a></h2>
        </div>



    </div>
</template>


<style scoped>  


.fishing {
   background-image:url('@/assets/pozadina_svega.png');
background-size: cover;
background-position: center;
vertical-align: 100vh;
height: 100%;
width: 100vw;
display: flex;
justify-content: center;
align-items: center;
flex-direction: column;
background-repeat: repeat-x;
}

.form {
  background-color:#FFAB56;
  border-radius: 20px;
  padding: 100px;
  width: 500px;
  margin:auto ;
  margin-bottom:50px;
  margin-top:50px;
  background-position: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

    
}

h2{

margin-bottom:12px;
   font-size: 30px;
    color: black;
    font-family: Press Start 2P, sans-serif;
    font-weight: bold;
    margin-top: 20px;
    background: #CD9148;
    padding: 10px;
    width:500px;
    border-radius: 20px;
    align-content: center;
    display:inline-block;
    row-gap: 55px;
    position:relative;

}



h1{

 font-size: 40px;
    color: #80461B;
    text-align: center;
   position:relative;
   top:-25px;

}




</style>