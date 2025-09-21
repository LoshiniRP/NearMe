# Ex04 Places Around Me
## Date: 21.09.2025

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
        <title>MAP</title>
    </head>

    <body bgcolor="pink">
        <h1 align="center">CHENNAI - R P LOSHINI(25002119)</h1>
        <br>
        <img src="Screenshot 2025-09-20 141854.png" usemap="#image-map" title="My Hometown-Chennai">
        
        <map name="image-map">
            <area target="" alt="CHENNAI AIRPORT" title="CHENNAI AIRPORT" href="airport.html" coords="543,673,700,798" shape="rect">
            <area target="" alt="MARINA BEACH" title="MARINA BEACH" href="beach.html" coords="1492,272,1680,325" shape="rect">
            <area target="" alt="ITC GRAND CHOLA" title="ITC GRAND CHOLA" href="hotel.html" coords="1025,573,1251,633" shape="rect">
            <area target="" alt="VADAPALANI TEMPLE" title="VADAPALANI TEMPLE" href="temple.html" coords="1009,308,90" shape="circle">
            <area target="" alt="PHOENIX MARKETCITY" title="PHOENIX MARKETCITY" href="marketcity.html" coords="846,720,946,702,1064,723,1040,776,872,774" shape="poly">
        </map>
    </body>
</html>

airport.html

<html>
    <head>
        <title>AIRPORT</title>
    </head>
    <body bgcolor="tomato">
        <h1 align="center">CHENNAI AIRPORT</h1>
        <p>
            <font size="5">Chennai International Airport is an international airport serving 
                the city of Chennai, the capital of Tamil Nadu, India. It is located in 
                Tirusulam in Chengalpattu district, in the Greater Chennai Metropolitan Area 
                around 21 km (13 mi) southwest of the city centre. The first air service was 
                operated in 1915 and the airport was commissioned in 1930. The airport 
                serves as the southern regional headquarters of the Airports Authority of 
                India (AAI) for South India comprising the states of Andhra Pradesh, 
                Karnataka, Kerala, Tamil Nadu and Telangana, and the union territories of 
                Lakshadweep and Puducherry. The airport is the fifth-busiest airport in 
                India by passenger traffic and aircraft movements, and fourth-busiest by 
                cargo handled in India and international traffic. In the financial year 
                2024–25, the airport handled over 22 million passengers and 0.37 million 
                tonnes of cargo.</font>
        </p>
        <img src="Screenshot 2025-09-21 123256.png" width="700" height="400" title="Chennai Airport">
    </body>
</html>

beach.html

<html>
    <head>
        <title>BEACH</title>
    </head>
    <body bgcolor="powderblue">
        <h1 align="center">MARINA BEACH</h1>
        <p>
            <font size="5">Marina Beach, or simply the Marina, is a natural urban beach in 
                Chennai, Tamil Nadu, India, along the Bay of Bengal. The beach runs from 
                near Fort St. George in the north to Foreshore Estate in the south, a 
                distance of 6.0 km (3.7 mi), making it the second longest urban beach in 
                the world, after Cox's Bazar Beach. The Marina is a primarily sandy beach, 
                with an average width of 300 m (980 ft) and the width at the widest stretch 
                is 437 m (1,434 ft). Bathing and swimming at the Marina are legally 
                prohibited because of the dangers, as the undercurrent is very turbulent. 
                It is one of the most crowded beaches in the country and attracts about 
                30,000 visitors a day during weekdays and 50,000 visitors a day during the 
                weekends and on holidays. During summer months, about 15,000 to 20,000 
                people visit the beach daily.</font>
        </p>
        <img src="Screenshot 2025-09-21 123344.png" width="700" height="400" title="Marina Beach">
    </body>
</html>

hotel.html

