# Ex04 Places Around Me
## Date:05/04/2024

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
map.html
<html>
<head>
<title>Rohith T map</title>
</head>
<body align="center" bgcolor="lightblue">
<h1 align="center">
<font color="black"><b>Hosur (one of the chill city in tamil nadu)</b></font>
</h1>
<h3 align="center">
<font color="black"><b>-Rohith T (21222304o173)</b></font>
</h3>
<img src="map.png" usemap="#image-map">
<map name="image-map">
    <area target="" alt="hotel hills" title="hotel hills" href="hotel.html" coords="430,201,640,261" shape="rect">
    <area target="" alt="Ramee guestline" title="Ramee guestline" href="guestline.html" coords="333,27,518,93" shape="rect">
    <area target="" alt="dam" title="dam" href="dam.html" coords="693,133,894,201" shape="rect">
    <area target="" alt="memorial house" title="memorial house" href="memorial.html" coords="681,441,891,502" shape="rect">
    <area target="" alt="MJ avanya resot" title="MJ avanya resot" href="resort.html" coords="105,274,314,338" shape="rect">
</body>
</html>


resort.html
<html>
    <head>
        <title>Avanya resort</title>
    </head>
    <body bgcolor="red"><center>
        <h1>MJ avanya resot</h1>
        <hr>
        <br>
        <p>
            MJ Avyanna is a distinguished resort and convention center located in India, renowned for its luxurious offerings and exceptional hospitality. Situated amidst 6 acres of lush greenery, the resort is an oasis of opulence and comfort.
            Our commitment to providing bespoke services and an unforgettable experience sets us apart. From the moment you step onto our grounds, you're enveloped in a world of elegance and grandeur. Whether you're seeking a relaxing weekend escape, planning a destination wedding, hosting a corporate event, or celebrating a special occasion, MJ Avyanna caters to your every need.
        </p>
    </center>
    </body>
</html>

memorial.html
<html>
    <head>
        <title>Memorial</title>
    </head>
    <body bgcolor="gold"><center>
        <h1>Rajaji Memorial</h1>
        <hr>
        <br>
        <p>
            The Rajaji Memorial is located close to Hosur. This memorial was built in the village named Thorapalli to honour Chakravarthy Rajagopalachari, who was the first and the last Indian Governor General of India. Rajagopalachari was born in Thorapalli and is still revered in the area.  
        </p>
    </center>
    </body>
</html>

dam.html
<html>
    <head>
        <title>Dam</title>
    </head>
    <body bgcolor="blue"><center>
        <h1>Kelevarapalli Dam</h1>
        <hr>
        <br>
        <p>
            Kelavarapalli dam in Hosur recorded a water level of 40.02 ft against the total level of 44.28 ft. The storage level in the dam stood at 333.88 tmcft of the total 480.86 tmcft. The inflow was 340 cusecs and the same quantum of water was being released from the dam.
        </p>
    </center>
    </body>
</html>

guestline.html
<html>
    <head>
        <title>Guestline</title>
    </head>
    <body bgcolor="orange"><center>
        <h1>Ramee guestline</h1>
        <hr>
        <br>
        <p>
            It is a couple-friendly property, hence it is absolutely safe for unmarried couples to stay here. You can find numerous hotels in Mumbai under different categories and Ramee Guestline Khar is one the best hotel under its category. Also you can book Ramee Guestline Khar from our partner website MakeMyTrip.Com.  
        </p>
    </center>
    </body>
</html>

hotel.html
<html>
    <head>
        <title>Hotel</title>
    </head>
    <body bgcolor="pink"><center>
        <h1>Hotel Hills</h1>
        <hr>
        <br>
        <p>
            Best hotel located in the Hosur, beside the Bangalore — Chennai highway which is 70 kms drive from Kempegowda International Airport, Bengaluru and 40 kms drive from Majestic Railway Station,Bengaluru.
            The hotel welcomes you with its fresh interiors as well as crisp and clean rooms and delights you with its unbeatable value and reliable safety standards.
               
        </p>
    </center>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2024-04-05 093645.png>)
![alt text](<Screenshot 2024-04-05 092436.png>)
![alt text](<Screenshot 2024-04-05 092520.png>)
![alt text](<Screenshot 2024-04-05 092829.png>)
![alt text](<Screenshot 2024-04-05 093153.png>)
![alt text](<Screenshot 2024-04-05 093440.png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
