<!DOCTYPE html>
<html>
<head>
  <!---aos link-->
  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
    <title>A M Engineering</title>
    <!--boostrap link-->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <!--icon CDN-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="styl.css">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <style>
        *{padding: 0%;margin: 0%;}
        #btncon:hover{transform: scale(1.5); transition:  transform 1s; }
#homee:hover{background-color: blue; width: 90px; color: white; border-radius: 9%;}


#h4slid {
  width: 640px;
  height: 150px;
  animation-name: example;
  animation-duration: 9s;
}

@keyframes example {
  0%   {font-size: 70px;}
  25%  {background-color: skyblue;font-size: 50px; }
  50%  {background-color: blue;}
  100% {color: white;}
}

    </style>
</head>
<body>
    <!--main frist line-->
    <div class="container-fluid bg-dark bg-gradient text-light">
        <div class="row ">

            <div class="col-3 col-sm-3 col-md-4 col-lg-4">

                <i class="fa fa-phone" aria-hidden="true"></i>Tel:+92303-5700527 /        03484855458     </div>

            <div class="col-4 col-sm-4 col-md-6 col-lg-5"> 

                <marquee scrollamount="10" height="" direction="left" behavior="invars  "  loop="12" onmouseover="stop()" onmouseout="start()"><h6><i class="fa fa-envelope-o" aria-hidden="true"></i> mobeenaslam7772@gmail.com </h6></marquee>
            </div>

            <div class="col-3 col-sm-3 col-md-2 col-lg-3">

                <a href="https://www.youtube.com/"  >
                <i  class="fa fa-youtube-play" aria-hidden="" style="font-size: 30px; color: rgb(252, 2, 2);" ></i>
            </a>
                
                <a href="https://www.youtube.com/"class="ms-lg-5 me-lg-5" >
                    <i  class="fa fa-instagram" aria-hidden="true" style="font-size: 30px;" ></i>
                </a>
                <a href="https://www.youtube.com/">
                    <i class="fa fa-facebook-square" aria-hidden="true" style="font-size: 30px; font-size: 30px; color: blue;"></i>
                </a>

            </div>
        </div>
    </div>
    <!--NavBar-->
    
 <div style="position:sticky; top: 0px; z-index: 5;">
    <nav class="navbar navbar-expand-lg navbar-light  bg-light " style="width: auto;">
      <div class="container-fluid" >
        <div class="view onmouseover">
        <a class="navbar-brand" href="#"><img src="images/Untitled-2.png" alt="" style="width: 100px; height: 50px;"></a>
        <button style="font-size: 50px;" class="navbar-toggler " type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">A M Engineering
          <span class="navbar-toggler"><mark> your dream <sup style="color: red;">is our vision</sup></mark></span>
          <a href="https://wa.me/message/QWRSB6ABNWC7G1"><i class="fa fa-whatsapp" aria-hidden="true" style="border-radius: 40%; color: white; background-color: green; font-size: 40px;"></i></a>
           



          





          
          

        </button>




        
        <button class="btn btn-primary" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight">Menu 
          <i class="fa fa-bars" aria-hidden="true"></i>
        </button>

        <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasRight" aria-labelledby="offcanvasRightLabel" style="width: 150px;">
          <div class="offcanvas-header">
            <h5 id="offcanvasRightLabel">         
              <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                   <a  id="homee" class="nav-link active" aria-current="page" href="#carouselExampleInterval">HOME</a>
                   
                   <a  id="homee" class="nav-link active" aria-current="page" href="#products">Products</a>
                   <a  id="homee" class="nav-link active" aria-current="page" href="#services">Services</a>
                   <a  id="homee" class="nav-link active" aria-current="page" href="#aboutus">About</a>
                   <a href="#contact us">
                    <button id="btncon" type="button" class="btn btn-primary">CONTACT</button> 
                  </h5>
           
          </div>
          
        </div>
        
                  
        

        
      </div>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-5 mb-2 mb-lg-0 ">
            <h1 style="color: black;">A M Engineering</h1>
          <b style="color: red;">your dream is our vision</b>
            <li class="nav-item">
              <a  id="homee" class="nav-link active" aria-current="page" href="#carouselExampleInterval" style="margin-left: 50px;">HOME</a>
            </li>
            <li class="nav-item">
              <a  id="homee" class="nav-link active" aria-current="page" href="#products">Products</a>
             
            </li>
            <li class="nav-item ">
              <a  id="homee" class="nav-link active" aria-current="page" href="#services">Services</a>
            </li>
            <li class="nav-item ">
              <a  id="homee" class="nav-link active" aria-current="page" href="#aboutus">About US</a>
              
            </li>
            <a href="#contact us">
            <button id="btncon" type="button" class="btn btn-primary" style="margin-left: 50px;">CONTACT US</button> 
          </a>

          

        </div>
      </div>
    </nav>
  </div>
  

    <!--Slider-->

    <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active" data-bs-interval="10000">
          <img src="images/panels/123338908_118596610051499_6802764730911976258_n.jpg" class="d-block w-100" alt="..." style="height: 600px; ">
          <h4 id="h4slid" style="position: absolute; top: 90px; left: 400px; font-size: 60px; color: black; font-weight: bolder;"data-aos="fade-up">Simple Solution for <br>Complex Applications</h4>
          
        </div>
        <div class="carousel-item" data-bs-interval="2000">
          <img src="images/impianti_distribuzione-1024x683.jpg" class="d-block w-100" alt="..." style="height: 600px;">
        </div>
        <div class="carousel-item">
          <img src="images/15.jpglt.jpg" class="d-block w-100" alt="..." style="height: 600px;">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
