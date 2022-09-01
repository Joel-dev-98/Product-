# Product-
HTML CODE:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel = "stylesheet" href = "style.css">
    <title>Product details</title>
</head>
<body>
    <div>
        <div class = "Parent">
            <div class = "left">
                <picture>
                    <source 
                       media="(orientation: landscape)"
                       srcset="image-product-mobile.jpg">
                    <source 
                       media="(orientation: portrait)"
                       srcset="image-product-desktop.jpg">
                       s
                  <img src="image-product-mobile.jpg" width="100%" height="auto">
                 </picture>
            </div>
            <div class = "right">
        
               <h4>PERFUME</h4>
                 <h1>Gabrielle <br> Essence Eau <br>De Parfum</h1>
               <p> 
                  A floral, solar and voluptuous <br>interpretation composed by <br> Oliver Polge, Perfume-Creator <br>for thr House of CHANEL.
                 
               </p> 
               <p>
                <strong> $149.99</strong> was <sup><s>$169.99</s></sup>
               </p> 

               <input type="image" src="/product-preview-card-component-main/images/icon-cart.svg" name="submit" width="100" height="48" alt="submit"/>
        
           </div>
        </div>
    </div>
    
</body>
</html>

//CSS CODE:
@import url https://fonts.googleapis.com/css2?family=Lobster&family=Montserrat:wght@400;900&family=Paytone+One&display=swap" rel="stylesheet"



p{
    font-family: 'Montserrat';
}

.Parent{
    background-color:bisque;
    border-color: aquamarine;
    border-style: double;
    border-radius: 0.5cm;
    margin-top: 10%;
    margin-left: 20%;
    margin-right: 20%;
    margin-bottom: 20%;
    width: 60%;
    
    height: 100%;
    
}

.right{
    padding:5%;
    text-align:left;
    background-color: #cccccc;
    width: 20%;
    float: right;
    align-items:center;
  
}

.left{
    padding:5%;
    background-image: url("landscape-PNG-File.png")
    background-color: #cccccc;
    width:20%;
    float: left;

}

    
