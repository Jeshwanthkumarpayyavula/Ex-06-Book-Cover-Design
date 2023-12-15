# Ex-06-Book-Cover-Design
# Aim:
To create a book cover design using Html and Css code's
## Step1:
Select an image from online and make it as background image
## Step2:
Using vs code create a html and css files
## Step3:
Try some designs and some font over the image
## Step4:
Also select another background images and make it small and paste it
## Step5:
Give the author name and photo down below the book cover
## Step6:
Run the Html Program to see the results
# Program:

book.html::
```
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="book.css">
</head>
<body>
   

<h1>Classmate</h1>
<hr>
<p align="center">Life is not as easy as u think.</p>

<p align="center">Work hard and smart to taste the success.</p>
<p align="center">Dont waste Your time!!</p>
<ul>
<li><p align="left">All is about Ur Life</p></li>
<li><p align="left">So Be calm and start working</p></li>

</ul>
<hr>
<div class="edit">
  <p>First Edition</p>
  
</div>
<div class="top">
  <img src="coool.jpeg" alt="">
</div>

  <img src="myphoto.jpg" alt="">
  <div class="create">
    <p>~By Jeshwanth kumar</p>
  </div>
  <div class="class">
    <img src="class.jpeg" alt="">
  </div>
</body>

</html>


```
book.css:
```
body {
    background-image: url("ii.jpeg");
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    margin-left: 100px;
    color:  white;
    .link {
      position: right;
    }
  }
  a {
    object-position: right;
    position: fixed;
    color: lightgreen;
  }
  .edit {
    position: sticky;
    left: 0;
    font-size: 50px;
    color:lightgreen;
      }
  
  h1 {
    color: lightgreen;
    font-size: 50px;
  }
  p {
     font-size: 40px;
  }
  img {
    margin-bottom: 100px;
    margin-right: 100px;
    float: right;
  }
  .create {
    position: fixed;
    right: 0;
    margin-bottom: 100px;
    margin-right: 100px;
    bottom: 100px; 
    color: lightgreen; 
  }
  
 .class {
  position: fixed;
  top: 0;
  right: 0;
 }
 .top {
    margin-bottom: 100px;
    margin-left: 0%;
    float: left;
```
 }
# Output:
![image](https://github.com/Jeshwanthkumarpayyavula/Ex-06-Book-Cover-Design/assets/145742402/d082db95-a25b-4296-bb49-688882010d30)


 
