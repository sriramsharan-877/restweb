# Ex.07 Restaurant Website
## Date:27/12/25

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<html>
<head>
    <title>MY RESTAURANT</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="container">
    <div class="nav">
        <a href="web.html" class="active">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>
    <div class="tit">
       <h5D> BITE IT AND GRAB IT!</h5>
    </div>
    <div class="quote-box">
    <p>FRESH.DELICIOUS.SWEET.TASTY</p>
    </div>
    <div class="offer-1">
        <h9D>50% offer</h9D>
    </div>
    <div class="offer-box">
        <img src="burg.jpg" alt="Monthly offer" class="offer-image">
        <div class="offer-text">
            <h4>Weekend Offer</h4>
            <p class="offer-quote">"Yummy & Tasty chicken burgers are now on offer - don't miss it out !</p> 
            
        </div>
    </div>
</div>
<footer class="f">
    <p>&copy; SRI RAMSHARAN - (25001689)</p>
</footer>

</body>
</html>

menu.html
<html>
<head>
    <title> Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="menu-container">
    <div class="nav">
        <a href="web.html">HOME</a>
        <a href="menu.html" class="active">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="menu-title">Our Menu</h1>

    <div class="cards">

        <div class="card">
            <img src="burg.jpg" alt="burgers">
            <h3>Burger-325/-</h3>
            <p> Soft and delicious.</p>
        </div>

        <div class="card">
            <img src="pizza.jpg" alt="pizza">
            <h3>Pizza-150/-</h3>
            <p>A rich,creamy dessert with a cheese-based filling.</p>
        </div>

        <div class="card">
            <img src="sushi.jpg" alt="sushi">
            <h3>Sushi-120/-</h3>
            <p>soft and delicious.</p>
        </div>

        <div class="card">
            <img src="tandoori.jpg" alt="Tandoori">
            <h3>Tandoori-299/-</h3>
            <p>Spicy chicken .</p>
        </div>


        <div class="card">
            <img src="rasamalai.jpg" alt="rasamalai">
            <h3>Rasamalai-150/-</h3>
            <p>A soft fresh  and filled with delightful toppings .</p>
        </div>

        <div class="card">
            <img src="gulab.jpg" alt="gulab jamun">
            <h3>Gulab Jamun-49/-</h3>
            <p>Fresh and sweety .</p>
        </div>
    </div>
</div>
<footer class="f">
    <p>&copy; SRI RAMSHARAN - (25001689)</p>
</footer>
</body>
</html>

contact.html
       <html>
<head>
    <title> Contact DETAILS</title>

    <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="contact-container">
    <div class="nav">
        <a href="web.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html" class="active">CONTACT</a>
    </div>
    <div class="contactquote">
        <p>“ CELEBRATE DAILY.”</p>
    </div>

    <div class="contact-card">
        <h1>Contact Us</h1>
        <p class="contact-quote">VISIT US AGAIN.</p>

        <div class="contact-details">
            <p><strong>Phone:</strong> 7855 4533 97 </p>
            <p><strong>Email:</strong> ramsrest@gmail.com</p>
            <p><strong>Address:</strong> RAM'S restaurant,EAST street,western city,Delhi</p>
        </div>
    </div>
</div>
<footer class="f">
    <p>&copy; SRI RAMSHARAN- (25001689)</p>
</footer>
</body>
</html>

admin.html
<html>
<head>
    <title>ADMIN Crew</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="admin-container">
    <div class="nav">
        <a href="web.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html" class="active">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="admin-title">OUR TEAM</h1>

    <div class="admin-row">

        <div class="admin-card">
            <img src="mypic.jpeg">
            <div class="admin-info">
                <h3>Sri ramsharan</h3>
                <p class="role">CEO</p>
                <p>Leads the restaurant with a focus on quality and customer happiness.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="rohit.jpg">
            <div class="admin-info">
                <h3>Rohit sharma</h3>
                <p class="role">Marketing Manager</p>
                <p>Creates campaigns that make every food lover find us.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="hardik.jpg">
            <div class="admin-info">
                <h3>Hardik Pandya</h3>
                <p class="role">Chef</p>
                <p>Designs the signature  dessert menu.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="bumrah.jpg">
            <div class="admin-info">
                <h3>Bumrah</h3>
                <p class="role">CO-chef</p>
                <p>Designs the signature  dessert menu.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="surya.jpg">
            <div class="admin-info">
                <h3>Suryakumar Yadav</h3>
                <p class="role">HR Manager</p>
                <p>Takes care of the team and training.</p>
            </div>
        </div>


        <div class="admin-card">
            <img src="tilak.jpg">
            <div class="admin-info">
                <h3>Tilak Varma</h3>
                <p class="role">Customer Service Manager</p>
                <p>Makes sure every guest leaves with a smile.</p>
            </div>
        </div>

    </div>
</div>
<footer class="f">
    <p>&copy; SRI RAMSHARAN - (25001689)</p>
</footer>
</body>
</html>

styles.css

