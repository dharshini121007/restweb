# Ex.07 Restaurant Website
## Date:07.10.2025

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
home.html
<html>
    <head>
        <title>My Restaurant</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <header>
        <h1>TAMIZH THATTU</h1>
    <nav>
        
          <a href="home.html">Home</a>
          <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
       
    </nav>
        </header>
<div>
    <h2>Tamizh Thattu-A soulful spread of Tamil flavors, served with heritage, heart, and a hint of home.</h2>
    <p>- Where every meal is a masterpiece of Tamil heritage.</p>
     <img src="logo1.jpg" alt="Restuarnt Banner" class="banner">
</div>  
</body>
<footer>
    <P>&copy;Dharshini.M(25008655)</P>
</footer>

    </body>
</html>

style.css
body
{
    background-color:rgb(245, 248, 249) ;
    color:black;
    size: 10px;
     margin: 0;
      padding: 0;
}
header
{
     background-color: rgb(0, 0, 0);
     color:rgb(255, 255, 255);
     text-align: center;
}
header h1
{
    font-size: x-large;
    margin-bottom: 15px;
}
nav a
{
   color:white;
   font-size: large;
}
div
{
    text-align: center;
    padding: 50px 25px;
}
.banner
{
   width: 90%; 
   height: 70%;
   object-fit: cover;
   margin-bottom: 30px;
}
.h2
{
    font-size: medium;
    margin-bottom: 25px;
}
p
{
     font-size: medium;
     color: black;
}
footer
{
    text-align: center;
    padding: 10px;
    width: 100%;
    bottom:0;
    position:fixed;
    color:black;

}
menu.html
<html>
    <head>
        <title>My Restaurant</title>
        <link rel="stylesheet" href="style2.css">
    </head>
    <body>
        <header>
            <h1>OurMenu</h1>
            <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
            </nav>
        </header>
        <div class="container">
            <div class="foods">
            <img src="food1.jpg" alt="food1">
            <h2>Poori</h2>
            </div>
            <div class="foods">
            <img src="food2.jpg" alt="food2">
            <h2>Vada</h2>
            </div>
            <div class="foods">
            <img src="food3.jpg" alt="food3">
            <h2>Pongal</h2>
            </div>
            <div class="foods">
            <img src="food4.jpg" alt="food4">
            <h2>Full Veg Meals</h2>
            </div>
            <div class="foods">
            <img src="food5.jpg" alt="food5">
            <h2>Full Non Veg Meals</h2>
            </div>
            <div class="foods">
            <img src="food6.jpg" alt="food6">
            <h2>Chicken Briyani</h2>
            </div>
            <div class="foods">
            <img src="food7.jpg" alt="food7">
            <h2>Idly</h2>
            </div>
            <div class="foods">
            <img src="food8.jpg" alt="food8">
            <h2>Dosa</h2>
            </div>
            <div class="foods">
            <img src="food9.jpg" alt="food9">
            <h2>Upma</h2>
            </div>
        </div>
        <footer>
             <P>&copy;Dharshini.M(25008655)</P>
        </footer>
    </body>
</html>

style2.css
body
{
    background-color: rgb(55, 193, 168);
    color: black;
    size: 10px;
    margin: 0;
    padding: 0;

}
header
{
     background-color: rgb(100, 13, 13);
     color:cornsilk;
     text-align: center;
}
nav a
{
   color:white;
   font-size: x-large;
}
.container
{
   display: flex;
  flex-flow: row;
   align-items: flex-start;
}


