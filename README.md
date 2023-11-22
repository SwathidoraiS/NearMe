# Ex04 Places Around Me
## Date: 20.11.2023

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
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="black"><b>Puducherry</b></font>
</h1>
<h3 align="center">
<font color="red"<b>Swathi S (23013673)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="900,220,1000,300" href="home.html" title="My Home Town">
<area shape="circle" coords="1150,600,50" href="beach.html" title="Pondy marinaa">
<area shape="circle" coords="1250,290,50" href="ashram.html" title="Sir Aurobindo ashram">
<area shape="circle" coords="1100,400,50" href="garden.html" title="Botanical Garden">
<area shape="circle" coords="1200,390,25" href="town.html" title="White Town">
</map>
</center>
</body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
<body bgcolor="yellow">
<h1 align="center">
<font color="Blue"><b>Puducherry</b></font>
</h1>
<h3 align="center">
<font color="Red"><b>Pondicherry</b></font>
</h3>
<hr size="3" color="Black">
<p align="justify">
<font face="Georgia" sixe="5"><color="white">
The Union Territory of Puducherry comprises the former French establishments of  Puducherry,
 Karaikal, Mahe and Yanam, which lie scattered in South India. Puducherry, the capital 
 of the Territory was once the original headquarters of the French in India, is situated on
the Coromandel Coast of the Bay of Bengal and is about 135 kms. from Chennai Airport. It
is bounded on the east by the Bay of Bengal and on the three sides by Tamil Nadu. About 130 kms.
south of Puducherry on the East Coast lies Karaikal. Mahe is situated on the Malabar coast on the Western
 Ghats surrounded by Kerala and is about 70 kms. from Calicut Airport. Yanam is situated adjoining
 the East Godavari district of Andhra Pradesh and is about 200 kms. from Visakhapatnam Airport. The main 
  languages spoken here are Tamil, Telugu, Malayalam, English and French.
</font>
</p>
</body>
</html>


beach.html

<html>
<head>
<title>My Home Town</title>
<body bgcolor="purple">
<h1 align="center">
<font color="pink"><b>Puducherry</b></font>
</h1>
<h3 align="center">
<font color="red"><b>Pondy marinaa</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" sixe="5">color="white">
Pondy Marina Beach in Pondicherry is the new tourist attraction near the new lighthouse.
 It was developed under the theme-based beaches programs by the Pondicherry government,
 and “Pondy Marina” beach is based on a food-based theme.They offer horse and camel riding
 on sandy beaches and ATV rides for adventure seekers. They have an adventure activity zone
 behind the food court, where many rides are there for kids and adults alike. They have a big
 open lawn to conduct parties and conferences. Having a party next to the beach with all the facilities will be fun.
</font>
</p>
</body>
</html>

ashram.html

<html>
<head>
<title>My Home Town</title>
<body bgcolor="green">
<h1 align="center">
<font color="Brown"><b>Puducherry</b></font>
</h1>
<h3 align="center">
<font color="Red"><b>Sri Auroboindo ashram</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" sixe="5">color="white">
The Ashram is located in the eastern part of Pondicherry. Inmates live and work 
in a number of buildings spread throughout the area. The focus of community life 
is the Ashram main building, usually called simply "the Ashram", which consists of an
 interconnected block of houses, including those in which Sri Aurobindo and the Mother 
lived for most of their lives. At its centre, in a tree-shaded courtyard, lies the Samadhi,
 a white marble shrine where their bodies are laid to rest.
</font>
</p>
</body>
</html>

 garden.html

<html>
<head>
<title>My Home Town</title>
<body bgcolor="Yellow">
<h1 align="center">
<font color="Blue"><b>Puducherry</b></font>
</h1>
<h3 align="center">
<font color="red"><b>Botanical Garden</b></font>
</h3>
<hr size="3" color="Black">
<p align="justify">
<font face="Georgia" sixe="5">color="white">
The Botanical Garden was established by the French in 1826, 
however mention of it has been made in 1740 itself. The main
 purpose of the Botanical Garden at that time was to study the
 performance of various cultivable plants and to identify suitable
 plants based on their adoptability to the agro-climatic conditions 
of Puducherry. In the year 1829 a vast collection of eight to nine hundred 
species were grown in an area of 7500 square meters was reported by the famous traveler Victor Jacquemont.
</font>
</p>
</body>
</html>
 
 town.html

 <html>
<head>
<title>My Home Town</title>
<body bgcolor="Pink">
<h1 align="center">
<font color="Blue"><b>Puducherry</b></font>
</h1>
<h3 align="center">
<font color="Red"><b>white town</b></font>
</h3>
<hr size="3" color="Black">
<p align="justify">
<font face="Georgia" sixe="5"><color="white">
Known as the French Colony of Pondicherry, White Town is a residential area in town
 which boasts of an interwoven culture of the Tamils and the primal French families.
  Flaunting cobblestone streets and mustard yellow houses, the colony retains the old 
  world charm, daintiness and also the architecture of ancient French Quarters. Most of these
   have been converted into heritage hotels, restaurants, quirky cafes and art galleries. The
    buildings are mostly painted in pale yellow colour or shades of it and the well paved clean pathways 
    are lined with shady trees.
Known to be the former headquarters of the French, White Town is borrows a lot from the foreign 
culture, which is also the highlight of the place. In addition to that, it is known for its elegant but expensive
 market which mostly comprises of boutiques, high-end brands and personalized goods’ stores. Most of these stores 
 are still run by French nationalists. Besides, you can also find home decor and antique furniture shops here.
</font>
</p>
</body>
</html>


```

## OUTPUT

![Alt text](<Screenshot (23).png>)
![Alt text](<Screenshot (29).png>)
![Alt text](<Screenshot (27).png>)
![Alt text](<Screenshot (26).png>)
![Alt text](<Screenshot (31).png>)
![Alt text](<Screenshot (25).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
