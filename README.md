# Project Responsive Web Design using Bootstrap
## Date:9-5-2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PRODUCTS</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:teal;
            color:white;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:60%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:rgb(198, 239, 144);
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:rgb(27, 30, 30);
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:white;
        }
        .bottomdiv{
            background-color:rgb(224, 220, 13);
            color:white;
            text-align: center;
            position:fixed;
            bottom:0;
            width:100%;
        }
    </style>
</head>
<body background="company img.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">HatTrick Crafts</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2" style="color: black;">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
                <img src="adobe.jpeg" width="200px">
                <h1>Adobe Creative Cloud Suite</h1>
                <p>Photoshop, Illustrator & More.</p>
            </div>
            <div class="box">
                <img src="maple.jpeg" width="200px" height="200px">
                <h1>Maple</h1>
                <p>Statistical Package</p>
                </div>
            <div class="box">
                <img src="sas.jpeg" width="200px" height="200px">
                <h1>SAS</h1>
                <p>Statistical Analysis System.</p>
                </div>
            <div class="box">
                <img src="matlab.jpeg" width="200px" height="200px">
                <h1>Matlab</h1>
                <p>Coding Software</p>
                </div>
            <div class="box">
                <img src="pycharm.jpeg" width="200px">
                <h1>Jetbrains Pycharm</h1>
                <p>Computer Programming</p>
                </div>
            <div class="box">
                <img src="office.jpeg" width="200px" height="200px">
                <h1>Microsoft Office Suite</h1>
                <p>Word, Powerpoint, Excel & More.</p>
                </div>
        </div>
    </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Pavithra M(212221040119)</p>
    </div>
</body>
</html>
```

## OUTPUT:
![Screenshot (37)](https://github.com/selvasachein/Pharma/assets/119229774/efc63e03-5c35-4849-961a-023624c8172a)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
