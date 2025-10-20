# Ex.06 Book Front Cover Page Design
## Date:09.10.2025

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
book.html
<html>
    <head>
        <title>The Power of Habit</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="cover">
            <div class="top">
                <h3>SEC INSIGHTS</h3>
            </div>
            <div class="hrstyle">
            <hr style="color: plum">
        </div>
        <div class="booktitle">
            <h1>Habit shapes our daily life</h1>
        </div>
        <div class="subtitle">
            <p>Our habit define us</p>
        </div>
        <div class="bottom">

        <div class="Author">
            <p><b>Farzana M(25013772)</b></p>
        </div>
        <div class="edition">
            <b>1ST Edition</b>
            <hr>
        </div>
        <div class="photo">
            <img src="WhatsApp Image 2025-10-08 at 15.09.10_b0ca202b.jpg" alt="Author photo" width="80" height="80"/>
        </div>
        <div class="sec">
            <b>SEC</b>
        </div>
        </div>
    </body>
</html>
style.css
body{
  display:flex;
  justify-content:center;
  align-items:center;
  height:100vh;
  margin:0;
  background: #fefcfc;
}
.cover {
  border: solid 3px rgb(49, 61, 99);
  border: right 40%;
  border: left 40%;
  border-bottom: 40%;
  border-top: 40%;
  height: 600px;
  width:500px;
  background-image: url('Screenshot 2025-10-09 163344.png') ; 
  background-size:cover;
  background-position: center;
  padding:20px;
  color:purple;
  font-family:Arial,sans-serif;
  position:relative;
}
.top h3 {
    margin: 0;
    color: purple;
    font-size: 16px;
}
.top hr {
    border: 1px solid purple;
    margin:5px 0 20px;
}
.booktitle h1 {
    text-align: center;
    font-size: 26px;
    font-weight: bold;
    color: purple;
    margin: 60px 0 30px;
}
.subtitle {
    text-align: center;
    font-size: 14px;
    margin-bottom: 80px;
}
.bottom {
    position: absolute;
    bottom: 20px;
    left: 20px;
    right: 20px;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
}
.edition {
    font-weight: bold;
    font-size: 14px;
    color: rgb(179, 36, 139);
}
.author {
    position: absolute;
    bottom: 40px;
    left: 20px;
    font-size: 14px;
    font-weight: bold;
}
.photo {
    position: absolute;
    bottom: 50px;
    right: 20px;
}
.photo img {
    width: 100px;
    height: 100px;
    object-fit: cover;
    border: 2px solid rgb(22, 21, 21);
}
.sec {
    position: absolute;
    bottom: 20px;
    right: 20px;
    font-weight: bold;
    font-size: 14px;
}
```


## OUTPUT:
![alt text](<Screenshot 2025-10-09 170101.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
