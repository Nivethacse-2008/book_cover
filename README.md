# Ex.06 Book Front Cover Page Design
# Date:01/10/2025
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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fundamentals of Web Application Development</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 40px;
      flex-wrap: wrap;
      min-height: 100vh;
      background: #eee;
      font-family: 'Times New Roman', serif;
    }

    .book-cover {
      width: 350px;
      height: 550px;
      border: 5px solid #222;
      padding: 20px;
      box-sizing: border-box;
      position: relative;
      color: white;
    }

    .book-cover h1 {
      font-size: 24px;
      text-align: center;
      font-weight: bold;
      margin-top: 80px;
      line-height: 1.4;
    }

    .subtitle {
      text-align: center;
      font-size: 14px;
      margin: 10px 0;
      font-style: italic;
    }

    .top-banner {
      position: absolute;
      top: 10px;
      left: 20px;
      font-size: 14px;
      font-weight: bold;
    }

    .special-edition {
      position: absolute;
      bottom: 100px;
      left: 20px;
      font-size: 14px;
      font-weight: bold;
      color: yellow;
    }

    .author {
      position: absolute;
      bottom: 40px;
      left: 20px;
      font-size: 14px;
      font-weight: bold;
    }

    .publisher {
      position: absolute;
      bottom: 40px;
      right: 20px;
      font-size: 14px;
      font-weight: bold;
    }

    .author-photo {
      position: absolute;
      bottom: 30px;
      right: 80px;
      width: 80px;
      height: 80px;
      background: white;
      border: 2px solid #ccc;
      background-size: cover;
      background-position: center;
    }
    .purple-glow {
      background: linear-gradient(to bottom, #4b0082, #cc66ff);
      border-color: #330066;
    }
  </style>
</head>
<body>

  <div class="book-cover purple-glow">
    <div class="top-banner">SEC Insights</div>
    <h1>FUNDAMENTALS OF<br>WEB APPLICATION<br>DEVELOPMENT</h1>
    <div class="subtitle">Deep Dive in HTML, CSS & JS Basics<br>Top seller of 2025</div>
    <div class="special-edition">SPECIAL EDITION</div>
    <div class="author">S.K.NIVETHA</div>
    <div class="publisher">SEC</div>
    <div class="author-photo" style="background-image:url('book.jpg');"></div>
  </div>

</body>
</html>

```
# OUTPUT:
<img width="1366" height="768" alt="Screenshot 2025-10-04 193121" src="https://github.com/user-attachments/assets/cd5ad951-8f15-4354-b412-c0aa17c2c63a" />


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