<br> <br>


<!--products-->
<div id="products" style="height: 1400px;">
    <div class="container">
      <div class="row">
        <h2 style="font-style: italic; font-weight: bolder; color: red ; border-bottom: 1px solid black   ">Popular Categories</h2>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class=" col-lg-3 col-md-4  col-sm-4">
          <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" target="blank">
            <img src="images/product img/PushButtons.jpg" alt="" style="height: 200px;"> <br> 
             <strong style=" font-size: 30px;">PushButtons</strong>
          </a>
        </div>
        <div class="col-lg-3 col-md-4  col-sm-4">
          <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html"target="_blank">
            <img src="images/product img/schneider-ic60-miniature-circuit-breaker-4-pole-40a-550x550.JPG.webp" alt="" style="height: 200px;"> <br> 
             <strong style=" font-size: 30px;">circuit Breakers</strong>
          </a>
        </div>
        <div class="col-lg-3 col-md-4  col-sm-4">
          <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html"target="_blank">
            <img src="images/product img/contactor.jpg" alt="" style="height: 200px;"> <br> 
             <strong style=" font-size: 30px;">Contactors</strong>
          </a>
        </div>
        <div class=" col-lg-3 col-md-4 col-sm-4">
          <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html"target="_blank">
            <img src="images/product img/105853SE_288x288.PNG" alt="" style="height: 200px;"> <br> 
             <strong style=" font-size: 30px;">Phase Sequence</strong>
          </a>
        </div>


        <div class="col-lg-3 col-md-4  col-sm-4">
          <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" target="_blank">
            <img src="images/product img/ms-panel-box-250x250.jpg" alt="" style="height: 200px;"> <br> 
             <strong style=" font-size: 30px;">MS/SS panel box</strong>
          </a>
        </div>
        <div class=" col-lg-3 col-md-4 col-sm-4">
          <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" target="_blank">
            <img src="images/product img/Samwha-Dsp-EOCR-SSD-Digital-Electronic-Overload-Relay-Motor-Protector-Thermal-Overload-Relay.webp" alt="" style="height: 200px;"> <br> 
             <strong style=" font-size: 30px;">EOCR-Relays</strong>
          </a>
        </div>


        <div class=" col-lg-3 col-md-4  col-sm-4">
          <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" target="blank">
            <img src="images/product img/omron-timer-500x500.jpg" alt="" style="height: 200px;"> <br> 
             <strong style=" font-size: 30px;"> Timer Relays</strong>
          </a>
        </div>
        <div class="col-lg-3 col-md-4  col-sm-4">
          <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" target="_blank">
            <img src="images/product img/hangyoung-ax-temperature-controller.jpg" alt="" style="height: 200px;"> <br> 
             <strong style=" font-size: 30px;">Temperature Controllers</strong>
          </a>
        </div>
        <div class="col-lg-3 col-md-4  col-sm-4">
          <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" target="_blank">
            <img src="images/product img/invrtr.jpg" alt="" style="height: 200px;"> <br> 
             <strong style=" font-size: 30px;">inverter</strong>
          </a>
        </div>

        <div class="col-lg-4   col-md-6  col-sm-6">
          <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" target="_blank">
            <img src="images/product img/relays.jpg" alt="" style="height: 200px;"> <br> 
             <strong style=" font-size: 30px;">RELAYS & ACCES</strong>
          </a>
        </div>
        
        <div class="col-lg-4 col-md-6  col-sm-6">
          <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" target="_blank">
            <img src="images/product img/omron-proximity-sensor-500x500.jpg" alt="" style="height: 200px;"> <br> 
             <strong style=" font-size: 30px;">Proximity-Sensor</strong>
          </a>
        </div>

        <div class="col-lg-3 col-md-4  col-sm-4">
          <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" target="_blank">
            <img src="images/product img/duct.jpg" alt="" style="height: 200px;"> <br> 
             <strong style=" font-size: 30px;">Cable Trunks systems</strong>
          </a>
        </div>



      
       
      





      
    </div>

  </div>
  </div>


    <br><br> <br><br><br>
    <!--services-->
    <div id="services">
      <h1 style="border: 1px solid rgb(10, 9, 7); background-color: whitesmoke; text-align: center; font-weight:bolder" data-aos="flip-down"> OUR Services</h1> </div>
      <br><br>
      <div class="container">
        <div class="row">



          
          <div class="col-lg-4 col-md-6 col-sm-6" data-aos="fade-right">

            <div class="card" style="width: 18rem; height: 460px;">
              <img src="images/card img/Auto-Transfer-Switch-and-Auto-Failure-1024x683.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">
      
                  <h4>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Auto Transfer Switch <br> and Auto Failure
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">A.M. motorized ATS is our specialized <br> product. It has both automatic and <br> manual that increases the reliability<br> We offer manual override option<br> by just utilizing 2 Nos. circuit breakers<br>The range of ATS that we offer <br> varies from 100Amps to 1600Amps. <br> Our Automatic Transfer have reliable <br> mechanical interlock high arc <br> quenching and high <br> thigh transfer speed</a></li>
                     
                    </ul>
                  </li>
                </h4>

                <br><br><br>
                </h5>
                <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" class="btn btn-primary" target="blank">More Information</a>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-sm-6" data-aos="fade-up">

            <div class="card" style="width: 18rem;">
              <img src="images/card img/dsss.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                     <b> Power Factor <br> Improvement Plant</b>
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">
                        We offer power factor <br> improvement correction panels for <br> indoor  applications with fixed or <br>automatic capacitor switching.<br>  These Panels reduces power <br>losses  and limit the unwanted <br>current to improve the life and <br>efficiency of  the system and  <br>save the cost of electricity</a></li>
                     
                    </ul>
                  </li>
                </h5>
                
                <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" class="btn btn-primary">More Information</a>
              </div>
            </div>
          </div>


          <div class="col-lg-4 col-md-6 col-sm-6" data-aos="fade-left">

            <div class="card" style="width: 18rem;">
              <img src="images/card img/Low-Voltage-Drawer-Switchgear.png" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                     <b> LV Panel with or <br> without Synchronizing</b>
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">
                        Our Low voltage switchgear <br> is a metal clad, totally enclosed<br> cubicle type with lockable hinged <br>doors, front access, and floor <br>mounting in free standing designs <br>for indoor/outdoor services.The<br> switch boards consist of vertical <br>sections bolted together to form <br>a rigid assembly, finished with<br> powder coating. The switch board <br>consist of four poles air insulated<br> electro tinned, <br>high conductivity copper bus<br> bar designed for 3-Phase,<br> 4 Wire 50HzAC system.<br>Our switchgear <br> includes circuit breaker, <br>(ACB,s, MCB, MCCB, ELCB,s,<br> RCCB & RCBO)<br> Current Transformer potential.<br>Transformers, protective relays, <br>measuring instruments, switches,<br> fuses, surge arrestors, isolators,<br> and various associated <br>types of equipment
                      </a></li>
                     
                    </ul>
                  </li>
                </h5>
                
                <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" class="btn btn-primary">More Information</a>
              </div>
            </div>
          </div>




          <div class="col-lg-4 col-md-6 col-sm-6" data-aos="fade-right">
            <div class="card" style="width: 18rem;">
              <img src="images/card img/power-distribution-electrical-control-panel-500x500.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Distribution-in-Industries</h5>
                
                <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" class="btn btn-primary">More Information</a>
              </div>
            </div>

          </div>
          <div class="col-lg-4 col-md-6 col-sm-6"data-aos="fade-up">

            <div class="card" style="width: 18rem;">
              <img src="images/card img/lt-distribution-panel-500x500.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Low Tension panel</h5>
                <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" class="btn btn-primary">More Information</a>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-sm-6"data-aos="fade-left">

            <div class="card" style="width: 18rem;">
              <img src="images/card img/lt-distribution-panel-500x500 (1).jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">High Tension panel</h5>
                
                <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" class="btn btn-primary">More Information</a>
              </div>
            </div>
          </div>
        
      




      
        
          <div class="col-lg-4 col-md-6 col-sm-6"data-aos="fade-right">
            <div class="card" style="width: 18rem;">
              <img src="images/card img/WhatsApp Image 2022-01-22 at 10.43.49 PM.jpeg" class="card-img-top" alt="..." style="height: 300px;">
              <div class="card-body">
                <h5 class="card-title">  sliding gate opener</h5> <br>
                
                <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" class="btn btn-primary">More Information</a>
              </div>
            </div>

          </div>
          <div class="col-lg-4 col-md-6 col-sm-6"data-aos="fade-up">

            <div class="card" style="width: 18rem;">
              <img src="images/card img/WhatsApp Image 2022-01-22 at 10.08.30 PM.jpeg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title" style="font-weight: bolder;"> Automatic gate opening </h5>
                <p>Convenience AT your fingertips </p>
              
                <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" class="btn btn-primary">More Information</a>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-sm-6" data-aos="fade-left">

            <div class="card" style="width: 18rem;">
              <img src="images/card img/openin gate.jpeg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Swing Gate Opener</h5> <br>   
                
                <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" class="btn btn-primary">More Information</a>
              </div>
            </div>
          </div>

          
        
      
 



      
        
          <div class="col-lg-4 col-md-6 col-sm-6"data-aos="fade-right">
            <div class="card" style="width: 18rem;">
              <img src="images/card img/assasri img.jpeg" class="card-img-top" alt="..." style="height: 300px;">
              <div class="card-body">
                <b class="card-title">
                  <h5>
                   <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    Dual Swing Gate Opener 
                  </a>
                  <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <li><a class="dropdown-item" href="#">Heavy Duty Automatic Gate Opener <br> Up to 660lbs & 18ft Long Gate <br> AC Powered 50W Automatic <br> Gate Openers with Remote <br> Complete Kit Push/Pull-to<br>Open  Dual Gate Opener</a></li>
                   
                  </ul>
                </li>     </h5>
               </b> <br>


                
                
                <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" class="btn btn-primary">More Information</a>
              </div>
            </div>

          </div>
          <div class="col-lg-4 col-md-6 col-sm-6"data-aos="fade-up">

            <div class="card" style="width: 18rem;">
              <img src="images/card img/s-l1600.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title" style="font-weight: bolder;"> Automatic gate opening </h5>
                <h4 style="text-align: center; color: red;">Convenience <br> At your fingertips </h4> <br>
              
                <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" class="btn btn-primary">More Information</a>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-sm-6"data-aos="fade-left">

            <div class="card" style="width: 18rem;">
              <img src="images/card img/slideng.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      1800kg Automatic Sliding <br> Gate Opener 
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">Heavy Duty  Gate Opener <br> Up to 1800KG/2500KG Gate <br> AC Powered 50W Automatic <br> Gate Openers with Remote <br> Complete Kit Push/Pull-to<br>Open  Dual Gate Opener</a></li>
                     
                    </ul>
                  </li>
                  </h5> <br>   
                
                <a href="file:///C:/Users/ECON/Desktop/Indus%20prtc/ameng%20Cunstraction.html" class="btn btn-primary">More Information</a>
              </div>
            </div>
          </div>
        





        </div>
      
   

    



   

    

      </div>
    


  </div>
    
