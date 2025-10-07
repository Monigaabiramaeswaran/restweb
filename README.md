# Ex.07 Restaurant Website
## Date:07/10/2025

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
    <title>PANDA RESTAURANT</title>
    <link rel="stylesheet" href="home.css">
</head>
<body>
    <div class="head">
        <h1>PANDA RESTAURANT</h1>
    </div>
    <div class="list">
        <ul>
            <li><a href="home.html">HOME|</a></li>
            <li><a href="food.html"> FOOD|</a></li>
            <li><a href="admin.html"> ADMIN|</a></li>
            <li><a href="contact.html"> CONTACT|</a></li>
        </ul>
    </div>
    <hr>
    <div class="center">
        <P class="type">BITE BLISS SPOT</P>
        <h1 class="quote">&QUOT;“Where every bite brings bliss — welcome to Bite Bliss!&QUOT;</h1>
        <p>Welcome to Bite Bliss, where flavor meets happiness! Step into a modern dining space<br> designed to delight your senses with mouthwatering dishes, stylish ambiance, and exceptional service. <br>At Bite Bliss, every meal is crafted with passion and creativity to bring you a perfect blend of taste and comfort. <br>Whether you’re craving a quick bite, a cozy meal with friends, or a family feast, we serve it all with freshness and flair.<br> Come, experience the true joy of dining — because at Bite Bliss, every bite is pure bliss!
</p>
    </div>
    <div class="bottom">
        <img src="restaurant.jpg" alt="interior" width="200" height="100">
    </div><hr>
    <h3 class="foot">&copy;A.MONIGA(25017526)</h3>
</body>
</html>

home.css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    background-image:url(panda.jpg);
    height: 100%;
    width: 100%;
    background-size: cover;
    background-position: center;
}
.head,.list,ul,li{
    display: inline-block;
}
ul{
    margin-left: 80%;
    display: flex;
}
li{
    background-color: pink;
}
li:hover{
    background-color: darkblue;
    border-radius: 0px;
}
h1{
    color:red;
    margin: 20px;
}
.type{
    margin-right: 70%;
}
p{
    color: black;
    font-size: 20px;
    margin: 20px;
    text-align: center;
}
.quote{
    text-align: center;
}
.bottom{
    margin-left: 30%;
}
.foot{
    text-align: center;
    color: red;
}

food.html

<html >
<head>
    <title>FOOD Page</title>
    <link rel="stylesheet" href="food.css">
</head>
<body>
    <div class="head">
    <h1>food</h1>
    </div>
    <div class="list">
        <ul>
            <li><a href="home.html">HOME|</a></li>
            <li><a href="food.html"> FOOD|</a></li>
            <li><a href="admin.html"> ADMIN|</a></li>
            <li><a href="contact.html"> CONTACT|</a></li>
        </ul>
        <h2>Foood Items</h2>
        <div class="food-item">
            <div class="food">
                <img src="chickenbiryani.jpg" alt="biryani" width="200" height="150">
                <h3>chicken biryani</h3>
            </div>
            <div class="food">
                <img src="muttoncurry.jpg" alt="mutton curry" width="200" height="150">
                <h3>mutton curry</h3>
            </div>
            <div class="food">
                <img src="chickencurry.jpg" alt="chicken curry" width="200" height="150">
                <h3>chicken curry</h3>
            </div>
            <div class="food">
                <img src="tandoori.jpg" alt="tandoori" width="200" height="150">
                <h3>chicken tandoori</h3>
            </div>
            <div class="food">
                <img src="eralthokku.jpg" alt="Eral Thokku" width="200" height="150">
                <h3>Eral Thokku</h3>
            </div>
            <div class="food">
                <img src="fishcurry.jpg" alt="Fish curry" width="200" height="150">
                <h3>Fish curry</h3>
            </div>
            <div class="food">
                <img src="chicken65.jpg" alt="chicken 65" width="200" height="150">
                <h3>chicken 65</h3>
            </div>
            <div class="food">
                <img src="chillichicken.jpg" alt="chilli chicken" width="200" height="150">
                <h3>chilli chicken</h3>
            </div>
            <div class="food">
                <img src="fishfry.jpg" alt="fish fry" width="200" height="150">
                <h3>fish fry</h3>
            </div>
            <div class="food">
                <img src="eggmasala.jpg" alt="egg masala" width="200" height="150">
                <h3>egg masala</h3>
            </div>
            <div class="food">
                <img src="eggomlete.jpg" alt="egg omlete" width="200" height="150">
                <h3>egg omlete</h3>
            </div>
            <div class="food">
                <img src="chilliparotta.jpg" alt="Chilli Parotta" width="200" height="150">
                <h3>Chilli Parotta</h3>
            </div>
    </div>
    <h3 class="foot">&copy;A.MONIGA(25017526)</h3>
