# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Open up a terminal in your preffered location, and start a django project using djang-admin startproject Next setup an app inside the project folder using django-admin startapp.

### Step 2:
Once Created ,link your app to the project by adding it in the list of apps in settings.py file located inside the project folder. Add access to your host in allowed host setting and add static folders path to your settings.py file.

### Step 3:
Create a static folder and template folder and add all your required files for the project - Images .etc in your static folder. In the Template folder add your html files required for the pages.

### Step 4:
Head to the views.py in your app folder and create required functions to render a particular page or template when requested by the client. Next go to the urls.py and route the correct view functions to each particular request as needed.

### Step 5:
Next start the server from the projects main directory using python3 manage.py runserver 0:. Now the pages can be accessed from all the routed addresses in urls.py.

### Code:

'''

NAME:Shashin prasad.S

REG NO:212222230144

'''
index.html

<!DOCTYPE html>
<html>
    <head>
        <title>
            Image Map
        </title>
    </head>
    <body >
        <h1 align="center" >
            <font color="red" >
                    SAVEETHA UNIVERSITY
            </font>


            
        </h1>
        <h3 align="center">
        <font color="blue">
           Shashin prasad.s(212222230144)
        </font>
            
        </h3>
        <center>
            <img src="/static/html/map1.jpeg" usemap="#image-map">
            <map name="image-map">
            <area target="_self" alt="sec" title="sec" href="sec.html" shape="rect" coords="634,437,684,487">
            <area target="_self" alt="scon" title="scon" href="scon.html" shape="rect" coords="382,450,437,511">
            <area target="_self" alt="sse" title="sse" href="sse.html" shape="rect" coords="973,111,1027,173"> 
            <area target="_self" alt="simats" title="simats" href="simats.html" shape="rect" coords="837,519,891,581">
            <area target="_self" alt="sca" title="sca" href="sca.html" shape="rect" coords="496,209,549,268">
            </map>




        </center>
        <p align="center">
            <font color="maroon"  face="Comic Sans MS" >
                This Image Map shows various locations around my home.<br>
                Click the location and get information about it.
            </font>
        </p>


    </body>
</html>

sec.html

<!DOCTYPE html>
<html>
    <head>
        <title>SEC</title>
    </head>
    <body bgcolor="yellow">
        <h1 align='center'>SAVEETHA ENGINEERING COLLEGE</h1>
        <center>
          <img src ="/static/html/sec.png"  height="300" width="600" align="center" >
        </center>
        <p style="font-size: 24px">
         Saveetha Engineering College (SEC) was established in 2001, by the Founder Chairman Dr. N. M. Veeraiyan, a committed and dedicated Medical Professional.SEC has a total strength of 4349 students in 15 UG courses, 8 PG Courses including MBA, MS by Research and Doctoral programs (PhD)  in five Departments.National Board of Accredition NBA has Accredited 5 UG courses.Ranked 96 by NIRF- National Institute Ranking Framework for the academic year 2017-18 among all IITs, Central, State and Private Institutions in India. Awarded 'A' GRADE with a high score of 3.19 on a scale of 4 by the National Assessment and Accreditation Council (NAAC) for 5 Years.SEC awarded AUTONOMOUS status by the UGC from the academic year 2019-2020. SEC is recognized as a Scientific and Industrial Research Organization (SIRO) by the Department of Scientific and Industrial Research (DSIR), Government of India.
</p>
    </body>

</html>

sse.html

<!DOCTYPE html>
<html>
    <head>
        <title>SSE</title>
    </head>
    <body bgcolor="green">
        <h1 align='center'>SAVEETHA SCHOOL OF ENGINEERING</h1>
        <center>
          <img src ="/static/html/sse.png"  height="300" width="600" align="center" >
        </center>
        <p style="font-size: 24px">
        Saveetha School of Engineering (SSE) Chennai, is a private institution, affiliated to AICTE, established in 2005, located in the Chennai city of Tamil Nadu state. It is accredited NAAC ‘A’ Grade and got recognition by 43rd rank in NIRF. SSE is one of the 80 universities around the globe which get the IET-UK Accreditation. The college promises for being one of the best engineering colleges in India by keeping high standards of quality education in engineering fields. Under Saveetha School of Engineering Admissions 2019, the college offers some full time Undergraduate, Postgraduate and Doctoral programs in many departments. Each department is enriched with experienced, dedicated and knowledgeable faculty members. With extra-ordinary infrastructure facilities and with innovative teaching methods like MILA, Flipped Classes, etc., SSE provides the best platform for the students to excel in their academics. 
