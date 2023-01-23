# Ex-06-Book-Cover-Design

#AIM:

To design a static web site for a book cover page.

#DESIGN STEPS:
```
Step 1:
Clone the GitHub repository and create a Django admin interface.
Step 2:
Write HTML and CSS Code for designing book cover page and execute them.
Step 3:
Validate the HTML and CSS code.
Step 4:
Publish the website in the given URL.
```

#PROGRAM :
```
<!DOCTYPE html>
<html>
 <head>
 <title>Cover page</title>
 <style>
 .coverpage{
 width : 500px;
 height :1000px;
 position: relative;
 display: block;
 }
 .head{
 font-size: 50px;
 font-family: arial black;
 padding-left: 50px;
 padding-bottom: 40px;
 position:relative ;
 bottom: -50px;
 color: white
 
 }
 .head2{
 font-size: 20px;
 font-family: 'Arial', Times, serif;
 padding-top: 10px ;
 padding-left: 50px;
 position: relative;
 top: 30px;
 
 color: white
 }
 .author{
 font-size: 30px;
 color: white;
 font-family: Arial;
 position: relative;
 bottom: 70px;
 right: -50px;
 }
 .container{
 backgroundimage:url("C:\Users\srini_\Desktop\Ben.png");
 background-repeat: no-repeat;
 background-size: cover;
 width: 600px;
 height: 800px;
 position: relative;
 display: block;
 background-color: black;
 background = 
"C:\Users\srini_\Desktop\Ben.png"
 position: fixed;
 }
 .expert{
 font-size: 15px;
 color: white;
 padding-left: 50px;
 position :relative;
 bottom: -50px
 }
 .developedby{
 font-size: 20px;
 color: white;
 position: relative;
 bottom: 60px;
 right: -50px;
 }
 .publisher{
 text-decoration: underline;
 font-size: 45px;
 color: white;
 position: relative;
 bottom: 125px;
 left: 400px;
 }
 .edition{
 font-size: 30px;
 font-style:"chiller";
 color: orange;
 display: inline;
 position: relative;
 bottom: 100px;
 right: -50px;
 }
 .image1{
 position: relative;
 right: -425px;
 bottom: 60px;
 
 
 }
 .image2{
position: retalive;

 }
 .hr{
 border: 1px solid orange;
 position: relative;
 right: 0px;
 bottom: 150px;
 width: 15.82cm;
 
 }
 .hrs{
 border: 1px solid orange;
 position: relative;
 right: 117px;
 top:50px; 
 width: 7cm;
 
 }
 body{
 
 }
 </style>
 </head>
 <body>
 <div class="container">
 <div class="coverpage">
 
 <div class="expert">EXPERT INSIGHT</div>
 <hr class="hrs">
 <div class="head"><b>Responsive Web 
Design With HTML5 and CSS</b></div> 
 <div class="head2">Develop future-proof 
responsive websites<br>
 using the latest HTML5 and CSS 
techniques.</div>
<div ><img width="600px" 
src="C:\Users\srini_\Desktop\design.jpg" 
class="image2" ></div>
 <div ><img width="150px" 
src="C:\Users\srini_\Desktop\ben.png" 
class="image1" ></div>
 
 <div class="edition">Third Edition</div>
 <div class="author">BEN FRAIN</div>
 <div class="developedby">Developed By :SRINIDHI</div>
 <hr class="hr">
 <div class="publisher">Packt></div>
 
 </div>
 </div>
 
 </body>
</html>
```
#OUTPUT:

![image](https://user-images.githubusercontent.com/121373170/214098229-9a35dc6e-517e-47f6-b4ca-b7b12e201c02.png)


#Result:

Thus the Book Cover Designed successfully.