<!--ABOUT US-->

<div style="margin: 90px;" id="aboutus">
<div class="container ">
  <div class="row ">
    <div class="col-lg-12 col-md-12 col-sm-12"  data-aos="zoom-in-right">
      <h2 style="border-bottom: 1px solid red; color: red; "><b>ABOUT US </b></h2></div>
    <div class="col-lg-12 col-md-12 col-sm-12 bg-primary text-light mt-4"data-aos="fade-up"
    data-aos-anchor-placement="top-bottom">
      <h5 style="padding: 25px;">We are a distribution company, which supplies parts for industrial automation. We store parts withdrawn by selected manufacturers to enable customers to optimize expenses associated with the repair of machinery and equipment. We supply among others industries: automotive, electrotechnical, tool, metallurgical, medical, mechanical and plastic processing</h5></div>
  </div>
</div>
<div class="container">
  <div class="row">
    <div class="col-lg-12 col-md-12 col-sm-12" data-aos="fade-down">
      <h6 style="text-align: center; color: blue; margin: 40px;">Our actions are aimed at breaking the old, rigid rules and the introduction of innovations in access to spare parts</h6>
    </div> </div>
</div>


<div class="container">
  <div class="row text-primary">
    <div class="col-sm-12 col-md-4 col-lg-4" data-aos="zoom-out-right">
     <p style="text-align: center ;"> We provide maintenance services <br> and parts of machines</p>
    </div>
    <div class="col-lg-4 col-md-4 col-sm-12"  data-aos="zoom-out">
      <p style="text-align: center;">We work with reputable  courier <br> companies</p>
    </div>
    <div class="col-lg-4 col-md-4 col-sm-12" data-aos="zoom-out-left">
      <p style="text-align: center;">We operate globally and open  to <br> the needs of customers</p>
    </div> 
  </div>
