# Ex.06 Book Front Cover Page Design
## Date:08.10.25

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
<html>
<head>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color : rgb(140, 109, 172)
      background-size:cover;
      background-position: center;
      color: black;
      background-color: brown;
    }
    .cover {
      width: 1000px;
      height: 1300px;
      margin: 50px auto;
      padding: 30px;
      position: relative;
      background: rgba(126, 78, 31, 0.9); 
      border: 5px solid rgb(62, 23, 3); 
      border-radius: 2%;
    }
    .top {
      font-size: 40px;
      font-weight: bold;
      color: rgb(21, 19, 19);
      text-align: left;
      letter-spacing: 2px;
    }
    .title {
      font-size: 65px;
      font-weight: bold;
      text-align: center;
      margin-top: 80px;
      color: rgb(4, 9, 4);
      font-family: 'Times New Roman', serif;
    }
    .subtitle {
      font-size: 40px;
      text-align: center;
      margin-top: 30px;
      font-style: italic;
      color: rgb(62, 56, 62);
    }
    .special {
      font-size: 30px;
      font-weight: bold;
      margin-top: 200px;
      color: rgba(241, 236, 243, 1);
      text-align: left;
    }
    .author {
      font-size: 20px;
      font-weight: bold;
      color: black;
      margin-top: 25px;
      text-align: left;
    }
    .sec {
      position: absolute;
      bottom: 30px;
      right: 20px;
      font-size: 18px;
      color: black;
    }
    .photo {
      width: 100px;
      height: 120px;
      position: absolute;
      bottom: 60px;
      right: 100px;
      border-radius: 8px;
      border: 2px dotted yellow;
      box-shadow: 0 0 10px black
    }
  </style>
</head>
<body>
  <h1 align="center">JOSHUA DANIEL A 25017654</h1>
  <div class="cover">
    <div class="top">SEC Insights</div>
    
    <div class="title">
      CYBER THREATS<br>
    </div>
    
    <div class="subtitle">
      "Understanding the Dangers in the Digital World"<br> 
    
    </div>
    
    <div class="special">SPECIAL EDITION</div>
    
    <img src="Daniel.jpg." class="photo" alt="Author Photo">
    
    <div class="author">JOSHUA DANIEL A</div>
    <div class="sec">SEC</div>
  </div>
</body>
</html>
```


## OUTPUT:

![alt text](<Screenshot (71).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
