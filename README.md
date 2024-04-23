# Ex.06 Book Front Cover Page Design
## Date: 23-04-2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>GUIDE TO WEB DESIGN</title>
        <link rel="stylesheet" href="{% static 'css/index.css' %}">
        <style>
            body{
    color:aquamarine;
    font-family: Helvetica, sans-serif;
    background-color: indian red
}

.book{
    width: 670px;
    height:700px;
    margin:auto;
    position: relative;
    background-image: url("book background.jpg");
    background-repeat: no-repeat;
    background-size:cover;
    background-position: bottom 0px center;
}
h1{
    font-size:70px;
    margin:60px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: xx-large;
    font-weight:10px;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    color:aqua

}
h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#top{
    border-bottom:2px solid orange;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 10px;
    border-top:2px solid burlywood;
    padding-top:0px;
    width:726px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.photo{
            position: relative;
            top: 170px;
            left: 550px;
            width: 150px;
            height: 150px;
            background-size: cover;
        }
#HASH {
    display: flex;
    justify-content: space-between;
}
  #HASH span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  #end{
    padding-right:60px;
  }
        </style>
    </head>
    <body>
        <section class="book">
            <br><br>
        <span id="top">THE INTERNATIONAL BESTSELLER &nbsp;&nbsp;&nbsp;</span>
            <h1>THE ART OF HAPPINESS</h1>
            <h4>A HANDBOOK FOR LIVING</h4>
            <h3>THIRD EDITION</h3>  
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>THEJASWINI D</span>
                    <span id="end"><u>SEC</u></span>
                </div>
            </footer>
           
    </section>
    </body>
</html>
```

## OUTPUT:

![Screenshot (25)](https://github.com/thejaswinidhanaraj/cover/assets/148514511/4619163a-3e36-46a2-abf5-2993a60d268d)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