</div>

<div class="container">
  <div class="row">
    <div class="col-lg-12" data-aos="flip-up"> <p style="text-align: center; color: blue; padding: 40px; margin: 40px; background-color: whitesmoke;"> We do everything to help customers reduce the cost of doing production and eliminate the stress of deficiencies that may weigh on the implementation of the firm,s orders. Our aim is to accelerate service delivery and continuous improvement staff </p> </div>
  </div>
</div>
<div class="container">
  <div class="row">
    <div class="col-lg-12" data-aos="zoom-in">
      <p style="text-align: center; color: blue; margin: 30px;">We work hard and we believe that our efforts will result in satisfaction on the side of our customers. We know what you are doing, we know what the market needs to grow and strive to make it happen. Located in our warehouses spare parts are often the only solution for machines used by companies that report to us. In cases where we are not able to provide the selected products, we offer a service whereby the machine<br> after all, can recover efficiency.  <br>

       <b> AM Engineering is a professional company, whose activities pose a challenge for the competition. Our services quickly and efficiently – helping in situations that at first glance may seem impossible to solve. We are characterized by commitment and personalized customer contact </b></p>
    </div>
  </div>
</div>

</div>

  
  <!--contact uS-->
  <div id="contact us">
  <div class="container-fluid">
    <div class="row bg-primary">
      <div class="col-lg-12 text-light">
        <b style=" font-size: 100px;">Need help<i class="fa fa-question" aria-hidden="true"></i></b>  
        <button id="btncon" type="button" class="btn btn-info">  Feel free To CONTACT US</button>

        

      </div>
    </div>
  </div>

  <div class="container-fluid  text-light ">
    <div class="row bg-dark" style="height: 400px;">
      <div class="col-lg-6 col-md-6 col-sm-6">
        <h2 style="margin-top: 20px; border-bottom: 1px solid white; width: 170px;">Head office</h2> <br>
        <h5> <i class="fa fa-map-marker" aria-hidden="true" style="color: red; font-size: 40px;"></i> Plot#8 Sadiq Street <br> <h4 style="margin-left: 90px;"> Ferozepur Road Ichra lahore</h4></h5>
        <h1> <i class="fa fa-phone-square" aria-hidden="true" ></i>   Phone  </h1>
        <h4 style="margin-left: 40px;"> +923035700527 /03484855458</h4>
        <h2> <i class="fa fa-envelope-o" aria-hidden="true"> Gmail</i> </h2>
         <h5 style="margin-left: 90px;"> amengineering52@gmail.com </h5>
         <br>

         <div> <i class="fa fa-comments-o" aria-hidden="true"></i>
          <label for="">  <input type="text" placeholder="Entr your message" name="" id=""></label><button style="color: whitesmoke; background-color: black;">Send<i class="fa fa-paper-plane" aria-hidden="true"></i></button>
      </div>

      </div>


      

      <div class="col-lg-6 col-md-6 col-sm-6">
        <h3 style=" margin-top: 20PX; border-bottom: 1px solid white; width: 260px;"> OUR SOCIAL MEDIA </h3> <br>
        <a href="https://web.facebook.com/AM-Engineering-100526982544816/?ref=pages_you_manage"><i class="fa fa-facebook-official" aria-hidden="true" style="font-size: 40px; color: white; background-color:blue; border-radius: 60%;"></i>   AMEngineering(Automation services)</a> <br> <br>
        <a href="https://web.facebook.com/AM-Engineering-100526982544816/?ref=pages_you_manage"><i class="fa fa-instagram" aria-hidden="true" style="font-size: 40px;"></i> AMEngineering(Automation services) </a> <br><br>
        <a href="https://web.facebook.com/AM-Engineering-100526982544816/?ref=pages_you_manage"><i class="fa fa-youtube-play" aria-hidden="true" style="font-size: 40px; color: red;"></i> AMEngineering(Automation services) </a> <br><br>
        <a href="https://web.facebook.com/AM-Engineering-100526982544816/?ref=pages_you_manage"><i class="fa fa-twitter" aria-hidden="true" style="font-size: 40px;"></i> AMEngineering(Automation services) </a>  <br> <br>
        <a href="https://wa.me/message/QWRSB6ABNWC7G1"><i class="fa fa-whatsapp" aria-hidden="true" style="color: green; font-size: 40px;"></i> https://wa.me/c/923035700527 </a>
        <br> 

      </div>
    </div>




    <div class="container-fluid">
      <div class="row bg-dark">
        <div class="col-lg-12">
          <p style="padding: 10px; text-align: center; border-top: 1px solid white;">Copyright © A.M. Engineering. 2021 <br>
            Designed & Developed By ameng Developer</p>
        </div>
      </div>
    </div>
  </div>
</div>


<!--aos linl-->
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
      AOS.init();
    </script>
    
<!---java script link-->
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
  AOS.init();
</script>
<script src="js/bootstrap.bundle.min.js"></script>
</body>
</html>