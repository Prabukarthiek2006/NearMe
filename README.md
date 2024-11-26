# Ex04 Places Around Me
## Date: 13-11-2024

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
        <style>
            body{
                background-color: black;
            }
            header{
                text-align: center;
                color:crimson;
                background-color:burlywood;
                font-size: 50px;
            }
        </style>
    </head>
    <body>
        <header>
            <font><b>SALEM CITY</b></font></header>
        <h3 align="center">
            <font color="white"><b>PRABU KARTHIEK (24010663)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#Mycity" width="1394" height="750"> </center>
            <map name="Mycity">
                <area target="" alt="GANDHI STADIUM" title="GANDHI STADIUM" href="stadium.html" coords="674,389,814,459" shape="rect">
                <area target="" alt="ANNA PARK" title="ANNA PARK" href="park.html" coords="512,346,659,404" shape="rect">
                <area target="" alt="LONDON ORTHO HOSPITAL" title="LONDON ORTHO HOSPITAL" href="london.html" coords="370,429,531,502" shape="rect">
                <area target="" alt="NALAM HOSPITAL" title="NALAM HOSPITAL" href="nalan.html" coords="70,583,221,647" shape="rect">
                <area target="" alt="YMCA" title="YMCA" href="ymca.html" coords="1075,603,1224,670" shape="rect">
            </map>
        
        
    </body>
</html>

<style>
    body{
        background-color: black;
    }
    header{
        text-align: center;
        color:crimson;
        background-color:burlywood;
        font-size: 50px;
    }
    p{
        color: white;
        font-size: 30px;
    }
</style>
<body>
    <header>
        <font><b>GANDHI STADIUM</b></font></header>
        <center>
            <img src="c:\Users\admin\Downloads\gandhi stadium.jpg"  width="400" height="400"> </center>
            <p>Mahatma Gandhi Stadium in Salem, Tamil Nadu, is a prominent sports and cultural venue in the city. It is primarily known for hosting cricket matches, athletics events, and various cultural programs. The stadium is named in honor of Mahatma Gandhi, the leader of India's independence movement, symbolizing values of peace, unity, and perseverance.

                The venue has a rich history of hosting regional and national sports events, serving as a hub for local athletes and sports enthusiasts. It also plays a role in the community, providing a space for public events, concerts, and other social gatherings. With its central location and significant infrastructure, Mahatma Gandhi Stadium holds an important place in Salem's sporting and cultural landscape.</p>
</body>

<style>
    body{
        background-color: black;
    }
    header{
        text-align: center;
        color:crimson;
        background-color:burlywood;
        font-size: 50px;
    }
    p{
        color: white;
        font-size: 30px;
    }
</style>
<body>
    <header>
        <font><b>ANNA PARK</b></font></header>
        <center>
            <img src="c:\Users\admin\Downloads\anna.jpg"  width="350" height="350"> </center>
            <p>Anna Park in Salem, Tamil Nadu, is a well-known public park that offers a peaceful retreat for locals and visitors alike. Located centrally in the city, it is named after former Chief Minister of Tamil Nadu, C.N. Annadurai, often referred to as "Anna," a leader highly revered for his contributions to Tamil culture and politics. The park is a popular spot for morning walkers, families, and tourists, featuring well-maintained gardens, pathways, and recreational areas.

                It also houses a statue of C.N. Annadurai, making it not only a place for relaxation but also a historical and cultural landmark. Anna Park is often used for events, exhibitions, and cultural programs, contributing to the community’s social and cultural life. Its calm ambiance and green spaces make it an ideal location for leisure, outdoor activities, and enjoying nature in the heart of Salem.</p>
</body>

<style>
    body{
        background-color: black;
    }
    header{
        text-align: center;
        color:crimson;
        background-color:burlywood;
        font-size: 50px;
    }
    p{
        color: white;
        font-size: 30px;
    }
</style>
<body>
    <header>
        <font><b>LONDON ORTHO HOSPITAL</b></font></header>
        <center>
            <img src="c:\Users\admin\Downloads\london ortho.jpg"  width="350" height="350"> </center>
            <p>London Ortho Hospital in Salem, Tamil Nadu, is a specialized healthcare facility focused on orthopedic care and treatments. Known for its expertise in diagnosing and treating musculoskeletal conditions, the hospital offers a range of services, including joint replacement surgeries, fracture care, spinal treatments, and sports medicine. The hospital is equipped with modern medical technology and a team of experienced orthopedic surgeons and healthcare professionals.

                London Ortho Hospital is recognized for its patient-centric approach, providing personalized care and rehabilitation services to help patients recover and regain mobility. With its focus on advanced orthopedic procedures and a commitment to high-quality healthcare, the hospital has become a trusted name for patients seeking reliable orthopedic treatment in Salem and the surrounding region.
                
                
                
                </p>
</body>

<style>
    body{
        background-color: black;
    }
    header{
        text-align: center;
        color:crimson;
        background-color:burlywood;
        font-size: 50px;
    }
    p{
        color: white;
        font-size: 30px;
    }
</style>
<body>
    <header>
        <font><b>NALAM HOSPITAL</b></font></header>
        <center>
            <img src="c:\Users\admin\Downloads\nalam.jpg"  width="350" height="350"> </center>
            <p>Nalam Hospital in Salem, Tamil Nadu, is a reputed healthcare institution that specializes in offering a wide range of medical services. Known for its patient-centered care, the hospital provides treatment across various departments including general medicine, surgery, gynecology, pediatrics, orthopedics, and more. With a team of experienced doctors and medical staff, Nalam Hospital has built a strong reputation for delivering high-quality healthcare services to the local community.

                The hospital is equipped with modern medical technology and facilities, which enables it to offer effective diagnostic, therapeutic, and surgical treatments. It is also known for its compassionate approach to patient care, making it a trusted name in Salem for both routine medical needs and emergency services. Nalam Hospital strives to combine expertise with a caring environment, ensuring that patients receive the best possible treatment and support.</p>
</body>

<style>
    body{
        background-color: black;
    }
    header{
        text-align: center;
        color:crimson;
        background-color:burlywood;
        font-size: 50px;
    }
    p{
        color: white;
        font-size: 30px;
    }
</style>
<body>
    <header>
        <font><b>YMCA PROGRAM CENTER</b></font></header>
        <center>
            <img src="c:\Users\admin\Downloads\ymca.jpg"  width="350" height="350"> </center>
            <p>The YMCA Program Center in Salem, Tamil Nadu, is a community-focused facility that offers a wide range of programs aimed at promoting social, cultural, and educational development. As part of the larger YMCA (Young Men's Christian Association) organization, the center plays a vital role in fostering community engagement, youth empowerment, and health & wellness in the region.

                The YMCA Program Center in Salem organizes various activities such as sports, fitness training, leadership development, vocational training, and cultural events. It also hosts social service programs aimed at supporting underprivileged communities. The center's emphasis on holistic development encourages individuals of all ages to participate, learn new skills, and engage in recreational and fitness activities. Through its inclusive approach, the YMCA Program Center serves as an important hub for community-building and personal growth in Salem.</p>
</body>
```

## OUTPUT
![alt text](<Screenshot 2024-11-26 081204.png>)
![alt text](<Screenshot 2024-11-26 093633.png>)
![alt text](<Screenshot 2024-11-26 093709.png>)
![alt text](<Screenshot 2024-11-26 093650.png>)
![alt text](<Screenshot 2024-11-26 093727.png>)
![alt text](<Screenshot 2024-11-26 093740.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
