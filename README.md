# Ex.06 Book Front cover-page-design
## Date: 12.12.2023
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:
### Step 1:
Write your own steps here.
### Step 2:
Create an app in the Django interface.
### Step 3:
Create a folder named 'static' in the app floder.
### Step 4:
Create a new HTML files in the static folder.
### Step 5:
Write the HTML code with relevant CSS properties
### Step 6:
Choose the appropriate style and color scheme.
### Step 7:
Insert rhe images in their appropriate places.
### Step 8:
publish the website in the localHost.
## PROGRAM:
```<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(bground.jpeg);
            background-size: cover;
        }
            

        .insight{
            color: black;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: black;
            top:180px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
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
            font-size: medium;
            position: relative;
            top:145px;
            left:330px;
        }
        .ed{
            color: black;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            text-align: center;
            top:60px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:lightblue;">
            </div>
            <div class="booktitle">
                <h1>Internet of things</h1></div>
            <div class="subtitle">
                       Impact of Internet of things
            </div>
            <div class="mypic">
                <img src="Harini.jpeg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color:white;">
            </div>
            <div class="author">
               <p><b> HARINI.N</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>
```
## Output:
![Screenshot from 2023-12-13 00-01-00](https://github.com/HARININAGAPPAN/cover-page-design/assets/147473910/3934af9e-fd0c-4c44-9ec2-6490832b97dd)
## Result:
The program for designing book front cover page using HTML and CSS is completed successfully.
