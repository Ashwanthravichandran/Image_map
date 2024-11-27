# Ex04 Places Around Me
# Date:27-11-2024
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
    <body>
        <h1 align="center">
            <font color="red"><b>NAMAKKAL</b></font>
            </h1>
            <h2 align="center">
                <b>
                    ASHWANTH R(24900175)
                </b>
            </h2>
            <h3 align="center">



        <img src="nklmap.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Namakkal Sree Anjaneyar Temple" title="Namakkal Sree Anjaneyar Temple" href="temple.html" coords="251,449,37" shape="circle">
    <area target="" alt="Namakkal Fort" title="Namakkal Fort" href="fort.html" coords="516,481,20" shape="circle">
    <area target="" alt="KS Cineplex" title="KS Cineplex" href="theatre.html" coords="357,75,35" shape="circle">
    <area target="" alt="Namakkal Bus Stand" title="Namakkal Bus Stand" href="busstand.html" coords="757,648,33" shape="circle">
    <area target="" alt="Amma Unavagam" title="Amma Unavagam" href="unavagam.html" coords="614,705,26" shape="circle">
</map>
    </body>
</html>

busstand.html

<html>
<body>
    <h1 align="center">
        <font color="red">
            NAMAKKAL
        </font>
    </h1>
    <h2 align="center">
        NAMAKKAL BUS STAND 
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="busstand.jpg"height="400"width="600" >
        </center>
        <br>
        <hr>
        <li>
            <font size="3">
                The Namakkal New Bus Stand that was inaugurated by Chief Minister M.K. Stalin a few weeks ago was thrown open to the public on Sunday and buses started using the bus stand.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                The Chief Minister inaugurated the new bus stand, constructed at ₹19.50 crore at Mudalaipatti on October 22.Officials of the Tamil Nadu State Transport Corporation (TNSTC) said that all the mofussil buses were operated from the new bus stand. A digital board displayed at the bus stand had details of the arrival and departure of buses.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                For the benefit of passengers, bus shelters would come up on Anna Road, Coastal Road, and Vallipuram Road. A few shops in the bus stand were also opened on Sunday.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                All town buses plying between Old Bus Stand and Rasipuram would enter the new bus stand. Between the old bus stand and the new bus stand, a government or private bus was operated every 10 minutes and the fare was ₹7 in town and mofussil buses and ₹10 in express buses.
            </font>
        </li>
    </h3>
</body>

</html>

fort.html

<html>
<body>
    <h1 align="center">
        <font color="red">
            NAMAKKAL
        </font>
    </h1>
    <h2 align="center">
        NAMAKKAL FORT 
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="fort.jpg"height="400"width="600" >
        </center>
        <br>
        <hr>
        <li>
            <font size="3">
                Namakkal Fort is a historic fort present in Namakkal in Namakkal district in the South Indian state of Tamil Nadu. The fort was built during the reign of Thirumalai Nayak of Madurai in 17th century.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                It was under the dominion of Tipu Sultan and then switched hands to the British East India Company as a part of Srirangapattinam treaty. The fort was used as a watch tower and garrison by the ruling empire.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                The fort is located on the top of a hillock made of a single rock, 75 m (246 ft) tall. There is a temple and a mosque that are located within the fort, both of which are popular tourist attractions of the town.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                In modern times, the fort is under the control of the Archaeological Department of the Government of Tamil Nadu.
            </font>
        </li>
    </h3>
</body>

</html>

temple.html

<html>
<body>
    <h1 align="center">
        <font color="red">
            NAMAKKAL
        </font>
    </h1>
    <h2 align="center">
        NAMAKKAL SREE ANJANEYAR TEMPLE 
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="temp.jpg" height="400"width="600">
        </center>
        <br>
        <hr>
        <li>
            <font size="3">
                Namakkal Anjaneyar temple is located in Namakkal, a town in Namakkal district in Tamil Nadu, India and is dedicated to the Hindu god Hanuman. It is constructed in the Tamil style of architecture. 
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                The legend of the temple is associated with Narasimha, an avatar of Hindu god Vishnu appearing for Hanuman and Lakshmi. The image of Anjaneyar is 18 ft (5.5 m) tall, making it one of the tallest images of Hanuman in India. The temple follows the Vaikhanasa tradition.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                The temple has a pillared hall leading to the sanctum. Four daily rituals and many yearly festivals are held at the temple, of which fifteen-day Panguni Uthiram festival celebrated during the Tamil month of Panguni (March - April) when the image of presiding deities are taken around the streets of the temple, being the most prominent.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                The temple is maintained and administered by the Hindu Religious and Charitable Endowments Department of the Government of Tamil Nadu.
            </font>
        </li>
    </h3>
</body>

</html>

thearte.html

<html>
<body>
    <h1 align="center">
        <font color="red">
            NAMAKKAL
        </font>
    </h1>
    <h2 align="center">
        NAMAKKAL KS CINEPLEX 
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="thearte.jpg" height="422" width="512" >
        </center>
        <br>
        <hr>
        <li>
            <font size="3">
                A cineplex is a multiplex, a movie theatre with several screens, coming from the words cinema and complex.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                Theatre or theater is a collaborative form of performing art that uses live performers, usually actors or actresses, to present experiences of a real or imagined event before a live audience in a specific place, often a stage.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                Modern Western theatre comes, in large measure, from the theatre of ancient Greece, from which it borrows technical terminology, classification into genres, and many of its themes, stock characters, and plot elements
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                A theatre company is an organisation that produces theatrical performances, as distinct from a theatre troupe (or acting company), which is a group of theatrical performers working together.
            </font>
        </li>
    </h3>
</body>

</html>

unavagam.html

<html>
<body>
    <h1 align="center">
        <font color="red">
            NAMAKKAL
        </font>
    </h1>
    <h2 align="center">
        NAMAKKAL AMMA UNAVAGAM 
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="unavagam.jpg"height="400"width="600" >
        </center>
        <br>
        <hr>
        <li>
            <font size="3">
                Amma Unavagam (Tamil: அம்மா உணவகம்) is a food subsidisation programme run by the Ministry of Food and Civil Supplies, Government of Tamil Nadu in India.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                Under the scheme, municipal corporations of the state-run canteens serving subsidised food at low prices.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                The genesis of the scheme could be traced to the concept of rural restaurants promoted by Nimbkar Agricultural Research Institute.
            </font>
        </li>
        <br>
        <li>
            <font size="3">
                The literal meaning of the name of the scheme Amma Unavagam is Mother's canteen. Amma translates to mother in Tamil, but is also a reference to the former chief minister of Tamil Nadu J. Jayalalithaa, who introduced this restaurant chain as part of government schemes aimed at aiding economically disadvantaged sections of society
            </font>
        </li>
    </h3>
</body>

</html>

```
# OUTPUT
![alt text](<Screenshot (8).png>)
![alt text](<Screenshot (13).png>)
![alt text](<Screenshot (11).png>)
![alt text](<Screenshot (10).png>)
![alt text](<Screenshot (9).png>)
![alt text](<Screenshot (12).png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
