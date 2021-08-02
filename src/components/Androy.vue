<template>    
       <header>           
            <div class="content">
                <div class="left">
                    <h1><span>M</span>eck </h1>  
                    <h2>Digital Clinic Services</h2>                 
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem odit deserunt atque praesentium quasi quae eligendi, nostrum, neque </p>
                    <button>Talk to a Doctor</button>
                </div>
                <div class="right">

                </div>
            </div>
            <div class="bottom">
                Call us on 08030433499
            </div>
       </header>


    <div class="section-box">
        <div class="section-header">
            <h3>Today</h3>
        </div>
        <div class="boxes">
            <div class="box">
                <div class="circle">
                    <img src="https://img.icons8.com/dotty/80/000000/find-clinic.png"/>                  
                </div>
                  <h4>Lorem, ipsum dolor.</h4>
                </div>
            
             <div class="box">
                   <div class="circle">
                       <img src="https://img.icons8.com/pastel-glyph/64/000000/letter-from-clinic.png"/>
                   </div>
                     <h4>Lorem, ipsum dolor.</h4>
             </div>
            <div class="box">
                  <div class="circle"> 
                      <img src="https://img.icons8.com/ios/50/000000/hospital-room--v2.png"/>
                      </div>  
                        <h4>Lorem, ipsum dolor.</h4>          
        </div>
    </div>

    </div>
       
       <div class="services-section">
           <div class="services-header">
               <h3>Services</h3>
           </div>
           <div class="services">             
               <div class="service">
                  <img src="https://img.icons8.com/nolan/64/hospital-2.png"/>                 
                  <p>Lorem, ipsum dolor sit amet consectetur !</p>
               </div>
                <div class="service">
                    <img src="https://img.icons8.com/nolan/64/hospital-room.png"/>
                     <p>Lorem, ipsum dolor sit amet consectetur !</p>
                </div>
                 <div class="service">
                     <img src="https://img.icons8.com/nolan/64/hospital-bed.png"/>
                      <p>Lorem, ipsum dolor sit amet consectetur !</p>
                 </div>
           </div>
        </div> 

        <div class="section-cta">
            <div class="cta-text">
                <h3>Get in Touch</h3>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eligendi nostrum vitae aliquam, illo repellat minima voluptatibus ea fugiat perferendis at ad inventore eveniet veniam possimus molestiae dicta ipsa, dolore porro!</p>
                <button>Talk to a Doctor</button>
            </div>
        </div>

        <div class="footer-section">
            <div class="footer">
                <div class="item">
                    <div><b>Email:</b> lorem@gmail.com </div>
                   <div> <b>Phone:</b> 08030433499</div>
                   <div><b>Lagos Office Address: </b>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti voluptates accusamus tempora deserunt </div>
                   
                </div>
                 <div class="item">
                       <div><b>Email:</b> lorem@gmail.com </div>
                   <div> <b>Phone:</b> 08030433499</div>
                   <div><b>Enugu Office Address: </b>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti voluptates accusamus tempora deserunt </div>
                   
                 </div>
                  <div class="item">
                        <div><b>Email:</b> lorem@gmail.com </div>
                   <div> <b>Phone:</b> 08030433499</div>
                   <div><b>Warri Office Address: </b>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti voluptates accusamus tempora deserunt </div>
                   
                  </div>
            </div>
        </div>    
        <h3 class="bottom-text">Powered by Androy Software Systems @copyright 2021</h3> 
          
</template>

<script>
import CircleProgress from "vue3-circle-progress";
export default {
      name: 'Androy',
       components: {CircleProgress},
      props: {
     greeting: String
  }
}
</script>

<style scoped>
header{
    width:100%;
    height:90vh;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;  
}

header .content{
    height:90%;
    width: 100%;
    display: flex;
    justify-content:center;
    align-items: center;  
}

header .content .left{
    width:50%;
    height:100%;
     display: flex;
     flex-direction: column;
    justify-content:flex-end;
    align-items:flex-start;
    border-right:2px solid #fff;
      padding-left:50px ;
}
@media screen and (max-width: 1200px) {
    header .content .left{
        width:100%;
    }
}
header .content .left h1{
    font-size:calc(2.5vw + 20px);
    text-align: left;  
     color:#1d2366da;
       margin-left: 0;
    padding-left:0 ;
}
header .content .left h1 span{
    font-size:calc(3vw + 30px);
    margin-right: 0;
    padding-right:0 ;
    color:#6C63FF;
}
header .content .left h2{
    font-size:calc(2vw + 20px);
    text-align: left;  
    color:#1d2366da;
    margin-bottom:20px ;
}
header .content .left p{
    font-size:20px;
      text-align: left;
    width:80%;
    margin-left:0 ;
    padding-left:0;
      color:#1d2366da;
     line-height: 30px;
}
header .content .left button{
    width:80%;
    padding:15px 20px;
    margin-top:50px;
    border-radius: 10px;
    font-size: 25px;
    background-color: #6C63FF;
    color:#fff;
    border :0;
    transition: all 3s ease;
    margin-bottom: 50px;
}
header .content .left button:hover{
     background-color: #fff;
     color:#3F3D56;
     border:2px solid #3F3D56;
}
header .content .right{
    width:50%;
    height:100%;
     display: flex;
     flex-direction: column;
    justify-content:center;
    align-items: center;
     background-image: url('~@/assets/images/bg.png');
    background-size: cover;
    background-position: top;
    background-repeat: no-repeat;   
    background-size: cover;
}
@media screen and (max-width: 768px) {
    header .content .right{
        display:none;
    }
}
header .bottom{
    height:10%;
    width:100%;
    background-color: #6C63FF;
    /* background-image: linear-gradient(30deg, #c4c3c9,#3F3D56 80%); */
    display: flex;
    justify-content:center;
    align-items: center;
    font-size:25px;
    color:#fff;
    letter-spacing: 10px;
    font-weight: 900;
}









