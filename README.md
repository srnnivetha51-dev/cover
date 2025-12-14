# Ex.05 Book Cover Page Design
## Date:

## AIM:
To design a book back cover page using HTML and CSS.

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
cover.htm<html>
<head>
    <title>About the Book</title>
    <link href="styles.css" rel="stylesheet">
</head>
<body>
    <div class="container">
        <h2>ABOUT THE BOOK</h2>
         
        <p>
            <span class= "highlight">"INTRODUCTION TO ALGORITHMS"</span>is a book on computer programming by S R NIVEDHITHA.The book is described by 
            its publisher as "the leading algorithms text in universities worldwide as well as the 
            standard reference for professionals". It is commonly known as a reference for algorithms 
            in published papers, with over 10,000 citations documented on CiteSeerX, and over 70,000 
            citations on Google Scholar as of 2024. The book sold half a million copies during its 
            first 20 years, and surpassed a million copies sold in 2022. Its fame has led to the 
            common use of the abbreviation "CLRS".
        </p> 
        <div class="box">
            <p>"But now that there are computers, there are even more algorithms, and algorithms lie at the heart of..."</p>
        </div>
        <div class="author">
            <img src="p.jpg" class="aut-img">
            <div class="content">
                <h3>S R NIVEDHITHA</h3>
                <p>
                    Nivedhitha is a sincere and dedicated individual.Has a strong interest in learning and self-improvement.
                    Shows curiosity towards technology and problem-solving.
                    Believes in discipline, consistency, and hard work.
                    Always strives to achieve goals with a positive attitude.
                </p>
            </div>
        </div>
        <footer class="footer">
            <span class="left">THE MIT PRESS PUBLISHERS</span>
            <span class="center">Price: 1000 rupees</span>
        </footer>
    </div>
</body>
<body>
    <h2 class="ref">S R NIVEDHITHA (25000724)</h2>
</body>
</html>

styles.css
body
{
    background:aliceblue;
}
.container
{   
    top:0;
    width:500px;
    height:610px;
    background-image:url('2.png');
    background-size:cover;
    background-position:center;
    border:5px solid rgb(166, 62, 142);
    border-radius:15px;
    box-shadow:inset;
    text-align:left;
    padding:25px;
    margin:30px auto;
    color:white;
    font-style: italic;
    display:flex;
    flex-direction: column;
}
.highlight
{
    background:skyblue;
}
.box
{
    background:blanchedalmond;
    border-left:5px solid red;
    padding:6px;
    margin:20px 0px;
    font-style:oblique;
    color:black;
}
.aut-img
{
    width:70px;
    height:80px;
    border-radius: 5px;
    object-fit:cover;
    margin-right: 10px;
}
.author
{
    display:flex;
    align-items: center;
    background-color: beige;
    color:brown;
    padding:5px;
    border-radius:9px;
    margin-top: 10px;
}
.footer
{
    margin-top: 25px;
    display:flex;
    background:burlywood;
    color:blueviolet;
    padding:12px 18px;
    border-radius:5px;
    font-weight:bold;
    justify-content: space-between;
}
.ref
{
    background-color:brown;
    color: black;
    text-align: center;
}
h2
{
    color:blueviolet;
}

```


## OUTPUT:
![alt text](<Screenshot 2025-12-14 094146.png>)


## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
