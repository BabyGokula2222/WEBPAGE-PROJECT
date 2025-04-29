# WEBPAGE-PROJECT
# HTML CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="icecream.css">
    <title>BABY ICE CREAMES</title>
</head>
<body>
    <hearder>
        <span class="logo">Logo</span>
        
        <span>
            <a href="#">HOME</a>
            <a href="#">FLAVOR'S</a>
            <a href="#">SERVICE'S</a>
            <a href="#">BRANCHE'S</a>
            <a href="#">CONTACT</a>
            <a href="#">ABOUT</a>
            <a href="#"class="buy-btn">BUY NOW</a>
        
        </span>
    
    </hearder>
    <section class="main-section">
        <div class="text-box">
            <h2>CHOOSE YOUR FAVOURITE</h2>
            <h2>ICE CREAM</h2></span>
            <h2>FLAVOR</h2>
            <h4>BABY'S ICE CREAM</h4>
            <h1>**FREE DELIVERY**</h1>
            <P>Littile BABY's ice-cream ->>>prided itself on crafting small-batch hand-made super-premium ice cream with inventive flavours that challenged traditional.some of their notable flavours</P> 
            <button class="buy-btn">BUY NOW</button>
        </div>
        
        <img src="https://img.pikbest.com/origin/09/21/20/35KpIkbEsTYWR.png!w700wp" alt="ice-cream">
    </section>
    
</body>
</html>

# CSS CODE:
body{
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: linear-gradient(to right,#8e2de2,#c31432);
    color: bisque;
}
header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 50px;
}
.logo{
    font-size:50px ;
    font-style:italic;
    color:rgb(255, 47, 175);
    font-weight: bold;
}

span a{
    
    color:black;
    text-align: center;
    margin: 0 45px;
    font-weight: bold;
    font-size: larger;
}
.main-section{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 60px 50px;
}
.text-box{
    max-width: 500px;
}
.text-box h2{
    font-family: 'Brush Script MT', cursive;
    font-size: 24px;
}
.text-box h2{
    font-size: 48px;
    margin:  10px 0;
}
.text-box h4{
    font-size: 70px;
    margin: 10px 0;
    color: #c31432;
    font-style: italic;
}
.text-box h1{
    display: block;
    margin:  10px 0;
    font-size: 25px;
    color: rgb(9, 230, 101);
}
.text-box p{
    font-size: 30px;
    line-height: 1.5;
    color:black;
}
.buy-btn{
    margin-top: 20px;
    padding:  12px 24px;
    background-color:orange;
    color: #333;
    font-weight: bold;
    border: none;
    border-radius: 8px;
    cursor:pointer;
    font-size: medium;
}
ice-creame-img{
    max-width: none;
    border-radius: none;
    align-items: right;
    height: 50px;
    width: 50px;
}
 

           
            


    


    
