<template>
<footer>

<div class="container">
<div class="row">
<div class="col-lg-3 col-md-6 col-sm-12 col-xs-12"> <p> أتصل بنا  <i class="fas fa-mobile-alt"></i> </p> 
            
<h5>+249929994349</h5>

<h5>+249117001768</h5>

<h5>+249922633075</h5>
</div>

<div class="col-lg-3 col-md-6 col-sm-12 col-xs-12"> <p> موقعنا <i class="fas fa-map-marker-alt"></i> </p> 

<h5>الخرطوم</h5>

<h5>امدرمان</h5>

<h5>بحري</h5> 
              
</div>

<div class="col-lg-3 col-md-6 col-sm-12 col-xs-12"> <p> فروعنا <i class="fas fa-compress-arrows-alt"></i> </p> 
                
<h5>فرع السوق العربي</h5>

<h5>فرع السوق الشعبي</h5>

<h5>فرع سوق اللفة</h5> 
                
</div>

<div class="col-lg-3 col-md-6 col-sm-12 col-xs-12"> <p> مجالاتنا <i class="fas fa-cart-plus"></i> </p> 

                  
<h5>مجال ألتامين</h5>

<h5>التجارة الالكترونية</h5>

<h5>التحويلات المصرفية</h5> 
                  
</div>
              
</div>

<div class="move">
<p> وسائل ألدفع ألاكتروني </p>
<div class="pay">
<span> <i class="fab fa-cc-visa"></i> </span>
<span> <i class="fab fa-cc-paypal"></i> </span>
<span> <i class="fab fa-cc-mastercard"></i>  </span>
<span> <i class="fab fa-bitcoin"></i>  </span>
</div>
</div>
</div>


<div class="mov">
<button type="button" class="login" data-toggle="modal" data-target="#signin" data-whatever="@mdo">   التسجيل في المنصة  </button>

<div class="modal fade" id="signin" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<h4 class="modal-title" id="exampleModalLabel"> شاشة إنشاء حساب </h4></div>
        
<div class="modal-body">
<form>
<div class="form-group">
<label for="recipient-name" class="col-form-label">أدخل إسمك الاول</label>
<input type="text" class="form-control" id="recipient-name">
</div>

<div class="form-group">
<label for="recipient-name" class="col-form-label">أدخل إسمك الثاني </label>
<input type="text" class="form-control" id="recipient-name">
</div>
        
<div class="form-group">
<label for="recipient-name" class="col-form-label"> أدخل عنوان البريد الالكنروني </label>
<input type="text" class="form-control" id="recipient-name">
</div>
        
<div class="form-group">
<label for="recipient-name" class="col-form-label">ادخل كلمة السر </label>
<input type="text" class="form-control" id="recipient-name">
</div>
        

</form>
</div>
<div class="modal-footer">
<button type="button" class="sub" data-dismiss="modal">إغلاق</button>
<button type="button" class="sub">تسجيل</button>
</div>
</div>
</div>
</div>

    

<button type="button" class="login" data-toggle="modal" data-target="#log" data-whatever="@mdo"> تسجيل الدخول  </button>

<div class="modal fade" id="log" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<h4 class="modal-title" id="exampleModalLabel"> شاشة تسجيل الدخول </h4></div>
        
<div class="modal-body">
<form>
      
        
<div class="form-group">
<label for="recipient-name" class="col-form-label">  أدخل عنوان البريد الالكتروني </label>
<input type="text" class="form-control" id="recipient-name">
</div>
        
<div class="form-group">
<label for="recipient-name" class="col-form-label"> أدخل كلمة السر الخاص بك  </label>
<input type="text" class="form-control" id="recipient-name">
</div>

</form>
</div>
<div class="modal-footer">
<button type="button" class="sub" data-dismiss="modal">إغلاق</button>
<button type="button" class="sub">دخول</button>
</div>
</div>
</div>
</div>

</div>   
</footer>
</template>

<style lang="scss" scoped>
footer{
    padding: 40px 0;
    background-color: #0b1e3a;
    color: white;
    

   .login{
    display:block;
    width:150px;
    height: 40px;
    background-color: #0b1e3a;
    color:white;
    font-weight: bold;
    margin:5px 5px;
   

}

.mov{
    display:flex;
    justify-content:center;
    margin:40px 0 0 0;
 
}

.login:hover{
    background-color: gold;
    transition: .5s all ease;
    border: 0;
    
}



.modal{
  z-index:5000;
}

.modal-header{
         direction: rtl;
         color: #0b1e3a;
     }

 label{
        color: #0b1e3a;
        float: right;
    }

    input{
        direction: rtl;
    }

      .modal-footer button{
        background-color: #0b1e3a;
        color: white;
        width: 70px;

    }

    .modal-footer > button:hover{
        background-color: gold;
        color: white;
    }


  
  

    .pay{
        position: relative;
        font-size: 40px;
        color: white;
        padding-bottom: 40px;
      
span{
    margin: 0 10px;
    
}
    }

    


.move{
    position: relative;
    top: 40px;
}


    p{
        margin: 20px 0;
        font-size: 20px;
        font-weight: bold;
        
    }

    h5{
        margin: 40px 0;
        position: relative;
        top: 5px;
        font-size: 15px;
        
    }
    
}
</style>