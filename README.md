# Ex04 Places Around Me
## Date: 

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
```c
MAP.Html
<!DOCTYPE html>
<html>
    <head>
          <title>CUMBUM</title>
    </head>
    <body>
         <h1 align="center">
             <font face="algerian" color="GREEN"><b>CUMBUM,THENI DISTRICT</b></font>
        </h1>
        <h3 align="center"> <font face="algerian" color="RED"><b> AVINASH T (212223230026)</b></font></h3>
        <center><img src="cumbum.png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="DEVABALA &amp; SAKTHIBALA CINEMAS" title="DEVABALA &amp; SAKTHIBALA CINEMAS" href="CINEMAS.html" coords="937,503,825,557" shape="rect">
        <area target="" alt="JSD MAHAL " title="JSD MAHAL " href="MAHAL.html" coords="1006,125,37" shape="circle">
        <area target="" alt="HOTEL LEMURIAN HERITAGE" title="HOTEL LEMURIAN HERITAGE" href="HOTEL.html" coords="534,863,679,803" shape="rect">
        <area target="" alt="NAMMHSS MATRICULATION SCHOOL" title="NAMMHSS MATRICULATION SCHOOL" href="SCHOOL.html" coords="1175,440,68" shape="circle">
        <area target="" alt="THANGAMAYIL JEWELLERY" title="THANGAMAYIL JEWELLERY" href="COSMETICS.html" coords="802,586,711,544" shape="rect">
    </map>
        </center>
    </body>
</html
```
```c
SCHOOL.html

<html>
    <head>
        <title>SCHOOL</title>
    </head>
    <body bgcolor="SKYBLUE">
        <h1 align="center">
            <font face="algerian" color="BLACK"><b>NAMMHSS MATRICULATION SCHOOL</b></font>
        </h1>
        <h3 align="center">
            <font face="algerian" color="blue"><b>SCHOOL</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                <br>Nagamani Ammal Matriculation Higher Secondary School (NAMMHSS) in Cumbum, Tamil Nadu, was established in 1987 and is managed by the Pvt. Unaided sector. Located in an urban area, it falls within the Cumbum block of Theni district. The school offers education from Grades 1 to 12 and is co-educational, with an attached pre-primary section.</br>

                <br>Here are some key details about NAMMHSS Cumbum:</br>
                
                <br>Instruction Medium: English</br>
                <br>Total Teachers: 92 (19 male teachers and 73 female teachers)</br>
                <br>Pre Primary Teachers: 10</br>
                <br>Head Teacher: P. VIJAYALAKSHMI</br>
                <br>School Area: Urban</br>
                <br>School Building: Private building with 36 classrooms</br>
                <br>Library: Contains 3500 books</br>
                <br>Computer Facilities: 20 computers for teaching and learning purposes</br>
                <br>Computer Aided Learning Lab: Available</br>
                <br>Playground: Yes</br>
                <br>Toilets: 35 boys toilets and 15 girls toilets</br>
                <br>Drinking Water Source: Tap water</br>
                <br>Mid-day Meal: Not provided</br>
                <br>NAMMHSS Cumbum aims to provide quality education to its students, and its rich history and commitment to learning make it an important institution in the region. 🏫📚</br>
            </font>
        </p>
        </body>
        </html>
```
```c
COSMETICS.html

<html>
    <head>
        <title>COSMETICS</title>
    </head>
    <body bgcolor="GOLD">
        <h1 align="center">
            <font face="algerian" color="BLACK"><b>THANGAMAYIL JEWELLERY</b></font>
        </h1>
        <h3 align="center">
            <font face="algerian" color="blue"><b>PLACE OF GOLD</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
            <br> Cumbum Branch </br>
            Thangamayil Jewellery flagged off its renovated branch at a new location on Jan 27, 2021, which it established on June 20, 2011. Cumbum town is located in the Theni District of Tamil Nadu, bordering Kerala State. The name Cumbum has been derived from the famous temple of Lord Cumbaraya Perumal around which the town has been built. Viswanatha Nayak of Vijaya Nagara dynasty wanted to build a temple.

Cumbum town is located in the Theni District of Tamil Nadu, near Kerala State, It is the third largest town in Theni district after Theni and Bodinayakanur. The soil in this region is mostly red soil in nature. Agriculture plays on vital role for its developmental activities. Crops like Paddy, Coconut, Groundnut and various kinds of fruits and vegetables are being cultivated in this area.

<br>THANGAMAYIL JEWELLERS</br>
<br>CUMBUM</br>

<br>196, L.F. Near North Police Station,</br>
<br>CUMBUM TAMILNADU 625516</br>
<br>OPEN NOW : 10:00 AM – 09:00PM</br>

            </font>
        </p>
        </body>
        </html>>
```
```c
```

## OUTPUT





## RESULT
The program for implementing image maps using HTML is executed successfully.
