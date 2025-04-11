# Ex04 Places Around Me
# Date:11.04.2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>TENKASI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>DHARUN ARULSELVAN(212224220024)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="home.html" title="My Home Town">
<area shape="circle" coords="570,230,45" href="sakthinagar.html" title="Sakthi Children's Park">
<area shape="circle" coords="540, 200, 30" href="temple.html" title="Arulmigu Kaasi Viswanathar Temple">
<area shape="rect" coords="600, 200, 700,500" href="king.html" title="King's Palace Hotel and Party Hall">
<area shape="rect" coords="950, 120, 1100, 140" href="rail.html" title="RAILWAY STATION">
</map>
</center>
</body>
</html>

home.html
<html>
<head>
<title>TENKASI</title>
</head>
<body bgcolor="purple">
<h1 align="center">
<font color="red"><b>TENKASI DISTRICT</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>KADAYANALLUR TALUK</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Tenkasi: is one of the 38 districts of Tamil Nadu, India, separated from Tirunelveli district on 22 November 2019. The Government of Tamil Nadu announced its creation on 18 July 2019. The district headquarters is at Tenkasi.
</font>
</p>
</body>
</html>

king.html
<html>
<head>
<title>KING'S PALACE</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="red"><b>PARTY HALL AND HOTEL</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>POSITIVE REVIEWS AND GOOD INFRASTRUCTURE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Kings Palace is an excellent choice for travellers visiting Tenkasi, offering a family-friendly environment alongside many helpful amenities designed to enhance your stay.
</font>
</p>
</body>
</html>

rail.html
<html>
<head>
<title>RAILWAY STATION</title>
</head>
<body bgcolor="black">
<h1 align="center">
<font color="white"><b>TENKASI JUNCTION</b></font>
</h1>
<h3 align="center">
<font color="white"><b>good place</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Georgia" size="5" color="white">
Tenkasi Junction railway station (station code: TSI) is an NSG–4 category Indian railway station in Madurai railway division of Southern Railway zone.[2] It is a junction railway station serving the town of Tenkasi in the Indian state of Tamil Nadu. The station is a part of the Madurai railway division of the Southern Railway zone. It is the junction point for Virudhunagar and Tirunelveli rail routes.
</font>
</p>
</body>
</html>

sakthinagar.html
<html>
<head>
<title>Sakthi Children's Park</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="red"><b>CHILDREN'S PARK</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>GOOD INFRASTRUCTURE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
It is known for its obstacle course and fun activities like ziplines and paintball. Sakthi Children's Park offers a range of amusement park rides and games.
</font>
</p>
</body>
</html>

temple.html
<html>
<head>
<title>Arulmigu Kaasi Viswanathar Temple</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="BLACK"><b>GOD IS EVERYWHERE</b></font>
</h1>
<h3 align="center">
<font color="red"><b>GOOD</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Kasi Viswanathar Temple in Tenkasi, a city in Tenkasi district in the South Indian state of Tamil Nadu, is dedicated to the Hindu god Shiva.
</font>
</p>
</body>
</html>
```

# OUTPUT
![Screenshot 2025-04-11 215146](https://github.com/user-attachments/assets/b3da9385-dc30-4729-b487-ef486762313b)
![2](https://github.com/user-attachments/assets/0c72e012-9820-41d4-8a80-9c9dba936531)
![3](https://github.com/user-attachments/assets/22fd4f2c-a7c7-401e-b740-675c6c1f8542)
![4](https://github.com/user-attachments/assets/b3d33693-738e-4857-ba2f-2a17ff81da35)
![5](https://github.com/user-attachments/assets/1409ee26-4999-491e-9495-d79326114b7f)
![6](https://github.com/user-attachments/assets/5da57819-f9e1-4e9e-8b16-7a7bd05a1fb4)







# RESULT
The program for implementing image maps using HTML is executed successfully.
