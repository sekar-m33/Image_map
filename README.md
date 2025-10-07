# Ex04 Places Around Me
# Date:05/10/2025
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
image.html

<html>
<head>
<title>My city</title>
</head>
<body>
<h1 align ="centre">
<front colour="red"><b>Tiruvallur</b></front>
</h1>
<h3 align="centre">
<front colour="blue"><b>Sekar M (25017565)</b></front>
</h3>
<center>
<img src="image.jpg" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Thiruttani" title="Thiruttani" href="thiruttani.html" coords="632,653,456,573" shape="rect">
    <area target="" alt="arakkonam" title="arakkonam" href="arakkonam.html" coords="547,747,786,818" shape="rect">
    <area target="" alt="sholinghur" title="sholinghur" href="sholinghur.html" coords="281,784,86,707" shape="rect">
    <area target="" alt="nagari" title="nagari" href="nagari.html" coords="410,261,521,344" shape="rect">
    <area target="" alt="puttur" title="puttur" href="puttur.html" coords="348,27,456,95" shape="rect">
</map>
</center>
</body>
</html>

thiruttani.html

<html>
<head>
<title>thiruttani</title>
</head>
<body bgcolor="purple">
<h1 align ="centre">
<front colour="red"><b>thiruttani</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="thiruttani" size="5">
    Thiruthani is a peaceful town located in the Tiruvallur District of Tamil Nadu. It is famous for the Arulmigu Subramanya Swamy Temple, one of the six abodes of Lord Murugan. The temple stands on a hill with 365 steps, representing the days of the year, and attracts thousands of devotees every year. The town is surrounded by scenic hills and has a calm spiritual atmosphere.

</font>
</p>
</body>
</html>

arakkonam.html

<html>
<head>
<title>arakkonam</title>
</head>
<body bgcolor="skyblue">
<h1 align ="centre">
<front colour="red"><b>arakkonam</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="arakkonam" size="5">
    Arakkonam, another important town in Tiruvallur District, is well known for its large railway junction, one of the oldest in South India. It also has an Indian Air Force base and several industries. Arakkonam acts as a connecting hub between Chennai, Bengaluru, and Tirupati. The town reflects a blend of modern development and traditional Tamil culture.

</font>
</p>
</body>
</html>

sholinghur.html

<html>
<head>
<title>sholinghur</title>
</head>
<body bgcolor="pink">
<h1 align ="centre">
<front colour="red"><b>sholinghur</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="sholinghur" size="5">
    Sholinghur, located near Arakkonam, is a famous pilgrim town known for the Yoga Narasimha Swamy Temple. The temple is situated on a 750-foot hill and is reached by climbing over 1,300 steps. It is believed that Lord Vishnu appeared here as Yoga Narasimha to bless devotees with peace and wisdom. The town is surrounded by natural beauty and provides a quiet, spiritual experience for visitors.


</font>
</p>
</body>
</html>

nagari.html

<html>
<head>
<title>nagari</title>
</head>
<body bgcolor="green">
<h1 align ="centre">
<front colour="red"><b>nagari</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="nagari" size="5">
    Nagari, situated in the Chittoor District of Andhra Pradesh, lies close to the Tamil Nadu border. It is best known for the Nagari Hills and the unique rock formation called “Nagari Nose,” which resembles a human nose. The town has a mix of Tamil and Telugu culture and is popular among nature lovers and trekkers for its scenic beauty and hill views.


</font>
</p>
</body>
</html>

puttur.html

<html>
<head>
<title>puttur</title>
</head>
<body bgcolor="yellow">
<h1 align ="centre">
<front colour="red"><b>puttur</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="puttur" size="5">
     Puttur, also in Chittoor District, is famous for its traditional bone-setting hospital known as the Puttur Kattu. It is a busy commercial town located between Chennai and Tirupati. Surrounded by green hills and farmlands, Puttur is known for its natural healing methods and warm local culture. The people here speak both Tamil and Telugu, showing a rich blend of two traditions.


</font>
</p>
</body>
</html>
```

# OUTPUT

![alt text](<Screenshot 2025-10-05 220939.png>) 
![alt text](<Screenshot 2025-10-05 221007.png>) 
![alt text](<Screenshot 2025-10-05 221028.png>) 
![alt text](<Screenshot 2025-10-05 221052.png>) 
![alt text](<Screenshot 2025-10-05 221102.png>) 
![alt text](<Screenshot 2025-10-05 221112.png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
