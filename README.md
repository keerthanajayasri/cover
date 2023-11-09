# Ex.06 Book Front Cover Page Design
## Date: 09-11-23

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```

<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(bg.jpg);
            background-size: cover;
        }
            

        .toptext{
            color:thistle;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            text-align: left;
            color:yellow;
            top:130px;
            
            font-family:'ink free';
            font-size: large;
        }
        .booktitle{
            font-family: 'gabriola', monospace;
            font-size: x-large;
            text-align: center;
            position: relative;
            top: 19px;
            color:purple;
        
        }
        
    
        .edition{
            color:yellow;
            font-size: large;
            font-family: 'ink free';
            text-align: right;
            position:relative;
            top: 105px;

        }
        .subtitle{
            font-family:'Segoe script';
            font-size: large;
            text-align: center;
            position: relative;
            top:17px;
        }
        .photo{
            position: relative;
            top: 65px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        .text-container {
            position: absolute;
            top: 395px;
            left: 550px; 
            color:black;
            font-size: x-large;
            font-family: 'cambria math',sans-serif ;
        }

         .text-containers {
            position: absolute;
            top: 435px;
            left: 590px; 
            color:black;
            font-size: x-large;
            font-family: 'cambria math',sans-serif;
        }

        .text-containerss {
            position: absolute;
            top: 470px;
            left: 635px; 
            color:black;
            font-size: x-large;
            font-family:  'cambria math',sans-serif;
        }
 

         
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>

        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>

            <div class="tophr">
                <hr style="color: red;">
            </div>

            <div class="subtitle">
                TiNy  chAnGEs
            </div>

            <div class="subtitle">
                ReMarKAblE  rEsulTs....
            </div>    

            <div class="booktitle">
                <h1>ATOMIC HABITS </h1>
            </div>

            <div class="subtitle">
                An EasY wAy AnD pROvEn WAys TO BuIld gOoD haBIts & bReAk baD ONes
            </div>
            

            <div class="photo">
                <img src="C:\Users\SEC\cover\KEE2.jpg" width="130" height="145" alt="">
            </div>
            `   
            <div class="text-container">
               <p>HaBits </p> 
            </div>

            <div class="text-containers">
               <p> deFiNEs </p> 
            </div>

            <div class="text-containerss">
               <p> yOu....</p> 
            </div>

            <div class="edition">
                <b>KEERTHANA JAYASRI S K </b>
            </div>
          
            
        </div>
    </body>
</html>
```

## OUTPUT:
![output](<Screenshot 2023-11-09 081623.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
