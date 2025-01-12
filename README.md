# John-Doe-
html {
  scroll-behavior: smooth;
}

* {
  margin: 0;
  padding: 0;
}
.hero-section{
    margin-top: 46px !important;
    background-image: url("https://spaces.w3schools.com/images/L1jYYtjgIic.jpg");
    background-repeat: no-repeat;
    box-sizing: border-box;
}
.hero-section-main{
    background-color: rgba(22, 22, 22, 0.7);
    display: flex;
    justify-content: center;    
}
.hero-section-into-text{
    padding: 40px ;
    width: 90%;;
    margin-bottom: 30px;
    border:2px solid white !important;
    border-radius:30px !important;    
}
.hero-section-into-text h1{
    font-size: 60px !important;
    letter-spacing: 2px;
    font-weight: 800;
    font-family: sans-serif;    
}
.hero-section-into-text p{
    width: 40%;
    letter-spacing: 1px;
}
.section-text-header{
    margin: 80px 0px!important;
    border-left:6px solid black;
    padding-left:50px !important;   
    text-transform: uppercase;
    font-weight: 600;    
}
.product-left-side{
    width:600px;
    height: 700px;
    margin-right: 20px;
}
.product-left-side img{
    height: 100%;
    width: 100%;
    object-fit: cover
}
.product-right-side{
    width:400px;
    display: grid;
    grid-template-rows: 1fr 1fr;
    grid-row-gap: 10px;    
}
.icons{
    font-size: 16px; 
    padding: 3px;
}
.product-right-side-1{    
    width:400px;
    height:340px;
}
.product-right-side-1 img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    overflow:hidden;
}
.product-right-side-2{
    height:337px;
    width:400px;
    margin-top: 8px;
    overflow:hidden ;
}
.product-right-side-2 img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    overflow:hidden ;
}
.contact{
    padding: 40px 0px;
    width:60%;
    margin: auto;
    display: flex;
    justify-content: space-evenly;
    flex-wrap: wrap;    
}
.products{
    width: 90%;
    margin: auto;
    overflow-x: hidden;
}
.product-list{
    width:80% !important;
    margin:auto;
    overflow:hidden ;   
}
.new-arrived-products{
    display: flex !important;
    flex-wrap: wrap;
    justify-content: center;
    gap:30px;
    grid-row-gap: 60px;
    width:80%;
    margin: auto;
    overflow:hidden ;
}
.new-product {
    height: 445px;
    color:gray;
}
.price{
    color:black;
    font-weight: 600;
    margin-top: 8px;
}
.new-arrived-image{
    width:300px !important;
    height:300px !important;
    overflow:hidden ;
}
.new-arrived-image img{
    width:100% !important;
    height: 100% !important;
    object-fit: cover;
}
.feedback{
   width:70%;
   margin: auto;
}
.name{
    font-weight: 600;
    font-size: 14px;
}
.card{
    width:380px;
    padding: 20px;
    border-radius: 10px;
    margin: 15px;
    background-color: white;
    height: 150px;
    box-shadow: 2px 7px 20px -5px rgba(0,0,0,0.57);
    -webkit-box-shadow: 2px 7px 20px -5px rgba(0,0,0,0.57);
    -moz-box-shadow: 2px 7px 20px -5px rgba(0,0,0,0.57);
}
.customer-profile{
    width:50px;
    height: 50px;
    margin-right: 10px;
}
.customer-feedback-header{
    display:flex;
    align-items: center;
    margin-bottom: 20px;
}
.customer-profile img{
    width:100% !important;
    height: 100% !important;
    object-fit: cover;
    border-radius: 50%;
}

/*medium screens - Laptops*/

@media screen and (max-width: 1024px) {
    .hero-section{
        background-image: url("https://spaces.w3schools.com/images/L1jYYtjgIic_1050_500.jpg");
        background-repeat: no-repeat;
    }
    .products{
        width: 90% !important;
    }
    .feedback{
        width:90%;
        margin: auto;    
    }
    .contact{
        width:90% !important;            
    }
}

