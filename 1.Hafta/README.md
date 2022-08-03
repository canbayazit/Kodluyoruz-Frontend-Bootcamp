# Kodluyoruz Frontend Bootcamp
 ## ÖDEV 1
 * cssbattle.dev'de 'Battle #13 - #70 Froggy' kodunun yazılması..	[Bu Linkten Ulaşabilirsiniz](https://cssbattle.dev/play/70)
 
 Code :
 ***
 ```
<div class="head">
     <div class="head-bottom"></div>  
</div>
<div class="head-noise"></div>
<div class="eye"></div>
<style>
  body{
    background: #293462;
    display:flex;
    justify-content:center;
    align-items:center;    
  }
  .head{
    width: 149px;
    height: 100px;
    margin-top:20px;
    background: #A64942;
    border-radius:120px;
    position:relative;
    overflow:hidden;
  }
   .head-bottom{
    background:#FE5F55;
    position:absolute;
    top:-30;
    left:-28;
    
    width:204px;
    height:100px;
    border-radius:50%;
     z-index:1;
  }
  .head-noise{
    border:5px solid #293462; 
    background:#293462;
    top:160;
    left:185.5;
    border-radius:50%;
    position:absolute;
    z-index:2;
    -webkit-box-reflect:right 10px;
  }
  .eye{
    position:absolute;
    width:10px;
    height:10px;
    border:10px solid #FFF1C1;
    top:95px;
    left:150px;
    border-radius:50%;
    box-shadow:0 0 0 10px #FE5F55;
    background:#293462;
    z-index:4;
    -webkit-box-reflect:right 40px;
    
  }
</style>


 ```
 
