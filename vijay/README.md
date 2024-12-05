# Ex.06 Book Front Cover Page Design
# Date: 05/12/2024
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
``` 
book.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="book-cover">
        <div class="best-seller">#1 NATIONAL BESTSELLER</div>
        <h1 class="title">The Art of Being Alone</h1>
        <p class="subtitle">Loneliness Was My Cage, Solitude Is My Home</p>
        <p class="author">Renuka Gavrani</p>
        <div class="man image">
            
            <img src="man.png" alt="man image">
        </div>
    </div>
</body>
</html>


style.css

body {
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: rgb(77, 74, 74);
    
}

.book-cover {
    background-color: white;
    width: 500px;
    height: 700px;
    text-align: center;
    padding: 20px;
    position: relative;
    border-radius: 15px;
    box-shadow: 5px 10px 15px rgb(18, 18, 18);
}

.best-seller {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 15px;
    color: #0c0c0c;
    margin-top: 10px;
}

.title {
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 100px;
    color: #503D33;
    margin: 20px 0;
}

.subtitle {
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-style: italic;
    font-size: 25px;
    color: #494b48;
    margin-bottom: 50px;
}


.man img {
    width: 150px;
    height: auto;
    position: absolute;
    bottom: 100px;
    left: calc(50% - 20px);
}

.author {
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    position: absolute;
    bottom:0;
    left: calc(25% - 1px);
    font-size: 25px;
    font-weight: bold;
    letter-spacing: 8px;
    color: #510cac;
    margin-bottom: 30px;
    
}
```
# OUTPUT:

![alt text](<Screenshot (82).png>)

# RESULT:

The program for designing book front cover page using HTML and CSS is completed successfully.
