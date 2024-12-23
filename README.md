# Ex.06 Book Front Cover Page Design
## Date: 05/12/2024

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

    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            

        }



        .bookpage {
            width: 400px;
            height: 600px;
            color: rgb(0, 0, 0);
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow';
            background-image: url(download.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
        }

        .insight {
            color: rgb(24, 180, 0);
        }

        .hrstyle {
            width: 100px;
        }

        .author {
            display: inline;
            position: relative;
            color: rgb(14, 13, 13);
            top: 190px;
            font-family: Georgia;
            font-size: medium;
        }

        .booktitle {
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .id {
            width: 400px;
            position: relative;
            top: 180px;
        }

        .pub {
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }

        .ed {
            color: rgb(8, 8, 8);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 230px;
            right: 410px;
        }

        .subtitle {
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 40px;
        }

        .mypic img {
            position: relative;
            top: 170px;
            left: 260px;
            width: 100px;
            height: 100px;
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
            <hr style="color: yellow;">
        </div>
        <div class="booktitle">
            <h1>Responsive Web Design with HTML5 and CSS</h1>
        </div>
        <div class="subtitle">
            develop future-proof responsive websites using the lat
        </div>
        <div class="mypic">
            <img src="IMG-20240909-WA0013.jpg" width="150">
        </div>
        <div class=" id">
            <hr style="color: orange;">
        </div>
        <div class="author">
            <p><b>SAVISH.R</b></p>
        </div>
        SEC
    </div>
    <div class="ed">
        <b>Second Edition</b>
    </div>
    </div>
</body>

</html>
```

## OUTPUT:
![alt text](<Screenshot (68).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
