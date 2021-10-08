<template>
    <div class="Social2">

      <span><div class="Facebook"> <a href="https://www.facebook.com/search/top?q=al%20jazeera%20channel%20-%20%D9%82%D9%86%D8%A7%D8%A9%20%D8%A7%D9%84%D8%AC%D8%B2%D9%8A%D8%B1%D8%A9"><i class="fab fa-facebook-f"></i></a> </div></span>
     <span><div class="Twitter"> <a href="https://twitter.com/ajarabic?lang=en"><i class="fab fa-twitter"></i></a> </div></span>
     <span><div class="Whatsapp"> <a href=""><i class="fab fa-whatsapp"></i></a> </div> </span>
     <span><div class="instgram"> <a href="https://www.instagram.com/aljazeera/"><i class="fab fa-instagram"></i></a> </div></span>
     <span><div class="Gmail"> <a href="https://www.aljazeera.net"><i class="far fa-envelope"></i></a> </div></span>
        
</div>
</template>


<style lang="scss">

@media (min-width:1500px) {
    .Social2{
        display: none;
    }
    
}

.Social2{
    position: fixed;
    top: 60%;
    left: 0px;
    transform: translateY(-50%);
    z-index: 1000;
  
  }
  
  .Social2 a{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 50px;
    height: 50px;
    padding: 0px;
    margin: 0px;
    line-height: 0px;
   color: white;
    border: 2px solid white ;
    box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.5);
    font-size: 20px;
 
  }

  .Social2 a:hover{
   background-color: #ffaa01;
    color: black;
   background-blend-mode: multiply;
    transition: all ease 0.5s;
   
    
    
  }

  .Facebook{
    background-color: rgb(55, 88, 143);
  }

  .Twitter{
    background-color: rgb(93, 154, 255);
  }

  .instgram{
    background-image: linear-gradient(-20deg, #fc6076 0%, #ff9a44 100%);
  }

  .Gmail{
   background-color: #ff0844
  }

  .Whatsapp{
    background-image: linear-gradient(to top, #0ba360 0%, #3cba92 100%);
  }

</style>