</p>
    </body>

</html>

scon.html

<!DOCTYPE html>
<html>
    <head>
        <title>SCON</title>
    </head>
    <body bgcolor="pink">
        <h1 align='center'>SAVEETHA COLLEGE OF NURSING</h1>
        <center>
          <img src ="/static/html/scon.png"  height="300" width="600" align="center" >
        </center>
        <p style="font-size: 24px">
        Saveetha College of Nursing, Saveetha University with its heritage of excellence in nursing education for over 30 years. The Institute is committed to generating, disseminating, and preserving knowledge, and to working with others to bring this knowledge and care to bear on the world's great challenges. Saveetha College of Nursing is dedicated to providing its students with an education that combines rigorous academic study and the excitement of discovery with the support and intellectual stimulation of a diverse campus community.Our college has a 1200 bedded multi super specialty parent hospital, with modernized and highly equipped and highly professionalized clinical team. We seek to develop in each member of the Saveetha College of Nursing community the ability and passion to work wisely, creatively, and effectively for the betterment of humankind. Saveetha College of Nursing To be amongst the global leaders in education promoting innovation in nursing field and providing an atmosphere that promotes cross disciplinary interaction and research by students and faculty alike. We provide unique pedagogy that combines classroom education with hands on learning experience.
</p>
    </body>

</html>

simats.html

<!DOCTYPE html>
<html>
    <head>
        <title>SIMATS</title>
    </head>
    <body bgcolor="lightblue">
        <h1 align='center'>SAVEETHA INSTITUTE OF MEDICAL AND TECHNICAL SCIENCE </h1>
        <center>
          <img src ="/static/html/simats.png"  height="300" width="600" align="center" >
        </center>
        <p style="font-size: 24px">
        Saveetha Institute of Medical And Technical Sciences Chennai also known as SIMATS CHENNAI, is a Deemed to be University situated in Chennai, Tamil Nadu. SIMATS CHENNAI was established in the year 2005. Its campus is spread over 150 Acres of land. SIMATS CHENNAI is accredited by NAAC A. SIMATS CHENNAI offers admission in various courses like BA LLB (HONS.), BBA + LLB (H), BDS, BE, BOT, B.P.Ed, BPT, BSc, B.Tech, DIP DENT, DIP DH, DIP DM, FFESS,  LL.D., LLM + Ph.D, MBA , MBBS, M.CH, ME, M.Phil. (SCI), MPT, MS, PGDM, PhD Arts, Ph.D DENT, Ph.D. ENG, Ph.D MED, Ph.D (MGMT), Ph.D. (SCI). Various Facilities provided by SIMATS CHENNAI are Medical Support Systems, Gym, Sports Complex, Library & Information Center, Practical Lab, IT Centers, Auditorium, Canteen, Girls Hostel, Boys Hostel and etc. SIMATS CHENNAI is run by Saveetha Medical and Educational Trust

</p>
    </body>

</html>

sca.html

<!DOCTYPE html>
<html>
    <head>
        <title>SCA</title>
    </head>
    <body bgcolor="red">
        <h1 align='center'>SAVEETHA COLLEGE OF ARCHITECTURE</h1>
        <center>
          <img src ="/static/html/sca.png"  height="300" width="600" align="center" >
        </center>
        <p style="font-size: 24px">
            Saveetha College of Architecture and Design (SCAD), SIMATS is one of the premier Architecture institutes located in Chennai, Tamil Nadu. The Collegeis a constituent unit of Saveetha College of Medical and Technical Sciences (SIMATS). SCAD was set up with a vision to improve standards in Architecture education, promote high-quality research in the field and play a key role in constructing sustainable buildings. The Collegeoffers BArch as its only academic programme. With emphasis on practical experience, SCAD Chennai helps its students with innovative expression, research, critical thinking, and creative exploration. It has collaborations with popular international universities and has signed MoUs (Memorandums of Understanding) with Penn State University, Gachon University and several other international universities. SCAD provides opportunities to take credit courses and involve in trans-disciplinary projects from Medical, Dental and Engineering streams.
</p>
    </body>

</html>



## Output:
Include your output screenshot here

## Result:
Hence a website has been developed to display details about the colleges around saveetha university.