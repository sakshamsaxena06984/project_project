# project_project
--------------------------------------------------------------------HTML--------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FOOD SIDE</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" media="screen and (max-width: 1170px)" href="css/phone1.css">
</head>

<body>
    <nav id="navbar">
        <div id="logo">
            <img src="food_logo.jpg" alt="saksham@gmail.com">
        </div>

        <ul>
            <li class="item"><a href="#">HOME</a></li>
            <li class="item"><a href="#">SERVICES</a></li>
            <li class="item"><a href="#">ABOUT US</a></li>
            <li class="item"><a href="#">CONTACT US</a></li>

        </ul>


    </nav>
    <section id="home">
        <h1 class="h-primary">welcome to my online foodmile's</h1>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repellendus vel omnis dicta laboriosam amet nostrum
            officia ratione! Perferendis dicta provident quidem maiores atque porro, autem error quis repellat inventore
            tempore.</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repellendus vel omnis dicta laboriosam amet nostrum
            officia ratione! Perferendis dicta provident quidem maiores atque porro, autem error quis repellat inventore
            tempore.</p>
        <button class="btn">order now</button>
         <div id="saksham">
             <!-- <p>our servicese</p> -->
         </div>

    </section>
    <!-- <section id="services">
        <h1 class="primary_center">our services</h1>
        <div id="services">

        </div>
    </section> -->
    <div class="myaddtion" id="abcd">
        <h1 class="myclass center">OUR SERVICES</h1>
    </div>
    <section class="service_container">
        <!-- <h class="h-primary center">our services</h> -->
        <!-- <h1 id="abcd" class="h-primary center">OUR SERVICES</h1> -->
        <div id="service">
        <div class="box">
            <img src="pizza_here.jpg" alt="error_saksham">
            <h1 class="h-secondry center">food ordering</h1>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aspernatur, consequuntur quos reprehenderit
                deleniti aut molestiae, aliquid sint eaque, vel id nulla! Nesciunt, beatae maiores. Natus corrupti
                numquam temporibus possimus officiis?</p>
        </div>
        <div class="box">
            <img src="veg_logo.jpg" alt="error_saksham">
            <h1 class="h-secondry center">veg_food</h1>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aspernatur, consequuntur quos reprehenderit
                deleniti aut molestiae, aliquid sint eaque, vel id nulla! Nesciunt, beatae maiores. Natus corrupti
                numquam temporibus possimus officiis?</p>
        </div>
        <div class="box">
            <img src="non_veg_logo.jpg" alt="error_saksham">
            <h1 class="h-secondry center">non_veg</h1>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aspernatur, consequuntur quos reprehenderit
                deleniti aut molestiae, aliquid sint eaque, vel id nulla! Nesciunt, beatae maiores. Natus corrupti
                numquam temporibus possimus officiis?</p>
        </div>
    </div>
    </section>
    <h1 class="h-primary center">out client's</h1>
    <section id="our-client">
        
        <div id="cleints">
            <div class="client-item">
                <img src="contact.png" alt="oour contact">
            </div>
        </div>
        <div id="cleints">
            <div class="client-item">
                <img src="contact.png" alt="oour contact">
            </div>
        </div>
        <div id="cleints">
            <div class="client-item">
                <img src="contact.png" alt="oour contact">
            </div>
        </div>
    </section>
    <section id="contact">
        <hr>
        <!-- <h1 class="h-primary">contant_us</h1> -->
        <h1 class="h-primary center">CONTACT_US</h1>
        <div id="contact-box">
            <form action="">
                <div class="form-group">
                    <label for="name">NAME</label>
                    <input type="text" name="name" id="name" placeholder="ENTER YOUR NAME">
                </div>
                <div class="form-group">
                    <label for="phone">YOUR NUMBER</label>
                    <input type="text" name="number" id="name" placeholder="ENTER YOUR NUMBER">
                </div>
                <div class="form-group">
                    <label for="gmail">YOUR G-MAIL</label>
                    <input type="text" name="gmail" id="name" placeholder="ENTER YOUR G-MAIL">
                </div>
                <div class="form-group">
                    <label for="message">TEXT-BOX</label>
                    <textarea name="message" id="message" cols="30" rows="10"></textarea>
                </div>
            </form>
        </div>
    </section>
    <footer>
        <div class="center">
            copyright &copy; www.saksham@saxena123gmail.com
        </div>
    </footer>
</body>
</html>

--------------------------------------------------------------------HTML--------------------------------------------------------------------

--------------------------------------------------------------------CSS---------------------------------------------------------------------

*{
    margin: 0;
    padding: 0;
    /* background-color: turquoise; */
     /* z-index: -50;  */
    opacity: 0.2px;
}
/* css variable */
:root{
    --navbar-height:59px;
}
/* navigation bar */
#navbar{
    display: flex;
    align-items: center;
    position: relative;
    top: 0;
}
/* navigation: logo and image */
#logo{
   margin: 5px 26px;
}
#logo img{
    height: 99px;
    margin: -23px -9px;
}