body {
    margin: 0;
}
.container {
    width: 100%;
    height: 730px;
    background-image: url("background.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    position: relative;
}
.nav {
    position: absolute;
    top: 40px;
    right: 60px;
}
.nav a {
    color: rgb(255, 255, 255);
    text-decoration: none;
    font-size: 18px;
    margin-left: 25px;
    font-weight: bold;
}
.nav a:hover {
    color: rgb(238, 225, 127);
}
.nav a.active{
    color: rgb(123, 27, 27);
    border-bottom: 2px solid gold;
}
.tit {
    position: absolute;
    top: 16%;
    left:6%;
    font-family: 'merlin';
    font-size:80;
    font-weight: 300;
    color: #b21527;
    letter-spacing: 4px;
    text-transform: uppercase;
}
.quote-box {
    position: absolute;
    margin-top:200px;
    margin-left:100px;
    background: rgba(17, 179, 219, 0.792);
    border-radius: 0px;
    padding:10px;
    backdrop-filter: blur(8px);
    max-width:1000px;
}
.quote-box p {
    
    font-family: 'dauphin';
    font-size: 14px;
    color: #ffffff;
    letter-spacing: 1px;
    line-height: 1.6;
}
.offer-1{
    position: absolute;
    font-family: 'dauphin';
    font-size: 50px;
    color: #fdfdfd;
    margin-top:200px;
    margin-left:800px;
    background: rgba(17, 179, 219, 0.792);
    border-radius: 1px;
    padding:10px;
    backdrop-filter: blur(8px);
    max-width:100px;
 
}
.offer-box{
    position: fixed;
    bottom: 400px;               
    left: 1000px;
    width: 460px;
    background: rgba(17, 179, 219, 0.792);
    border-radius: 2px;
    padding:20px;
    box-shadow: 0 10px 28px rgba(163, 155, 161, 0.895);
    color: #fff;
    text-align: center;
    z-index: 60;
    backdrop-filter: blur(4px);
}
.offer-image{
    width: 300px;
    height: 110px;
    border-radius: 1px;
    object-fit: cover;
    border: 0px solid #ffffff;
    box-shadow: 0 4px 12px rgba(0,0,0,0.35);
    margin-bottom: 10px;
}
.offer-text h4{
    margin: 0 0 6px;
    font-family: 'Poppins', sans-serif;
    font-size: 18px;
    letter-spacing: 2px;
    text-transform: uppercase;
}
.offer-quote{
    margin: 0 0 8px;
    font-family: 'Great Vibes', cursive;
    font-size: 20px;
    color: #c8a3a3;
}

.menu-container{
    background-image: url("background.jpg");
    padding-top:22px;
}
.menu-title{
    text-align: center;
    margin-bottom: 30px;
    letter-spacing: 3px;
    color: rgb(43, 8, 37);
}
.menu-container .nav{
    position: fixed;
    top: 20px;
    right: 60px;
}
.cards{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 0 40px 40px;
}
.card{
    width: 220px;
    background: #d090ba;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
    padding: 15px;
    text-align: center;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    cursor: pointer;
}
.card:hover{
    transform: translateY(-8px) scale(1.03);
    box-shadow: 0 8px 20px rgba(0,0,0,0.25);
}
.card img{
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 6px;
    margin-bottom: 10px;
}
.card h3{
    margin: 8px 0;
}
.card p{
    font-size: 14px;
    color: #555;
}


.admin-container{
    height:600px;
    background: url("background.jpg") center/cover no-repeat;
    padding: 80px 40px 40px;
    color: #9e1b47;
}
.admin-title{
    text-align: center;
    font-size: 40px;
    letter-spacing: 4px;
    margin-bottom:20px;
    text-transform: uppercase;
}
.admin-row{
    display: flex;
    flex-wrap: wrap;           
    justify-content: center;
    gap: 20px;
}
.admin-card{
    width: 260px;              
    display: flex;
    flex-direction: column;
    align-items: center;
    background: rgba(128, 16, 65, 0.522);
    color: #333;
    border-radius: 18px;
    padding: 18px 12px;
    backdrop-filter: blur(4px);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.admin-card:hover{
    transform: translateY(-6px);
    box-shadow: 0 10px 24px rgba(0,0,0,0.35);
}
.admin-card img{
    width: 130px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 10px;
}
.admin-info{
    text-align: center;
}
.admin-info h3{
    margin: 0 0 4px;
    font-size: 20px;
}
.admin-info .role{
    margin: 0 0 6px;
    font-weight: 600;
    font-size: 14px;
    color: #b0662d;
}
.admin-info p{
    margin: 0;
    font-size: 13px;
}


.contact-container{
    min-height: 100vh;
    background:url(background.jpg) no-repeat center/cover;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 100px;      
    padding-bottom: 80px;    
}
.contactquote{
    text-align: center;
    background-color:rgb(74, 39, 39) ;
    padding: 1px;
    border-radius:100px;
    margin-bottom: 20px;
}
.contactquote p{
    margin-top:50px;;
    font-family: 'monotype corsiva';
    font-size: 42px;
    color: #bfbfbf;
}
.contact-card{
    background: #ffffff;
    padding: 30px 40px;
    border-radius: 20px;
    margin-top:60px;
    text-align: center;
    max-width: 480px;
    width: 90%;
}
.contact-card h1{
    margin-bottom: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;
}
.contact-quote{
    font-style:normal;
    color: #7a5b3a;
    margin-bottom: 20px;
}
.contact-details p{
    margin: 6px 0;
    font-size: 15px;
}


.f{
    background: #111;
    color: #f5f5f5;
    text-align: center;
    padding: 10px 0;
    font-size: 13px;
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    z-index: 50;
}
.f p{
    margin: 0;
    letter-spacing: 1px;
}

```

## OUTPUT:
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (26).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
