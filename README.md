<?php @include('navloginandsigin.php') ?>
<?php session_start();
$valid_user = false; ?>
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>home</title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
         <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.min.js" integrity="sha384-Rx+T1VzGupg4BHQYs2gCW9It+akI2MM/mndMCy36UVfodzcJcF0GGLxZIzObiEfa" crossorigin="anonymous"></script>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
           <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

        <link rel="stylesheet" href="style.css">
    </head>
    <style>
        * {
    box-sizing: border-box;
}

body {
    font-family: Arial, Helvetica, sans-serif;
}

/* Float four columns side by side */
.column {
    float: left;
    width: 25%;
    padding: 0 10px;
}

/* Remove extra left and right margins, due to padding */
.row {
    margin: 0 -5px;
}

/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}

/* Responsive columns */
@media screen and (max-width: 600px) {
    .column {
        width: 100%;
        display: block;
        margin-bottom: 20px;
    }
}

/* Style the counter cards */
.card {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    padding: 16px;
    text-align: center;
    background-color: #f1f1f1;
  
}
  #frist{
        font-size: x-large;
        font: bold;
        color: white;
        font-family: Arial Narrow Bold;
        font-weight: 900;
        font-size: xx-large;
    }
    #p{
        text-align: justify;
    }

    </style>
  <body> 
   
       <div class="pic">
        <img src="im/pexels-vecislavas-popa-1571459.jpg" style="height: 85%;"  class="card-img" alt="...">
        <div class="card-img-overlay " style="margin-top: 20%;text-align:center; " >
            <h1 class="card-title " id="frist" style="color:white; font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif" >HOME SERVICES</h1>
            <p class="card-text" id="frist">All services of this webiste </p>
            <p class="card-text" id="frist">Website this more use in website this work in my</p>
            <p class="card-text" id="frist"></p>
            
        </div> 
       </div>
            
    <div class="container">
        
     
        <div class="container" style="background:blue;color:white;align-items:center;text-align:center;margin-top:15px;border-radius: 8px; " >
            <h3>Welcome My website to visit</h3>
        </div>
        <center>
        <div class="container" style="margin-top: 35px;">
            <div class="row" >
                <div class="col">
                    <div class="card mb-3" style="max-width: 540px;">
            <div class="row g-0">
                <div class="col-md-4">
                <img src="icon/plumber (1).png" class="img-fluid rounded-start" alt="...">
                </div>
                <div class="col-md-8">
                <div class="card-body">
                    <h5 class="card-title">Service</h5>
                    <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                    <p class="card-text"><small class="text-muted">All services of my website</small></p>
                </div>
                </div>
            </div>
            </div>
                </div>
                 <div class="col">
                    <div class="card mb-3" style="max-width: 540px;">
            <div class="row g-0">
                <div class="col-md-4">
                <img src="icon/images.jpeg" style="margin-top: 20px;" class="img-fluid rounded-start" alt="...">
                </div>
                <div class="col-md-8">
                <div class="card-body">
                    <h5 class="card-title">Order</h5>
                    <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                    <p class="card-text"><small class="text-muted">All services of my website</small></p>
                </div>
                </div>
            </div>
            </div>
                </div>
            </div>
        </div>
       
       
          <div class="container" style="margin-top: 35px;">
            <div class="card" style="background-color:burlywood">
                <h2 style="color:blue;" >What are Services? Definition</h2>
                <p id="p">A service is defined as an intangible good that is produced and consumed simultaneously. This can be contrasted with a physical good, which is a tangible product that is produced and then consumed at a later time. While this definition may seem straightforward, the concept of a service can be difficult to wrap your head around. In this blog post, we will explore what services are and some examples to help you better understand this idea.</p>

            </div>
        </div>
         <div class="container" style="margin-top: 35px;">
<div class="card">
<div class="row">
  <div class="column">
    <div class="card">
     <img src="im/LandscapingandOutdoor1.jpg" alt="">
    </div>
  </div>

  <div class="column">
    <div class="card">
    <img src="im/cleaner1.jpg" alt="">
    </div>
  </div>
  
  <div class="column">
    <div class="card">
     <img src="im/plumber1.jpg" alt="">
    </div>
  </div>
  
  <div class="column">
    <div class="card">
      <img src="im/SecurityandAutomation.jpg" alt="">
    </div>
  </div>
</div>
</div>
            </div>
        <div class="container"  style="margin-top: 35px;background-color:blueviolet; border-radius:8px;" >
            <div class="card">
                <div class="row">
                    <div class="col">
                    <h3>Advantages and disadvantages of services</h3>
                    <p id="p" >When it comes to business, the term “services” can refer to a lot of different things. It can be anything from construction work to consulting services. But what are services, really? And what are the advantages and disadvantages of them?</p>
                    <p id="p">In short, services are businesses that provide a service rather than a product. This means that they don’t physically produce anything, but instead offer their expertise or labor. Some examples of common services include hair salons, mechanics, and plumbers.</p>
                    <p id="p">There are both advantages and disadvantages to offering services instead of products. One advantage is that it can be less expensive to start a service-based business than a product-based business. This is because you don’t need to invest in inventory or manufacturing equipment. Additionally, service businesses often have lower overhead costs than product businesses.</p>
                    <p id="p">However, there are also some disadvantages to having a service-based business. One disadvantage is that it can be harder to scale a service business than a product business. This is because you can only do so much work yourself before you need to hire additional staff. Additionally, service businesses are often more reliant on word-of-mouth marketing and personal relationships than product businesses.</p>
                    </div>
                </div>
            </div>
        </div>
       
        
                
                </div>
                <div class="container" style="color:darkslateblue;margin-top: 35px;margin-bottom:35px;" >
                <div class="card" style="background-color:burlywood" >
                <h4>Want to find out more about procurement?</h4>
                <p>Access more blogs, articles and FAQ's relating to procurement</p>
                </div>
                </div>
            </div>
        </div>
        </div>
         </center>
     <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
        <script>
            alert("Hello,Sir Wellcome to website!");
        </script>
    </body>
</html>
<?php @include('footer.php') ?>