#navbar ul{
    display: flex;
    /* border: 8px solid rgb(194, 188, 188); */
    border-radius: 232px;
        
}
#navbar ul li{
      list-style: none;
      font-size: 1.3rem;
}
#navbar ul li a{
    position: relative;
     display: block; 
    color: white;
    font-size: 15px;
    padding: -2px;
    margin: 40px;
    /* background-color: 2px solid rebeccapurple; */
}
#navbar ul li a:hover{
    color: rgb(57, 52, 61);
    background-color: rgb(131, 127, 127);
    
}
#navbar::before{
    content:" ";
    position: absolute;
    background-color: black;
    height: 100%;
    width: 100%;
    top: 0;
    left: 0;
    z-index: -1;
    opacity: 2;
}

/* home secetion */
#home{
    display: flex;
    flex-direction: column;
    padding: 40px 200px;
    height: 450px;
    /* width: 100%; */
    justify-content: center;
    align-items: center;
}
#home::before{
    content:" ";
    position: absolute;
    height: 100vh;
    width: 100%;
    /* top: 0;
    left: 0; */
      background: url('../new_food_logo.jpg') no-repeat center center/cover;
    
    z-index: -1;
    opacity: 0.9;
}
/* UTility class */
#home h1{
    font-size: 2.4rem;
    /* font-family: 'Open Sans', sans-serif; */
    /* font-family: 'Open Sans', sans-serif; */
    font-family: 'Raleway', sans-serif;
    color: black;
    text-align: center;
    justify-content: center;
}
#home p{
    font-family: 'Open Sans', sans-serif;
    color: white;
    font-size: 10px;
}
.h-primary{
    /* font-family: 'Raleway', sans-serif; */
    font-family: 'Open Sans', sans-serif;
    font-size: 3.4rem;
}
.btn{
    padding: 0px 56px;
    margin: 4px 1px;
    border: 2px solid rgb(184, 181, 181);
    background-color: rgb(199, 193, 191);
    border-radius: 6px;
    font-size: 14px;
    opacity: 0.9;
    cursor: pointer;
}
.btn:hover{
    background-color: rgb(51, 40, 42);
    opacity: 4;
}
/* UTILITY_CLASS */
.center{
    text-align: center;
}
/* OUR_SERVICE MAINTAIN HERE */
#saksham p{
    color: black;
    font-size: 60px;
    padding: 2px 12px;
    margin: 22px  12px;
}
/*SERVICE ID HERE-*/
#service{
    margin: 34px;
    display: flex;
    /* height: 250px; */
    

}
#service .box{
 border: 4px solid rgb(68, 68, 67);
 
 margin: 95px 11px;
 padding: 16px 10px; 
 border-radius: 25px;
 text-align: center;
 background-color: rgb(201, 198, 193);

}
#service .box img{
    height: 158px;
    display: block;
    margin: auto;

}
/* client part here */

 #our-client section{
    /* display: flex; */
    /* height: 1334px; */
}

#our-client{
     display: flex; 
      
     flex-direction: row;
    justify-content: center;
    align-items: center;
    height: 333px; 
}
#our-client::before{
    content: " ";
    position: absolute;
    background: url('../vegitable.jpg') no-repeat center center/cover;
    height: 326px;
    width: 100%;
   z-index: -1;
   opacity: 0.4;
}  
#our-client img{
     height: 124px;
    /* margin: 145px -36px; */
}
.client-item{
    padding: 34px 43px;
}
/* CONATCT_FORM */
#contact{
    position: relative;

}
#contact::before{
    content: " ";
    position: absolute;
    width: 100%;
    height: 400px;
    z-index: -1;
    opacity: 0.9;
    padding: 10px 10px;
    margin: 10px 10px;
    background: url(../paneer.jpg) no-repeat center center/cover;
}
#contact-box{
    display: flex;
    justify-content: center;
    align-items: center;
    padding-bottom: 34px;
}
#contact-box img{
    opacity: 0.4;
}
#contact-box input, 
#contact-box textarea{
    width: 100%;
    /* padding:10px 10px;
    margin: 10px 10xp; */
    border-radius: 16px;
    background-color: wheat;


}
#contact-box input, 
#contact-box textarea:hover{
    background-color: white;
    border-radius: 10px;

}
#contact-box form{
    width: 40%;
    padding: 10px 10xp;
    margin: -6px 29px;
    /* background-color: blanchedalmond; */

    
}
#contact-box label{
    font-size: 01.3rem;
    color: white;
}
/* //WARKING ON FOOTER */
footer{
    padding: 10px 50px;
    background-color: rgb(163, 157, 157);
    color: white;
    z-index: -1;
}
#contact h1{
    color: white;
}
/* .service_container >h1{
    margin: 10px 10px;
    padding: 100px 10px;
    color: violet;

} */
#abcd{
    height: 30px;
    width: 100%;
    padding: 10px 20px;
    margin: 127px -0px;
    /* border: 10px solid red; */
    font-size: 20px;
    border-radius: 25px;
    background-color: rgb(135, 141, 141);
    color: white;
}

--------------------------------------------------------------------------------CSS------------------------------------------------------------------------
