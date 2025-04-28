# Ex.06 Book Front Cover Page Design
# Date:28/4/2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
~~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: radial-gradient(circle, #ffd700, #ff8c00);
        }
        .book-cover {
            width: 350px;
            height: 500px;
            background: linear-gradient(135deg, #5a1a1a, #a52a2a);
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            border-radius: 15px;
            box-shadow: 10px 10px 25px rgba(0, 0, 0, 0.5);
            text-align: center;
            font-family: 'Georgia', serif;
            border: 7px solid gold;
            position: relative;
            overflow: hidden;
            padding: 20px;
        }
        .book-cover img {
            width:60%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        .author-img {
            width: 15px;
            height: 15px;
            border-radius: 5px;
            border: 3px solid gold;
            margin-top: 5px;
        }
        .title {
            font-size: 30px;
            font-weight: bold;
            margin-bottom: 10px;
            text-shadow: 4px 4px 8px rgba(0, 0, 0, 0.6);
        }
        .author {
            font-size: 22px;
            font-style: italic;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <img src="web app logo.webp" alt="Book Cover Image">
        <div class="title">Web Application Development</div>
        <div class="author">by P.VIGNESHWARAN</div>
        <img class="author-img" src="author-img.jpg" alt="Author Image">
    </div>
</body>
</html>
~~~~~

# OUTPUT:
<img width="940" alt="image" src="https://github.com/user-attachments/assets/ce178889-0e4a-40a0-ab0f-36132105baf5" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
