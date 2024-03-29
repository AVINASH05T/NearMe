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
HOTEL.html

<html>
    <head>
        <title>HOTEL</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font face="algerian" color="BLACK"><b>LEMURIAN HERITAGE</b></font>
        </h1>
        <h3 align="center">
            <font face="algerian" color="blue"><b>PLACE OF PEACE</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
            <br>Hotel Lemurian Heritage in Cumbum, Tamil Nadu, India, is a charming retreat that offers a blend of comfort, culture, and natural beauty. Let’s explore what this heritage hotel has to offer:</br>

            <br>Location and Ambience:</br>
            Hotel Lemurian Heritage is situated at 145, Kumily Road, Cumbum, 625516.
            The hotel boasts a serene and picturesque setting, surrounded by lush greenery and rolling hills.
            <br>Accommodations:</br>
            The rooms are well-appointed and comfortable, providing a peaceful escape for guests.
            Some rooms feature blackout curtains, soundproofing, air conditioning, and coffee/tea makers.
            <br>Amenities:</br>
            Swimming Pool: Guests can take a refreshing dip in the hotel’s swimming pool.
            Free High-Speed Internet: Stay connected during your visit.
            <br>Coffee Shop: Enjoy a cup of coffee or tea in a cozy setting.</br>
            <br>Fishing: For those who love angling, the hotel offers fishing facilities.</br>
            <br>Airport Transportation: Convenient options for travelers arriving by air.</br>
            <br>Meeting Rooms: Ideal for business meetings or events.</br>
            <br>24-Hour Security: Ensures a safe and secure stay.</br>
            <br>Nearby Attractions:</br>
            <br>Suruli Falls: Approximately 7.8 km away, this scenic waterfall is a must-visit.</br>
            <br>MSR Grapes Garden: Explore this beautiful vineyard just 2.8 km from the hotel.</br>
            <br>Kodi Lingam Temple: A religious site located 6.4 km away.</br>
            <br>Guest Reviews:</br>
            Visitors have praised the hotel’s appearance, cleanliness, and friendly staff.
            Families appreciate the swimming pool, and overall, it’s considered a good place to stay.
            
            <br>Whether you’re seeking relaxation, cultural exploration, or a nature retreat, Hotel Lemurian Heritage offers a delightful experience in the heart of Cumbum. 🌿🏨</br>

            </font>
        </p>
        </body>
        </html>>
```
```c
CINEMAS.html

<html>
    <head>
        <title>CINEMAS</title>
    </head>
    <body bgcolor="ORANGE">
        <h1 align="center">
            <font face="algerian" color="BLACK"><b>DEVABALA&SHAKTHIBALA</b></font>
        </h1>
        <h3 align="center">
            <font face="algerian" color="blue"><b>WORLD OF CINEMAS</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                In Cumbum, there are two notable cinemas: Deva Bala Sakthi Bala Cinemas and Thambis Theatre A/C Dolby Atmos. Let’s take a closer look at each of them:

                <br>Deva Bala Sakthi Bala Cinemas A/C Dolby Atmos:</br>
                <br>Location: No. 2 Mani Nagaram, Cumbum, Tamil Nadu 625516, India.</br>
                <br>Features: This cinema offers the latest movie releases in a comfortable atmosphere with Dolby Atmos sound technology. It’s a great place for film enthusiasts to enjoy their favorite movies.</br>
                <br>Upcoming Shows: You can check the show timings and book tickets for movies like “Manjummel Boys” (Malayalam) and “Guardian” (Tamil) 1.</br>
                <br>Booking: You can book your tickets for Deva Bala Sakthi Bala Cinemas A/C Dolby Atmos in Cumbum through Ticketnew or Paytm.</br>
                <br>ANOTHER CINEMAS NEAR JSD MAHAL: Thambis Theatre A/C Dolby Atmos:</br>
                <br>Location: Cumbum (specific address not provided).</br>
                <br>Features: Thambis Theatre offers movie screenings with Dolby Atmos technology. It’s a great place to catch the latest films in a comfortable setting 2.</br>
                <br>Both cinemas provide entertainment options for moviegoers in Cumbum. Whether you’re interested in regional films or international releases, these theaters offer a cinematic experience worth exploring.</br>

            </font>
        </p>
        </body>
        </html>
```
```c
MAHAL.html

<html>
    <head>
        <title>JSD MAHAL</title>
    </head>
    <body bgcolor="lightgreen">
        <h1 align="center">
            <font face="algerian" color="RED"><b>JSD MAHAL</b></font>
        </h1>
        <h3 align="center">
            <font face="algerian" color="blue"><b>MAHAL-TOWN'S PRIDE</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
            JSD Mahal in Cumbum, Tamil Nadu, is a limited-service property that offers a comfortable stay for travelers. Here are some details about JSD Mahal:
            <br>Location: LF Main Road, Cumbum, Tamil Nadu, India.</br>
            <br>Rooms: The property features 20 air-conditioned cozy rooms.</br>
            <br>Amenities:</br>
                    <br>*Complimentary breakfast</br>
                    <br>*Free Wi-Fi access.</br>
                    <br>*Doctor on call.</br>
                    <br>*In-room dining facilities.</br>
                    <br>*Multi-cuisine restaurant.</br>
                    <br>*Mini fridge in every room.</br>
                    <br>*Underground spacious car parking.</br>
           <br> Whether you’re exploring the nearby attractions like Ramakkalmedu or Suruli Falls, JSD Mahal provides a convenient base for your stay in Cumbum. Enjoy the cozy rooms, delicious meals, and warm hospitality during your visit! 🏨🌟</br>

            </font>
        </p>
        </body>
        </html>
```

## OUTPUT
![alt text](<Screenshot 2024-03-26 143342.png>)
![alt text](<Screenshot 2024-03-26 143510.png>)
![alt text](<Screenshot 2024-03-26 143617.png>)
![alt text](<Screenshot 2024-03-26 143638.png>)
![alt text](<Screenshot 2024-03-26 143830.png>)
![alt text](<Screenshot 2024-03-26 143923.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