.foods
{
    padding: 10px;
    width:100px;
    height:150px;
    margin: auto;
    border: 4px solid rgb(6, 6, 6);
    flex-wrap: nowrap;
    font-size: small;
}
img{
    width: 100px;
    height: 100px;
    object-fit: cover;
}
footer
{
    text-align: center;
    padding: 10px;
    width: 100%;
    bottom:0;
    position:fixed;
    color:black;

}
admin.html
<html>
    <head>
         <title>My Restaurant</title>
        <link rel="stylesheet" href="style3.css">
    </head>
    <body>
        <header>
            <h1>AdminTeam</h1>
            <nav>
                <a href="home.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="admin.html">Administration</a>
                <a href="contact.html">Contact Us</a>
            </nav>
        </header>
        <div>
            <div class="team">
                <div class="person">
                <img src="dharshini.jpg" alt="person1">
                <h3>Dharshini.M</h3>
                <h4>Owner</h4>
                </div>
                <div class="person">
                    <img src="dad.png" alt="person2">
                    <h3>Madhavan.V</h3>
                    <h4>GeneralManager</h4>
                </div>
                 <div class="person">
                    <img src="abishek.jpeg" alt="person3">
                    <h3>AbishekSharma</h3>
                    <h4>HRManager</h4>
                </div>
                 <div class="person">
                    <img src="rohitsharma.jpg" alt="person4">
                    <h3>RohitSharma</h3>
                    <h4>FinanceManager</h4>
                </div>
                 <div class="person">
                    <img src="rahul.jpg" alt="person5">
                    <h3>Rahul</h3>
                    <h4>ProcurementManager</h4>
                </div>
                 <div class="person">
                    <img src="shreyas.jpeg" alt="person6">
                    <h3>SheryasIyer</h3>
                    <h4>MarketingManager</h4>
                </div>

            </div>
        </div>
        <footer>
               <P>&copy;Dharshini.M(25008655)</P>
        </footer>
    </body>
</html>
style3.css
body{
    background-color: rgb(50, 110, 26);
    color: black;
    size: 10px;
    margin: 0;
    bottom: 0;
    top:10%;
}
header{
    background-color: yellow;
    color:rgb(207, 9, 42);
    text-align: center;
}
.team{
    display: flex;
  flex-flow: row;
   align-items: flex-start;
}
.person{
    padding: 15px;
    top: 10%;
    bottom: 10%;
    margin: auto;
    border: 3px solid rgb(6, 6, 6);
    flex-wrap: nowrap;
    font-size:large;
    border-radius: 10px;
}
img{
     width: 150px;
    height: 200px;
    object-fit: cover;
}
footer
{
    text-align: center;
    padding: 10px;
    width: 100%;
    bottom:0;
    position:fixed;
    color:black;

}
contact.html
<html>
    <head>
        <title>My Restaurant</title>
        <link rel="stylesheet" href="style4.css">
    </head>
    <body>
        <header>
        <h1>Contact Us</h1>
        </header>
              <section id="contact">
                <address>
                    <h2>Visit Our Restaurant at:</h2>
                    2, Bhagirathi Ammal St, T. Nagar, Chennai.<br>
                    phone: 044-2678 1234<br>
                    Email:Thamizhthattu07@gmail.com
                </address>
           </section>
           <footer>
               <P>&copy;Dharshini.M(25008655)</P>
        </footer>
    </body>
</html>
style4.css
body{
    background-color: rgb(37, 212, 136);
    color: black;
    margin: 0;
}
header{
    text-align: center;
    background-color: rgb(251, 47, 193);
    color: black;
}
#contact{
    background-color: rgb(114, 234, 216);
     padding: 40px 20px;
    margin: 40px auto;
    max-width: 600px;
    border-radius: 8px;
    text-align: center;
}
#contact h2 {
     margin-bottom: 40px;
     color: rgb(0, 0, 0);
}
address {
    color: #333;
}
footer
{
    text-align: center;
    padding: 10px;
    width: 100%;
    bottom:0;
    position:fixed;
    color:black;

}
```

## OUTPUT:
![alt text](<Screenshot (54).png>)
![alt text](<Screenshot (55).png>)
![alt text](<Screenshot (56).png>)
![alt text](<Screenshot (57).png>)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
