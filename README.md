# Ex.06 Book Front Cover Page Design
## Date:08.05.2025

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
<html>
<head>
    <title>CSE</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:rgb(162, 67, 67);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(premium_photo-1701534008693-0eee0632d47a.jpeg);
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(0, 194, 194);
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(188, 42, 42);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(37, 143, 143);
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:rgb(63, 182, 182);
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:rgb(7, 138, 138);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:azure;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                MUSIC
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(157, 121, 66)">
            </div>
            <div class="booktitle">
                <h1>INTRODUCTION TO COMPUTER SCIENCE</h1></div>
            <div class="subtitle">
                 books for beginners
            </div>
            <div class="subtitle">
                 Top seller of 2023
            </div>

            <div class="mypic">
                <img src="WhatsApp Image 2024-12-03 at 08.55.29_d9bb30b0.jpg" width="120" height="100" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>VISVES H</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
        

</html>


```


## OUTPUT:
![alt text](<Screenshot (21).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
