## Date:
# Ex.06 Book Front Cover Page Design

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
```C
<!DOCTYPE html>
<html>

<head>
    <title>WEB APPLICATION DEVELOPMENT</title>
    <style>
         <style>
        h1, h2 {
            color: white;
            font-family: 'Copperplate Gothic Light', sans-serif;
        }
        .mypic{
            position: absolute;
            top: 10px;
            left: 150px;
            bottom: 100px;
            width: 400px;
            height: 700px;
            background-size:contain;
        }
       body{
            width: 400px;
            height: 700px;
            color:rgb(239, 239, 239);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('C:\Users\Admin\Desktop\ex6\PICSS\DINESH.jpg');
            background-repeat: no-repeat;
            background-size: cover;
        }
       .insight{
            color:rgb(255, 255, 255);
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-weight: 500;
        }
        .hrstyle{
            width:100px;
        }
        .author{
            display: inline;
            position: relative;
            font-size: medium;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            color:rgb(255, 255, 255);
            top:170px;
            left: 20px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(255, 255, 255);
            font-family: garamond;
            font-size: x-large;
            text-align: center;
            position: relative;
            top: 10px;
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
        }
        .pub{
            color: #fff5f5;
            font-family: 'Times New Roman', Times, serif;
            font-size: medium;
            position: relative;
            top:60px;
            left:300px;
        }
        .ed{
            color:rgb(255, 255, 255);
            font-size: medium;
            font-family: Georgia, 'Times New Roman', Times, serif;
            position:relative;
            top:100px;
        }
        .subtitle{
            color:rgb(255, 255, 255);
            font-family: 'Times New Roman', Times, serif;
            font-size: large;
            position: relative;
            top:40px;
        }
        
    </style>
    <title>Book Cover Page</title>
</head>

        <div class="body">
            <div class="mypic">
                <img src="C:\Users\Admin\Desktop\ex6\PICSS\DINESH.jpg" width="500" height="700" >
            </div>
            <div class="insight">
               <strong>COMPUTER SCIENCE ENGINEERING</strong> 
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(255, 255, 255)">
            </div>
            <div class="booktitle">
                <h1>MUSCLE<BR>CRAFT</h1></div>
            <div class="subtitle">
                 <strong>NEVER GIVE UP</strong> 
            </div>
            <div class="subtitle">
                 <strong>LIMITED EDITION</strong><br><br><br><br><br><br><br><br>
            </div>
            <div class="author">
                <p><b><strong>DHINESH P<br>(212222043001)</strong></b></p>
             </div>
             <div class="pub">
                 <strong>SAVEETHA<br>INDIA</strong>
             </div>

            
            <div class="id">
                <hr style="color:rgb(255, 255, 255)">
            </div>
            
        </div>
</body>
</html>
```

## OUTPUT:
![fundamentals book pic](https://github.com/dhinesh00406/cover/assets/147149471/c5e00106-e2f8-4edc-856b-9801afb8162a)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