/* Services with box section */
.section-box{
    width:100%;
    display:flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin:150px auto;   
}
.section-box .section-header{
    width:100%;
    padding:10px;
    background-color: #6C63FF;
     padding-left: 150px;
}
.section-box .section-header h3{
    font-size: 35px;
    color:#fff;
    text-align: left;
}
.section-box .boxes{
    width:100%;
    display: flex;
    justify-content:space-around;
    align-items: center;
    padding:70px 0;
    background-color: #EEEEF7;    
}
@media screen and (max-width:800px){    
   .section-box .boxes{
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding:0 20px;
   }
}
.section-box .boxes .box{
    width:25%;
    height:40vh;  
    background-color: #fff;    
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    border-radius: 20px;
    box-shadow:3px 3px 3px #7a779b;
}
@media screen and (max-width:800px){    
    .section-box .boxes .box{
        width:100%;
        margin-top: 50px;
        margin-bottom:25px;
    }
}
 .section-box .boxes .box .circle{
     height:150px;
     width:150px;   
     border-radius: 50%;
     background-color: #E1E0FF;
     display: flex;
     justify-content:center;
     align-items: center;
       box-shadow:3px 3px 3px #7a779b;
 }   
 .section-box .boxes .box h4{
     margin-top: 20px;
 }
















.services-section{
     width: 90%;    
     margin: 150px auto; 
     display: flex;
     flex-direction: column;
     justify-content: center;
     align-items: center;  
      background-color: #eeeef7;
}
.services-section .services-header{
     width:100%;
    height:10vh;
    display: flex;
    justify-content:flex-start;
    align-items: center;  
}
.services-section .services-header h3{
      font-size: 35px;    
     margin-left: 100px;
}
.services-section .services{
     width: 90%;
    height: 40vh;  
    display: flex;
    justify-content: space-evenly;
    align-items: center;       
}
@media screen and (max-width:1100px) {
    .services-section{
        height:120vh;
        justify-content: flex-start;
    }
    .services-section .services{
        display:block;
    }
}
.services-section .services .service{
    width:350px;
    height:200px;
    background-color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px 20px;
    border-radius: 20px;
      box-shadow:3px 3px 3px #7a779b;
}
@media screen and (max-width:1100px) {
  .services-section .services .service{
      width:100%;
      margin-bottom:50px;
  }
}
.services-section .services .service img{
    padding: 20px;
    background-color: #6b63ff33;
    border-radius: 50%;
    margin-right:15px;
      box-shadow:3px 3px 3px #7a779b;
}
.services-section .services .service p{
    text-align:left;
}

.section-cta{
    width:90%;
    height:80vh;
    margin: 150px auto 0 auto;
    /* background-color: #3E437C;  */
     background-image: url('~@/assets/images/doc.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;   
    background-size: cover;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    
}
.section-cta .cta-text{
    width:90%;
    height:60%;
    backdrop-filter: blur(5px);
     display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    background-color: #d5d5e95b;
    padding: 20px;
      box-shadow:3px 3px 3px #7a779b;
      border-radius: 20px;
}
@media screen and (max-width: 900px) {
    .section-cta .cta-text{
        width:100%;
    }
    .section-cta .cta-text button{
        width:100%;
    }
}
.section-cta .cta-text h3{
    font-size: 35px;
    color: #1D2366;
    margin-bottom:20px;
}
.section-cta .cta-text p{
    font-size: 20px;
    color: #1D2366;
    text-align: left;
}
.section-cta .cta-text button{
    font-size: 20px;
    color: #fff;
    width:70%;
    padding:15px 20px; 
    margin-top: 30px;
    border-radius: 10px;
    font-weight: bold;
    border: none;
    background-color: #6C63FF;
}
.footer-section{
     width: 90%;
     height: 50vh;
     margin: 150px auto 0 auto; 
     display: flex;
     flex-direction: column;
     justify-content: center;
     align-items: center;  
     background-color: #eeeef7;
}


.footer-section .footer{
     width: 90%;
    height: 40vh;  
    display: flex;
    justify-content: space-evenly;
    align-items: center;   
}
@media  screen and (max-width:1100px){
      .footer-section {
        height:140vh;
    }   
}
@media screen and (max-width:1100px) {
    .footer-section .footer{
        flex-direction:column;
        justify-content: center;
        align-items: center;
        height:140vh;
    }
}
.footer-section .footer .item{
    width:30%;
    height:100%;
    background-color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;  
    border-radius: 20px;
    padding: 20px 30px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content:center;
}
@media screen and (max-width:1100px) {  
    .footer-section .footer .item{
       width:100%;
       margin-bottom:30px;
    }
}
.footer-section .footer .item div{
    margin: 5px;
    letter-spacing: 1.5px;
    line-height: 25px;
    color:#3E437C;
    text-align: left;
}
.bottom-text{
    padding:20px;
    font-size:20px;
    color:#fff;
    background-color: #6C63FF;
}
</style>