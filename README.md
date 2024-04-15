# Ex04 Places Around Me
## Date: 14/04/24

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
<html>
<head>
<title>MY CITY</title>
</head>
<body>
<h1 align="center">
<font color="blue"><b>MADURAI</b></font>
</h1>
<center>
<img src="map1.png" usemap="#image-map">

<map name="image-map">
    <area target="_self" alt="k.pudur" title="k.pudur" href="pudur.html" coords="656,202,800,271" shape="rect">
    <area target="_self" alt="dharmathupatti" title="dharmathupatti" href="dramathupatti.html" coords="190,556,343,640" shape="rect">
    <area target="_self" alt="ananjiyur" title="ananjiyur" href="ananjiyur.html" coords="977,511,1118,588" shape="rect">
    <area target="_self" alt="kinnimangalam" title="kinnimangalam" href="kinnimangalam.html" coords="37,302,237,382" shape="rect">
    <area target="_self" alt="madurai airport" title="madurai airport" href="airport.html" coords="582,615,426,677" shape="rect">
</map>
</center>
</body>
</html>



<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="pink"><b>MADURAI</b></font>
</h1>
<h3 align="center">
<font color="green"><b>village-pudur</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="6">
It is located at about 158 m above the mean sea level with the geographical coordinates of 9.954300°N 78.150700°E 
K. Pudur is a neighbourhood in Madurai district of Tamil Nadu state in the peninsular India.[1][2][3]
Madurai, Sellur, Narimedu,, East Gate, Thathaneri, Koodal Nagar and Arappalayam are some of the important neighbourhoods of K. Pudur.

</font>
</p>
</body>
</html>


<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="purple">
<h1 align="center">
<font color="black"><b>MADURAI</b></font>
</h1>
<h3 align="center">
<font color="green"><b>village-dramathupatti</b></font>
</h3>
<hr size="3" color="yellow">
<p align="justify">
<font face="Georgia" size="6">
The Dharmathupatti village is located in Thirumangalam taluka of Madurai in Tamil Nadu, India. 
The census code of this vill is 640939. The total geographical area of Dharmathupatti village is 220.33 Hectares / 2.2 KM2. 
The nearest police station is located in Thirumangalam tahsil.
</font>
</p>
</body>
</html>


<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="black"><b>MADURAI</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>village-ananjiyur</b></font>
</h3>
<hr size="3" color="brown">
<p align="justify">
<font face="Georgia" size="6">
    The Ananjiyur village is located in Madurai North taluka of Madurai in Tamil Nadu, India. 
    The census code of this vill is 640702. The total geographical area of Ananjiyur village is 330.79 Hectares / 3.3 KM2.
    The nearest police station is located in Madurai North tahsil.
</p>
</body>
</html>



<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="orange"><b>MADURAI</b></font>
</h1>
<h3 align="center">
<font color="green"><b>village-kinnimangalam</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Georgia" size="6">
    Kinnimangalam is a Village in Tirumangalam Block in Madurai District of Tamil Nadu State, India.
     It is located 16 KM towards west from District head quarters Madurai. 12 KM from Tirumangalam. 499 KM from State capital Chennai
</p>
</body>
</html>



<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="orange"><b>MADURAI</b></font>
</h1>
<h3 align="center">
<font color="white"><b>madurai airport</b></font>
</h3>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="6">
    Madurai International Airport (IXM)
    It is located approximately 12 kilometers from the railway station and was established in 1957. During the Second World War,
 the airport was used by the Royal Air Force.Primary passenger flight on the Madurai – Trivandrum – Madurai route flew in 1956.
</p>
</body>
</html>
```

## OUTPUT

![image](https://github.com/lakshman1206/NearMe/assets/129931784/80ace82e-648a-4af7-990b-f65a1cc85753)

![image](https://github.com/lakshman1206/NearMe/assets/129931784/ccec242a-27e4-4918-9216-08a89a571296)

![image](https://github.com/lakshman1206/NearMe/assets/129931784/96a63c64-11e1-43a5-b877-e08aa37dd26c)

![image](https://github.com/lakshman1206/NearMe/assets/129931784/d16677a2-62c8-4fc4-bbe9-774b167b2741)
## RESULT
The program for implementing image maps using HTML is executed successfully.
