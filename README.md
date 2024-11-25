# Ex04 Places Around Me
## Date:25.11.2024 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
tmap.html

<html>
<head>
<title> My City</title>
</head>
<body> 
<h1 align="center">
<font color="red"<b>Thoothukudi</b></font>
</h1>  
<h3 align="center">
<font color="blue"<b>Elfreeda Jesusha J</b></font>
</h3> 
<center>
<img src="map.png" usemap="#imagemap">
<map name="imagemap">
<area target="_blank" alt="Roach beach" title="Roach beach" href="roach.html" coords="1018,442,34" shape="circle">
<area target="_blank" alt="Harbour Beach" title="Harbour Beach" href="harbour.html" coords="1103,657,53" shape="circle">
<area target="_blank" alt="Snows Basilica" title="Snows Basilica" href="snows.html" coords="1003,328,64" shape="circle">
<area target="_blank" alt="Mullakadu beach" title="Mullakadu beach" href="tforest.html" coords="1009,699,38" shape="circle">
<area target="_blank" alt="Korampallam" title="Korampallam" href="kora.html" coords="714,489,48" shape="circle">
</map>
</map>

roach.html

<html>
<head>
<title>Roach beach</title>
<head>
<body bgcolor="cyan">
<h1 align="center">
    <font color="red"<b>Thoothukudi</b></h1></font></h1>
<h3 align="center">
    <font color="blue" <b>Roach beach</b></font></h3>
<p><font size="5" <b>Roach beach is a picturesque place with backwaters and greenery.It has a children's park and a lot other amenities.It is situated on the Beach road in Thoothukudi</font></b></p>
</body>
</html>

harbour.html

<html>
<head>
<title>Harbour Beach</title>
<head>
<body bgcolor="yellow">
<h1 align="center">
    <font color="red"<b>Thoothukudi</b></h1></font></h1>
<h3 align="center">
    <font color="blue" <b>Harbour Beach</b></font></h3>
<p><b><font size="5" Harbour beach is a port located in the Harbour estate of Thoothukudi.It supports the occupations of seaweed farmers and fishermen.It is a hub for import,export and logistics.</font> </b></p>
</body>
</html>

snows.html

<html>
<head>
<title>Snows Basilica</title>
<head>
<body bgcolor="orange">
<h1 align="center">
    <font color="red"<b>Thoothukudi</b></h1></font></h1>
<h3 align="center">
    <font color="blue" <b>Snows Basilica</b></font></h3>
<p><font size="5" <b>Snows Basilica is a shrine dedicated to Virgin Mary.It is situated along the Beach road.It is known for the temple festival which happens yearly for almost 10 days. </font></b></p>
</body>
</html>

tforest.html

<html>
<head>
<title>Mullakadu beach</title>
<head>
<body bgcolor="green">
<h1 align="center">
    <font color="red"<b>Thoothukudi</b></h1></font></h1>
<h3 align="center">
    <font color="blue" <b>Mullakadu beach</b></font></h3>
<p><font size="5" <b>Mullakadu beach is a remote beach situated on the outskirts of Tuticorin.It is known for its clear water and peaceful ambience.It has a Shiva temple by the shore.</font></b></p>
</body>
</html>

kora.html

<html>
<head>
<title>Korampallam</title>
<head>
<body bgcolor="brown">
<h1 align="center">
    <font color="red"<b>Thoothukudi</b></h1></font></h1>
<h3 align="center">
    <font color="blue" <b>Korampallam</b></font></h3>
<p><font size="5" <b>Korampallam is a village situated on the outskirts of Thoothukudi.It is a home to many ponds and lakes.It is also the abode of Sankara Rameshvarar Tirukoil.</font> </b></p>
</body>
</html>

```



## OUTPUT

![alt text](<Screenshot 2024-11-25 170144-1.png>)
![alt text](<Screenshot 2024-11-25 170230.png>)
![alt text](<Screenshot 2024-11-25 170307.png>)
![alt text](<Screenshot 2024-11-25 170328.png>)
![alt text](<Screenshot 2024-11-25 170350.png>)
![alt text](<Screenshot 2024-11-25 170411.png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