@media screen and (min-width: 1200px) {
    .new-arrived-products{
        width:80% !important;
    }
    .feedback{
        width:70%;
        margin: auto;    
    }
    .products{
        width: 70%;
        margin: auto;
    }
    .product-list{
       display: flex;
       justify-content: space-between;
    }
    .hero-section-main{
        display: flex;
        justify-content: center;
        height: 600px;
    }
   .hero-section{
    background-image: url("https://spaces.w3schools.com/images/L1jYYtjgIic.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    margin: auto;
    height: 600px;
    }
    .contact{
        width:70%;
    }
    .hero-qoute{
        font-size: 17px !important;
        
    }
    
}

/*Small screens - tablets*/
@media screen and (min-width:481px) and (max-width: 768px) {
    .feedback{
        width:90%;
        margin: auto    
    }
    .Customer-feedback{
        justify-content: center !important;
    }
    .products{
        width: 90% !important;
        margin: auto !important;
    }
    .new-arrived-image{
        width:250px !important;
        height:300px !important;
    }
    .new-arrived-image img{
        width:100%!important;
        height: 100% !important;
        object-fit: cover;
    }
    
    .hero-section{
        margin-top: 50px;
        background-image: url("https://spaces.w3schools.com/images/L1jYYtjgIic_780_500.jpg");
        background-repeat: no-repeat;
    }
    .hero-section-main{
        background-color: rgba(22, 22, 22, 0.7);
        display: flex;
        justify-content: center;
        height: 400px;
    }
    .hero-section-into-text h1{
        font-size: 25px !important;
        letter-spacing: 2px;
        font-weight: 800;
        font-family: sans-serif;
    }
    .hero-section-into-text p{
        width: 100%;
        letter-spacing: 1px;
        font-size: 11px ;
        margin-top: 30px;
    }
   .products{
       width: 80% !important;
       margin: auto;
   }
    .product-left-side{
        width:500px !important;
        height: 540px;
        margin: auto !important;
    }
    .product-left-side img{
        height: 100%;
        width: 100%;
        object-fit: cover;
    }
    .product-right-side{
        width:500px ;
         display: grid;
         grid-template-rows: 1fr 1fr;
         grid-row-gap: 10px;
    }
    .product-right-side-1{
    width:500px !important;
    height:540px !important;
    margin: 30px auto
    }
    .product-right-side-1 img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        overflow:hidden;
    }
    .product-right-side-2{
        height:540px !important;
        width:500px !important;
    }
    .product-right-side-2 img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        overflow:hidden ;
    }
    .contact{
        margin-top: 50px !important;
        width:85% !important;
        justify-content: space-between;
    }

    .contact-head{
    font-size:20px;
    }
    .contact h4{
    font-size:15px ;
    }
    .contact p{
    font-size: 10px; 
    }
    .contact h2{
    font-size: 16px;
    }

}


/*Extra small screens - phones*/
@media screen and (max-width: 480px) {
    .hero-section-main{
        background-color: rgba(22, 22, 22, 0.7);
        display: flex;
        justify-content: center;
        height: 400px;
    }
    .hero-section{
        margin-top: 50px;
        background-image: url("https://spaces.w3schools.com/images/L1jYYtjgIic_480_400.jpg") !important;
        background-repeat: no-repeat;
        overflow-x: hidden;
        overflow-y: scroll;    
    }
    .hero-section-into-text h1{
        font-size: 25px !important;
        letter-spacing: 2px;
        font-weight: 800;
        font-family: sans-serif;
    }
    .hero-section-into-text p{
        width: 100%;
        letter-spacing: 1px;
        font-size: 11px ;
        margin-top: 30px;
    }
    .products{
        width:90%;
        overflow-x: hidden;
    }
    .section{
        height: 2000px !important;
    }
    .product-list{
        display: flex !important;
        flex-direction: column;
    }
    .product-left-side{
        width:300px !important; 
        height: 350px !important;
        margin-top: 40px;
        overflow:hidden ;
    }
    .product-left-side img{
        width: 100% !important;
        height: 100% !important;
        object-fit: cover;
    }
    .product-right-side{
        display: flex;
        flex-direction: column;
    }
    .product-right-side-1{
        width:300px !important;
        height:350px !important;
        margin-top: 40px !important;
    }
    .product-right-side-1 img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        overflow:hidden;
    }
    .product-right-side-2{
        height:350px !important;
        width:300px !important;
        margin-top: 40px !important; 
    }
    .product-right-side-2 img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        overflow:hidden ;
    }
    .section-text-header{
        width: 300px !important;
        margin: 40px 0px!important;
        border-left:6px solid white;
        font-size: 20px !important;
        padding-left:30px !important;   
        text-transform: uppercase;
        font-weight: 600;    
    }

    .new-product{
        border-bottom:1px solid gray;
        padding-bottom: 50px;
        height: 420px;    
    }
    .new-arrived-image{
        width:230px !important;
        height:240px !important;
    }
    .new-arrived-image img{
        width:100% !important;
        height: 100% !important;
        object-fit: cover;
    }
    .feedback{
        width:90%;
        margin: auto;
    }
    .Customer-feedback{
        justify-content: center !important;
    }
    .contact-info{
        width:300px;
        border:1px solid whitesmoke;
        padding: 30px 15px;
        border-radius: 10px;
    }
    .contact{
        width:80%;
                
    }
    .contact-head{
        font-size:20px;
    }
    .contact h4{
        font-size:15px ;
    }
    .contact p{
        font-size: 10px;
    }
    .contact h2{
        font-size: 16px;
    }

}
