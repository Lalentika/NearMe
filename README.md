# Ex04 Places Around Me
## Date: 10.05.2025

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
home.html

<html>
<head>
  <title>My City</title>
</head>
<body>
  <h1 align="center">
    <font color="red"><b>Tambaram</b></font>
  </h1>

  <h3 align="center">
    <font color="black"><b>LALENTIKA TWISHA M (212224220052)</b></font>
  </h3>
<center>
    <img src="map.png" usemap="#MyCity" height="610" width="1450">
    <map name="MyCity">
      <area shape="rect" coords="700,250,850,400" href="home.html" title="Home">
      <area shape="circle" coords="570,230,45" href="road.html" title="Muduchur road">
      <area shape="circle" coords="640,200,30" href="lake.html" title="Tambaram Lake">
      <area shape="circle" coords="1120,360,25" href="garden.html" title="GG Garden">
      <area shape="rect" coords="950,120,1100,140" href="stop.html" title="Pallikarani">
    </map>
  </center>
</body>
</html>
```
```
garden.html

<html>
<head>
  <title>Garden</title>
</head>
<body bgcolor="blue">
  <h1 align="center">
    <font color="cyan"><b>Tambaram</b></font>
  </h1>
  <h3 align="center">
    <font color="lime"><b>GG Garden</b></font>
  </h3>
  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5" color="white">
        GG Garden in Tambaram is a peaceful residential area known for its calm surroundings.
        It offers easy access to schools, shops, and transport facilities, making life convenient.
        The neighborhood features clean streets, friendly communities, and a green environment.
        Ideal for families, GG Garden combines suburban charm with city connectivity. 
  </p>
</body>
</html>
```
```
lake.html

<html>
<head>
  <title>Lake</title>
</head>
<body bgcolor="blue">
  <h1 align="center">
    <font color="cyan"><b>Tambaram</b></font>
  </h1>
  <h3 align="center">
    <font color="lime"><b>Tambaram lake</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5" color="white">
      Lakes are generally formed as a consequence of the tectonic or glacial activity. 
      Lakes are also formed due to the meandering river or even by human activity. 
      For civilization, there are abundant reasons to point them out, this owes to the 
      resource of water, and water is a definite source to continue life on this planet. 
      This lake is also facing numerous problems such as pollution, siltation, and 
      climate change. 
  </p>
</body>
</html>
```
```
road.html

<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="green">
  <h1 align="center">
    <font color="gray"><b>Tambaram</b></font>
  </h1>
  <h3 align="center">
    <font color="blue"><b>MUDUCHUR ROAD </b></font>
  </h3>
  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">
      These Roads construction started at 2017 and successfully ended on 2023.
      These Roads are constructed by L&T . These Roads are know for it's pot holes and 
      number of accidents occuring.
    </font>
  </p>
</body>
</html>
```
```
stop.html

<html>
<head>
  <title>Pallikarani</title>
</head>
<body bgcolor="blue">
  <h1 align="center">
    <font color="cyan"><b>Tambaram</b></font>
  </h1>
<h3 align="center">
<font color="lime"><b>Pallikarani</b></font>
<hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">
        Pallikaranai is a neighborhood and a residential area in south Chennai, Tamil Nadu, India. Located in proximity to the IT industry in Old Mahabalipuram Road
    </font>
  </p>
</body>
</html>
```

## OUTPUT

![image](https://github.com/user-attachments/assets/63de0254-a4e7-4e42-ac32-ce650ff7ae34)

![Screenshot 2025-05-14 203546](https://github.com/user-attachments/assets/fb87462d-9d03-4e47-8818-b5901f0b6535)

![Screenshot 2025-05-14 203601](https://github.com/user-attachments/assets/686bf603-6577-4228-b7fb-37797d6122fc)

![Screenshot 2025-05-14 203615](https://github.com/user-attachments/assets/e9f8cd75-ddde-437e-a439-7f4437a8727d)

![Screenshot 2025-05-14 203629](https://github.com/user-attachments/assets/c6ecb44e-9124-4dcf-8c74-03f891ae8349)



## RESULT
The program for implementing image maps using HTML is executed successfully.
