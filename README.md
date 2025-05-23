# Ex.06 Book Front Cover Page Design
## Date:15.5.25

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
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage {
            width: 400px;
            height: 600px;
            color: #a399eade;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-color: blueviolet;
            background-size: cover;             
            background-repeat: no-repeat;       
            background-position: center center;
            border: 2px solid #00000022; 
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
}

            

        .insight{
            color: rgb(42, 165, 65);

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(20, 196, 227);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-size: 20px;
            font-weight: bold;
            text-align: center;
            color: #efe11a;
            position: relative;
            top: 30px;
            text-shadow: 1px 1px 4px #000;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: 20px;
            position: relative;
            top:155px;
            left:330px;
            color: #00ffd5;
        }
        .ed{
            color: rgb(27, 27, 218);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            color:#c01616;
            font-size:16px;
            position: relative;
            top:40px;
            margin: 0 10px 40px 10px;
            line-height: 1.5;
            text-shadow: 1px 1px 2px #000;
            text-align: center;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                MY INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Mastering Learning With Books</h1></div>
            <div class="subtitle">
                Transform Your Mind, One Page at a Time

            </div>
            <div class="id">
                <hr style="color: rgb(41, 13, 15);">
            </div>
            <div class="author">
               <p><b>Niralya J</b></p>
            </div>
            <div class="ed">
                <b>Latest Edition</b>
            </div>
        </div>
    </body>
</html>
```
## output:

![alt text](<Screenshot (125).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
