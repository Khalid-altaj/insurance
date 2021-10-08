<template>
    <div class="contact">
<p> تواصل معنا</p>

<div class="container">
<div class="bag">





<div class="modal-body">
<form>
<div class="form-group">
<label for="recipient-name" class="col-form-label">إسم المرسل </label>
<input type="text" class="form-control" id="recipient-name">
</div>


<div class="form-group">
<label for="recipient-name" class="col-form-label"> الرقم الوطني الخاص بك</label>
<input type="text" class="form-control" id="recipient-name">
</div>


<div class="form-group">
<label for="recipient-name" class="col-form-label"> رقم الهاتف الخاص بك </label>
<input type="text" class="form-control" id="recipient-name">
</div>


<div class="form-group">
<label for="recipient-name" class="col-form-label"> عنوان الايميل الخاص بك </label>
<input type="text" class="form-control" id="recipient-name">
</div>

<div class="form-group">
<label for="message-text" class="col-form-label">إجعل رسالتك بناءة</label>
<textarea class="form-control" id="message-text"></textarea>
</div>

</form>
</div>


<div class="modal-footer">
<button type="button" class="btn btn-primary">إرسال وجهة نظرك</button>
</div>
</div>
</div>
</div>



</template>




<style lang="scss" scoped>

.contact{
    padding-top: 70px;
    padding-bottom: 70px;

    p{
        color: #0b1e3a;
        font-size: 20px;
        font-weight: bold;
        text-align: center;

    }


    .bag{
        width: 100%;     
        background-color: #0b1e3a;
    }

    label{
        float: right;
        color: white;
    }

    textarea{
        direction: rtl;
        height: 7rem;
    }

    input{
        direction: rtl;
    }

   button{
       background-color: white;
       color: black;
       font-weight: bold;
   }

   button:hover{
       background-color: gold;
   }
}
</style>