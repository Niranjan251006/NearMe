# Ex04 Places Around Me
## Date: 23.10.2025

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
map.html
```
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>NIRANJAN S (212224040221)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1000">
<map name="MyCity">
<area shape="circle" coords="800,76,60" href="central.html" title="Chennai Central">
<area shape="circle" coords="100,490,60" href="ripon.html" title="Greater Chennai Corporation Office">
<area shape="circle" coords="180,85,60" href="more.html" title="More Market">
</map>
</center>
</body>
</html>
```
central.html
```
<html>
<head>
<title>central</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="blueviolet"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="blueviolet"><b>CHENNAI CENTRAL</b></font>
</h3>
<hr size="3" color="black">
<p align="justify" style="font-family: Georgia; font-size: large;">
Chennai Central Railway Station, built in 1873, is a heritage Gothic Revival and Romanesque structure with a prominent clock tower, serving as a busy transport hub connecting northern India.
</p>
</body>
</html>

```
more.html
```
<html>
<head>
<title>shivan temple</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font style="color: blueviolet;"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font style="color: blueviolet;"><b>MOORE MARKET</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
    Moore Market is a historic shopping complex near Chennai Central, originally a bazaars building, now a vibrant marketplace known for textiles and antiques.
</p>
</body>
</html>
```
ripon.html
```
<html>
<head>
<title>shivan temple</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font style="color: blueviolet;"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font style="color: blueviolet;"><b>RIPON BUILDING</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
Ripon Building is a neo-classical structure housing Chennai Corporation headquarters, notable for its tall clock tower and colonial-era architecture.</p>
</body>
</html>
```

## OUTPUT

![alt text](<exp4 1.png>)
![alt text](<exp 4 2.png>) 
![alt text](<exp 4 3.png>)
![alt text](<exp 4 4.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