<html>
    <head>
        <title>HOTEL</title>
    </head>
    <body bgcolor="olive">
        <h1 align="center">ITC GRAND CHOLA</h1>
        <p>
            <font size="5">The ITC Grand Chola is a 5-star luxury hotel in Chennai, India. 
                It is located in Guindy, opposite SPIC building and along the same row of 
                buildings as Ashok Leyland Towers. The building, designed by Singapore-based 
                SRSS Architects, is of mixed-use development with three separate wings and 
                is themed after traditional Dravidian architecture of the Chola dynasty. The 
                hotel is the ninth hotel in The Luxury Collection brand. The hotel, built on 
                over 1,600,000 sq ft, is dubbed the largest stand-alone hotel in the country 
                built with an investment of ₹ 12,000 million and has the largest convention 
                centre in the country built on 100,000 sq ft with a 30,000-sq ft pillar-less 
                ballroom. In terms of room inventory, with 600 rooms, it is the third largest 
                hotel in India after Renaissance Mumbai Convention Centre Hotel – now 
                rebranded as The Westin Mumbai Powai Lake (759 rooms) and Grand Hyatt 
                (694 rooms), both in Mumbai.</font>
        </p>
        <img src="Screenshot 2025-09-21 123504.png" width="700" height="400" title="ITC Grand Chola">
    </body>
</html>

marketcity.html

<html>
    <head>
        <title>MARKETCITY</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">PHOENIX MARKETCITY</h1>
        <p>
            <font size="5">Phoenix Marketcity is a shopping mall developed by Phoenix Mills 
                Limited located in Chennai, Tamil Nadu, India. It was opened in January 2013 
                and is the 2nd largest mall in the city. It was the fourth largest mall in 
                India in 2018. It has a built up area of 1,000,000 square feet. Also there 
                is a Palladium mall situated right next to it. This mall was jointly 
                developed by Phoenix Mills Limited and Crest Ventures Ltd. Phoenix Mall 
                Chennai is part of a development which includes a premium residential space 
                as part of Phase I. Phase II development includes a luxury mall called 
                Palladium and residential space. Phoenix Mall features an 11-screen 
                multiplex which is also Chennai's first IMAX screen. Palladium, the first 
                luxury and premium luxury retail and entertainment destination of Chennai, 
                was launched alongside Phoenix Marketcity as its second branch in the 
                country after the Mumbai one. It is also located in the same compound of 
                Phoenix Marketcity Chennai.</font>
        </p>
        <img src="Screenshot 2025-09-21 123425.png" width="700" height="400" title="Phoenix Marketcity">
    </body>
</html>

temple.html

<html>
    <head>
        <title>TEMPLE</title>
    </head>
    <body bgcolor="violet">
        <h1 align="center">VADAPALANI MURUGAN TEMPLE</h1>
        <p>
            <font size="5">Vadapalani Andavar Temple is a Hindu temple dedicated to Lord Muruga. 
                It is located in Vadapalani, Chennai, Tamil Nadu, India. It was renovated in the 
                1920s and a Rajagopuram was built during that time. The temple has grown in 
                popularity, which is believed to be in part due to the patronage of cinema 
                stars. The temple is built on the traditional lines of south Indian temples. 
                The Rajagopuram at the entrance has several stuccos with the legends of the 
                Skanda Purana depicted on them. The Moolavar (main deity) resembles the 
                Palani temple idol and is in standing position. The belief is very strong 
                here that people who cannot undertake the pilgrimage to the Palani temple 
                can visit the Vadapalani temple with their offerings. Palaniandavar showers 
                devotees with his blessings just the same as in Southern Palani. His grace 
                resolves all issues for devotees, and they believe in the power of this 
                sacred temple.</font>
        </p>
        <img src="Screenshot 2025-09-21 123532.png" width="700" height="400" title="Vadapalani Temple">
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (36).png>)
![alt text](<Screenshot (37).png>)
![alt text](<Screenshot (38).png>)
![alt text](<Screenshot (39).png>)
![alt text](<Screenshot (40).png>)
![alt text](<Screenshot (41).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
