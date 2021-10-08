<template>
<div class="commitments">

<div class="alert alert-warning alert-dismissible fade show" role="alert">
<i class="fas fa-exclamation-triangle"></i>
<p>تحذير: إن عدم احترام التزاماتكم قد يؤدي إلى فقدان حقوقكم</p>
<button type="button" class="close" data-dismiss="alert" aria-label="Close">
<span aria-hidden="true">&times;</span>
</button>
</div>


<p class="title"> إلتزامات مترتبة علي المستخدمين</p>


<div class="commit">

<div class="container">

<div class="row">
<div class="col-lg-4 col-md-4 col-sm-12 col-xs-12"> 
   
<div class="content"> 
<div class="enter">
<div class="circle"> <i class="fas fa-handshake"></i> </div>
<h5> أداء قسط التأمين </h5>

</div>
</div> </div>

<div class="col-lg-4 col-md-4 col-sm-12 col-xs-12"> <div class="content">

<div class="enter">
<div class="circle"> <i class="fas fa-car-crash"></i> </div>
<h5>  إشعار المؤمن في حالة وقوع حادث  </h5>
</div>  
    
</div> </div>

<div class="col-lg-4 col-md-4 col-sm-12 col-xs-12"> <div class="content">
    

<div class="enter">
<div class="circle"> <i class="fas fa-exclamation-triangle"></i> </div>
<h5>  إشعار المؤمن بكل تغيير قد يؤثر  </h5>
</div>   
    
</div> </div>

</div>



<div class="row">

<div class="col-lg-4 col-md-4 col-sm-12 col-xs-12"> <div class="content">
    

<div class="enter">
<div class="circle"> <i class="fas fa-bell"></i> </div>
<h5>  إشعار المؤمن في حالة التأمين المتعدد  </h5>
</div>     
    
</div> </div>

<div class="col-lg-4 col-md-4 col-sm-12 col-xs-12"> <div class="content">
    

<div class="enter">
<div class="circle"> <i class="fas fa-file-signature"></i> </div>
<h5> تقديم الإقرارات اللازمة لتحديد قيمة القسط  </h5>
</div>    

</div> </div>

<div class="col-lg-4 col-md-4 col-sm-12 col-xs-12"> <div class="content">
    

<div class="enter">
<div class="circle"> <i class="fas fa-tty"></i> </div>
<h5> التواصل مع مندوبي الشركة فقط  </h5>
</div>    

</div> </div>


</div> </div>

</div>




</div>

</template>





<style lang="scss" scoped>

.commitments{
    padding-bottom: 70px;
    

.title{
    font-size: 20px;
    font-weight: bold;
    color: #0b1e3a;
    text-align: center;
    padding-top: 70px;
}


.commit{
    padding-bottom: 50px;

   
}


.content{
    width: 100%;
    height: 220px;
    background-color: #0b1e3a;
    color: white;
    margin: 20px 0;
    position: relative;


     .overlay{
            position: absolute;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, .5);
            opacity: 0;
            transition: opacity 0.5s;
        }

    .content:hover .overlay{
        opacity: 1;
    }


    .enter{
        position: relative;
        color: white; 
    }

     


    .circle{
        position: absolute;
        top: 30px;
        left: 50%;
        transform: translateX(-50%);
        height: 90px;
        width: 90px;
        border-radius: 50%;
        border: 10px solid white;
    }

    .fa-handshake, .fa-bell, .fa-exclamation-triangle, .fa-car-crash, .fa-file-signature, .fa-tty{
        font-size: 40px;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }



    h5{
        font-weight: bold;
        font-size: 17px;
        position: relative;
        padding: 140px 0 0 0;
        padding-left: 10px;
        padding-right: 10px;
        margin: auto;
        
    }


}

.alert{
    margin:20px 0 0 0;


    p{
           color:  #c00000;
        font-size: 13px;  
    }

    .fa-exclamation-triangle{
        color:  #c00000;
        font-size: 30px;
    }

}
}



</style>