</body>

food.css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    background-image: url(backgroundfood.jpg);
    background-size: cover;
    background-attachment: fixed;
    text-align: center;
    line-height: 1.6;
}
h2{
    color: lime;
}
h3{
    color: limegreen;
}
.list,ul,li{
    display: inline;
    background-color: white;
}
li:hover{
    background-color: lightgrey;
}
h1{
    color: blue;
    background-color: yellow;
}

.food{
    border: 2px solid pink;
    margin: 20px;
    padding: 20px;
    border-radius: 10px;
    background-color: darkgreen;
    display: inline-block;
}
.food:hover{
    background-color: green;
    transform: scale(1.1);
    transition: 0.3s;
}
.food-item h3{
    color: white;
}

admin.html

<html >
<head>
    <title>Admin page</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <div class="head">
    <h1>Administration Team</h1>
    </div>
    <div class="list">
        <ul>
            <li><a href="home.html">HOME|</a></li>
            <li><a href="food.html"> FOOD|</a></li>
            <li><a href="admin.html"> ADMIN|</a></li>
            <li><a href="contact.html"> CONTACT|</a></li>
        </ul>
    </div>
    <h2>team members</h2>
    <div class="team">
        <div class="member">
            <img src="ADMIN1.jpg" alt="Admin 1" width="200" height="200">
            <h3>shizuka</h3>
            <p>CEO</p>
        </div>
        <div class="member">
            <img src="ADMIN2.jpg" alt="Admin 2" width="200" height="200">
            <h3>lavanya</h3>
            <p>Marketing Manager</p>
        </div>
        <div class="member">
            <img src="ADMIN3.jpg" alt="Admin 3" width="200" height="200">
            <h3>pruthvi</h3>
            <p>Operation manager</p>
        </div>
        <div class="member">
            <img src="ADMIN4.jpg" alt="Admin 4" width="200" height="200">
            <h3>moniga</h3>
            <p>HR manager</p>
    </div>
        <div class="member">
            <img src="ADMIN5.jpg" alt="Admin 5" width="200" height="200">
            <h3>visaniya</h3>
            <p>Head Chef</p>
        </div>
        <div class="member">
            <img src="ADMIN6.jpg" alt="Admin 6" width="200" height="200">
            <h3>sam</h3>
            <p>Customer Service Manager</p>
        </div>
    </div>
    <hr>
    <h3 class="foot">&copy;A.MONIGA(25017526)</h3>
</body>
</html>

admin.css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    background-color: yellow;
    color: blueviolet;
    line-height: 1.6;
    text-align: center;
}
.member{
    border: 2px solid pink;
    margin: 20px;
    padding: 20px;
    border-radius: 10px;
    background-color: orange;
    display: inline-block;
}
.member:hover{
    background-color: lightblue;
    color: black;
    transform: scale(1.1);
    transition: 0.3s;
}
.list,ul,li{
    display: inline;
    background-color: white;
}
li:hover{
    background-color: lightgrey;
}
.team{
    background-color: orangered;
}

contact.html

<html >
<head>
    <title>Contact Us</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>
    <div class="head">
    <h1>Contact Info</h1>
    </div>
    <div class="list">
        <ul>
            <li><a href="home.html">HOME|</a></li>
            <li><a href="food.html"> FOOD|</a></li>
            <li><a href="admin.html"> ADMIN|</a></li>
            <li><a href="contact.html"> CONTACT|</a></li>
        </ul>
    </div>
    <div class="content">
        <h2>Contact Us</h2>
        <p>If you have any questions or would like to make a reservation,<br>please contact us using the information below:<br>
           Phone: (108) 687-2340<br>Email: bitesbliss@mail.com<br>
           Visit us at: 67k cross Street, cuddalore,TamilNadu, India<br></p>
    </div>
    <h3 class="foot">&copy;A.MONIGA(25017526)</h3>
</body>

contact.css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}
body{
    background-image:url(contactbg.jpg) ;
    background-size: cover;
    background-position: center;
    text-align: center;
}
h1{
    text-align: center;
    padding: 20px;
    color: white;
    font-size: 40px;
}
h3{
    color: lime;
}
.list,ul,li{
    display: inline;
    background-color: white;
}
li:hover{
    background-color: lightgrey;
}
.content{
    border: 2px solid pink;
    color: white;
    font-size: 20px;
    margin: 20px;
    padding: 20px;
    background-color: rgba(0, 0, 0, 0.788);
    border-radius: 10px;
}

```


## OUTPUT:
![alt text](<Screenshot (40).png>)
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
