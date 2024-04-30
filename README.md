# Ex04 Places Around Me
## Date: 04-04-2024
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
create 'ex04'directory
### Step 2:
create project'myproj' using "django-admin startproject myproj"
### step 3:
create myapp using 'python3 manage.py startapp myapp'
### step 4:
create image map using image maps.com
### step 5:
create neccessary webpages for the places on the map
### step 6:
push to README.md and push to Github repository
## Code:
```
map.html

<!DOCTYPE html>
<html>
    <head>
        <title>KADAPA</title>

    </head>
    <body>
        <h1 align="center">
            <font color="RED"><b>KADAPA,KADAPA DISTRICT</b></font>
        </h1>
        <h3 align="center"><font color="blue"><b>P.REVANTH(212223040143)</b></font></h3>

       <center><img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Maruthi Theater" title="Maruthi Theater" href="cinema.html" coords="584,307,767,346" shape="rect">
    <area target="" alt="shilparamam" title="shilparamam" href="shilparamam.html" coords="1325,56,1478,134" shape="rect">
    <area target="" alt="Rani Thopu" title="Rani Thopu" href="rani thopu.html" coords="544,661,415,610" shape="rect">
    <area target="" alt="Loyola Polytechnic College" title="Loyola Polytechnic College" href="college.html" coords="1161,507,1356,585" shape="rect">
    <area target="" alt="Dr YS Rajasekhar Reddy Statue" title="Dr YS Rajasekhar Reddy Statue" href="statue.html" coords="174,633,375,677" shape="rect">
</map>
       </center> 
    </body>
</html>

cinema.html

<html>
    <head>
        <title>CINEPLEX</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
            <font color="red"><b>Maruthi Theater</b></font>
        </h3>
        <hr size="10" color="black">
        <p align="justify">
            <font face="Georgia" size="5">
            <br>Its is one of the famous theater in Pulivendula and its surroundings.</br>
            <br>This theater has two screens.</br>![1 map](https://github.com/Revanth-2717/NearMe/assets/152462274/e0117878-8652-4c26-bd05-860b6dd6bf7a)
![2 cinema](https://github.com/Revanth-2717/NearMe/assets/152462274/4af90601-aa27-444b-ba37-ac06b05d35c9)

            <br>It is the first theater in Pulivendula.</br>
            <br>It is bulit in 1990.</br>
            <br>It is a v celluliod cinema theater in Pulivendula.</br></font>
        </p>

    </body>
</html>

shilparamam.html

<html>
    <head>
        <title>shilparamam</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="red"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
            <font color="voilet"><b>shilaparamam</b></font>
        </h3>
        <hr size="5" color="blue">
        <p align="justify">
            <font face="Georgia" size="3">
            A prominent hub of fruit orchards in Kadapa district, Pulivendula has maintained its unique fabric of being a rural town, with an urban outlook. The advent of Shilparamam in the year 2009, has added a feather in the cap for this bustling town of Andhra Pradesh.
            
            <h2>Ticket Price:</h2>
            <br>ADULTS = 30/-</br>
            <br>ABOVE 5 YEARS BELOW 8 YEARS CHILDRENS = 15/-</br>
            <br>BOATING = 30/-</br>
            <br>CEMARA = 60/-</br>
            <br>VIDEOGRAPHY = 120/-</br>
            <h3>Timings</h3>
            <br>MORNING = 9 A.M TO</br>
            <br>EVINING = 8 P.M</br></font>
        </p>

    </body>
</html>

rani thopu.html

<html>
    <head>
        <title>Rani Thopu</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="yellow"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
            <font color="green"><b>Rani Thopu-The Park</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
            <font face="Georgia" size="5">
            Parks keep our environment clean and make us very happy. People visit the park for cycling, walking, and enjoying leisurely picnics. Some parks are designed smartly, keeping all age groups in mind, and even have benches so that people who get tired can sit.
            Parks play a very important role in society. They help people to stay healthy and fit. walking on grass and staying around a lot of trees is very healthy. It also reduces stress and makes people happy. People meet their friends and spend quality time. Parks are a safe place for children where there are no vehicles and they can play there safely. Parks also make our society look beautiful and green. Trees are planted here and it is also good for the environment.</font>
        </p>

    </body>
</html>

college.html

<html>
    <head>
        <title>college</title>
    </head>
    <body bgcolor="white">
        <h1 align="center">
            <font color="blue"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
            <font color="red"><b>Loyola Polytechnic College</b></font>
        </h3>
        <hr size="5" color="cyan">
        <p align="justify">
            <font face="Georgia" size="5">
            Loyola Polytechnic College, a prestigious higher education institution, was founded in Kadapa, Andhra Pradesh, in 1980. The institute offers Diploma programmes for students to further their studies. These programs are specially designed for Full Time mode and are approved by prominent national bodies such as AICTE. The institute offers a variety of courses such as after 10th Diploma in major streams including Engineering. Loyola Polytechnic College provides its students with top-notch education delivered by its skilled and experienced faculty in the fields of Electrical Engineering, Electronics & Communication Engineering, Computer Science Engineering, Mechanical Engineering, Mining Engineering, Civil Engineering. Most importantly, the 756 seats in these courses are provided at reasonable fees ranging between INR 72,000, to enable students to acquire knowledge and skills in their preferred area of interest. Loyola Polytechnic College also offers excellent infrastructure.</font>
        </p>

    </body>
</html>

statue.html

<html>
    <head>
        <title>statue</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
            <font color="orange"><b>PULIVENDULA</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Dr YS Rajasekhar Reddy Statue</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
            <font face="Georgia" size="5">
            Yeduguri Sandinti Rajasekhara Reddy (8 July 1949 - 2 September 2009), popularly known as YSR was an Indian politician. He served as the 14th chief minister of Andhra Pradesh from 2004 to 2009. Reddy was elected four times to the Lok Sabha from Kadapa and to the Andhra Pradesh Legislative Assembly for five terms from the Pulivendula, winning every election he contested.

In 2003, he undertook a three-month-long padayatra covering 1,500 kilometres (930 mi) in 60 days across 11 districts of Andhra Pradesh as a part of his election campaign. He led the Congress party to victory in the 2004 and 2009 assembly elections. On 2 September 2009, a helicopter carrying Reddy went missing in the Nallamala Forest area which was later confirmed to have crashed with all five people including Reddy pronounced dead.</font>
        </p>

    </body>
</html>
```

## Output:
![1 map](https://github.com/Revanth-2717/NearMe/assets/152462274/7e21307b-d745-485f-9d50-3f6fe19d03f4)
![2 cinema](https://github.com/Revanth-2717/NearMe/assets/152462274/50285af0-741c-4d77-b292-217a1c7f1bb8)
![3 shilparamam](https://github.com/Revanth-2717/NearMe/assets/152462274/0ad9c687-6f3c-48bc-826f-a17ee8062d1a)
![4 contact](https://github.com/Revanth-2717/NearMe/assets/152462274/4d90059b-f8d4-4050-a457-8f971f7941d4)
![4 rani thopu](https://github.com/Revanth-2717/NearMe/assets/152462274/c2636d5b-fefb-409b-b555-09be8bb8221e)
![5 college](https://github.com/Revanth-2717/NearMe/assets/152462274/a175f496-3da6-418b-9293-e1d0daeada35)

## Result:
image-maps has been created succesfully
