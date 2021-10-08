<template>
<div id="app">




<div class="navbar sticky-top flex-row">

<div class="logo">  <i class="fas fa-umbrella-beach"></i></div>


<ul class="desktop">
      <router-link tag="li"  to="/">  ألرئيسية</router-link> 
      <router-link tag="li"  to="/Company"> ألشركات</router-link> 
      <router-link tag="li"  to="/TypeInsurance"> منتجات ألتأمين </router-link>
      <router-link tag="li"   to="/ConceptInsurance">مفاهيم تأمينية</router-link> 
      <router-link tag="li"   to="/Commitments"> إلتزامات المؤمن </router-link>  
      <router-link tag="li"  to="/Contract"> أعرف حقوقك</router-link> 
      <router-link tag="li"  to="/WhatInsurance">هل التأمين ضروري</router-link> 
      <router-link tag="li"   to="/ContactUs">تواصل معنا</router-link>
</ul>            


<div class="Social">

      <span><div class="Facebook"> <a href="https://www.facebook.com/search/top?q=al%20jazeera%20channel%20-%20%D9%82%D9%86%D8%A7%D8%A9%20%D8%A7%D9%84%D8%AC%D8%B2%D9%8A%D8%B1%D8%A9"><i class="fab fa-facebook-f"></i></a> </div></span>
     <span><div class="Twitter"> <a href="https://twitter.com/ajarabic?lang=en"><i class="fab fa-twitter"></i></a> </div></span>
     <span><div class="Whatsapp"> <a href=""><i class="fab fa-whatsapp"></i></a> </div> </span>
     <span><div class="instgram"> <a href="https://www.instagram.com/aljazeera/"><i class="fab fa-instagram"></i></a> </div></span>
     <span><div class="google"> <a href="https://www.aljazeera.net"><i class="far fa-envelope"></i></a> </div></span>
        
</div>




<button class="navbar-toggler " type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <i class="fas fa-bars"></i>
</button>


<div class="collapse navbar-collapse" id="navbarSupportedContent">

<ul class="mobile">
      <router-link tag="li"  to="/">  ألرئيسية</router-link> 
      <router-link tag="li"  to="/Company"> ألشركات</router-link> 
      <router-link tag="li"  to="/TypeInsurance"> منتجات ألتأمين </router-link>
      <router-link tag="li"   to="/ConceptInsurance">مفاهيم تأمينية</router-link> 
      <router-link tag="li"   to="/Commitments"> إلتزامات المؤمن </router-link>  
      <router-link tag="li"  to="/Contract"> أعرف حقوقك</router-link> 
      <router-link tag="li"  to="/WhatInsurance">هل التأمين ضروري</router-link> 
      <router-link tag="li"   to="/ContactUs">تواصل معنا</router-link>
</ul> 

</div>

</div>



<router-view />
</div>
</template>



<style lang="scss" scoped>


*{
  padding: 0;
  margin: 0;

}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
   font-family: 'Heebo', sans-serif;
  font-family: 'Tajawal', sans-serif;
  
 
}




.navbar{
  padding: 20px ;
  background-color: #0b1e3a;
  color: white;
  direction: rtl;
  overflow:hidden;
  z-index: 300;
   box-shadow: 0 5px 5px 2px rgba(0, 0, 0, .05);
 
}

.flex-row{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;

}


.fa-umbrella-beach{
    color: white;
    font-size: 2.2rem;

}

li{

  display: inline-block;
  list-style: none;
  color: white;
  padding: 0 2rem;
  cursor: pointer;
  font-size: 1.1rem;
  font-weight: bold;
  
}

.mobile li{
  display: none;
}

 li {
    color: white;

    &.router-link-exact-active {
      color: gold;
    }
  }

li:hover{
  color: gold;
  transition: .5s all ease;
}



.Social span{
  display: inline-block;
  color: white;
  position: relative;
   margin:10px 5px 0 0

}

.Social span div{
  width: 40px;
  height: 40px;
  border-radius: 50%;
  cursor: pointer;
}

.Social span div:hover{
  background-color: gold;
  transition: .5s all ease;

}

.Social a {
  position: absolute;
  top: 50%;
  left: 50%;
  transform:translate(-50%, -50%);
  font-weight: 900;
  color: white;
  font-size: 23px;
  text-decoration: none;

 
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

.google{
 background-color: #ff0844
}

.Whatsapp{
  background-image: linear-gradient(to top, #0ba360 0%, #3cba92 100%);
  
}


.navbar > button{
  height: 40px;
  width: 40px;
  border: 2px solid white;
  position: relative;
  display: none;
}

.fa-bars{
  color: white;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  
}



@media (max-width:1700px){

  .Social span{
    display: none;
  }

   .navbar .desktop li{
    display: none; 
  }


   .navbar .mobile li{
    display: block; 
    text-align: right;
    position: relative;
    right: -25px;
    margin: 20px 0 0 0;
  }

 .navbar > button{
  display: block;
 

  }
}

  
</style>