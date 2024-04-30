<h1 align="center">Hola, soy MomoDev 👋</h1>
<img src="https://cdn.leonardo.ai/users/40344ce2-26b2-4ac4-9a5c-2672816e4111/generations/e295c5cf-885c-4d05-acad-12344c4fa929/Default_Sad_raccoon_looking_down_animation_style_Studio_Ghibli_0.jpg" alt="Sad Raccoon">

<div class="pacman">
  <div class="pacman-top"></div>
  <div class="pacman-bottom"></div>
  <div class="feed"></div>
</div>

<style>
  @import url(https://fonts.googleapis.com/css?family=Press+Start+2P);
  
  html{
    background-color:#000;
    border-bottom:solid 5px blue;
    border-top:solid 5px blue;
    overflow-x:hidden;
    padding-bottom:142px;
  }
  
  p{
    color:#FFF;
    font: 50px 'Press Start 2P',  cursive;
    margin:200px 139px;
    position:absolute;
    text-align:center;
  }
  
  .pacman{
    margin:40px 10px;
  }
  
  .pacman-top{
    background-color:yellow;
    height:100px;
    width:200px;
    border-radius:100px 100px 0 0;
    animation: spin1 0.5s infinite linear;
  }
  
  .pacman-bottom{
  background-color:yellow;
    height:100px;
    width:200px;
    border-radius:0 0 100px 100px;
    animation: spin2 0.5s infinite linear;
  }
  
  .feed {
  margin-top: -185px;
  margin-left:15px;
  width: 45px;
  height: 45px;
  border-radius: 30%;
  -moz-animation: eat 1s linear 0s infinite;
  -webkit-animation: eat 1s linear 0s infinite;
  animation: eat 1s linear 0s infinite;
  }   
  
  /* Animation*/
  
  @keyframes spin1 {
  	0%  {transform: rotate(0deg);}
  	50%{transform: rotate(-35deg);}
    
  }
  @keyframes spin2 {
  	0%  {transform: rotate(0deg);}
    50%{transform: rotate(35deg);}	
  }
  
  @-moz-keyframes spin1 {
  	0%  {transform: rotate(0deg);}
  	50%{transform: rotate(-35deg);}
    
  }
  @-moz-keyframes spin2 {
  	0%  {transform: rotate(0deg);}
    50%{transform: rotate(35deg);}	
  }
  
  @-webkit-keyframes spin1 {
  	0%  {transform: rotate(0deg);}
  	50%{transform: rotate(-35deg);}
    
  }
  @-webkit-keyframes spin2 {
  	0%  {transform: rotate(0deg);}
    50%{transform: rotate(35deg);}	
  }
  
  @keyframes eat {
  	0% { box-shadow: 
        100px 65px 0 0 white, 
        300px 65px 0 0 white, 
        500px 65px 0 0 white, 
        700px 65px 0 0 white,
        900px 65px 0 0 white, 
        1100px 65px 0 0 white, 
        1300px 65px 0 0 white;}
    
  100% { box-shadow: 
        0px 65px 0 0 white, 
        100px 65px 0 0 white,
        300px 65px 0 0 white, 
        500px 65px 0 0 white, 
        700px 65px 0 0 white, 
        900px 65px 0 0 white, 
        1100px 65px 0 0 white;}
  }
  }
  
  
  @-moz-keyframes eat {
  	0% { box-shadow: 
        100px 65px 0 0 white, 
        300px 65px 0 0 white, 
        500px 65px 0 0 white, 
        700px 65px 0 0 white,
        900px 65px 0 0 white, 
        1100px 65px 0 0 white, 
        1300px 65px 0 0 white;}
    
  100% { box-shadow: 
        0px 65px 0 0 white, 
        100px 65px 0 0 white,
        300px 65px 0 0 white, 
        500px 65px 0 0 white, 
        700px 65px 0 0 white, 
        900px 65px 0 0 white, 
        1100px 65px 0 0 white;}
  }
  }
  
  
  @-webkit-keyframes eat {
  	0% { box-shadow: 
        100px 65px 0 0 white, 
        300px 65px 0 0 white, 
        500px 65px 0 0 white, 
        700px 65px 0 0 white,
        900px 65px 0 0 white, 
        1100px 65px 0 0 white, 
        1300px 65px 0 0 white;}
    
  100% { box-shadow: 
        0px 65px 0 0 white, 
        100px 65px 0 0 white,
        300px 65px 0 0 white, 
        500px 65px 0 0 white, 
        700px 65px 0 0 white, 
        900px 65px 0 0 white, 
        1100px 65px 0 0 white;}
  }
  }
</style>
