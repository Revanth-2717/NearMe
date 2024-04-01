# Ex04 Places Around Me
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
index.html :

```
<!DOCTYPE html>
<html>
    <head>
        <title>Places around me</title>
    </head> 
    <body>
        <img id="Image-Maps-Com-image-maps-2023-07-24-084406" src="https://app.image-maps.com/m/private/0/iq82kpfjes1dlnffrlu45qlpbt_maps.jpg" border="0" width="1200" height="811" orgWidth="1200" orgHeight="811" usemap="#image-maps-2023-07-24-084406" alt="" />
        <map name="image-maps-2023-07-24-084406" id="ImageMapsCom-image-maps-2023-07-24-084406">
            <area alt="" title="college" href="college.html" shape="rect" coords="253,98,460,215" style="outline:none;" target="_self" />
            <area alt="" title="tabunhotel" href="tabunhotel.html" shape="rect" coords="402,248,602,319" style="outline:none;" target="_self" />
            <area alt="" title="tempel" href="tempel.html" shape="rect" coords="931,175,1120,236" style="outline:none;" target="_self" />
            <area alt="" title="conventionhall" href="conventionhall.html" shape="rect" coords="328,529,520,604" style="outline:none;" target="_self" />
            <area alt="" title="home" href="home.html" shape="rect" coords="328,385,471,433" style="outline:none;" target="_self" />
            <area shape="rect" coords="1198,809,1200,811" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
        </map>
    </body>
</html>
```
college.html:

```
<!DOCTYPE html>
<html>
    <head>
        <title>college</title>
    </head>  
    <body>
        <img src="C:\Users\admin\Downloads\college.jepg" alt="College Image" style="width:100%">
        <br>
        <br>
        <h1>SRI VENKATESWARA COLLEGE OF ENGINEERING</h1>
        <br>
        Sri Venkateswara College of Engineering and Technology, established
        in 1998 is affiliated to JNTUA, Anantapur and approved by AICTE, NBA.
        SVCET offers B.Tech courses at the undergraduate level and offers MBA, MCA
        and M.Tech courses in various disciplines at the postgraduate level.
        Admission to the courses offered will be done based on the candidate’s
        performance in the entrance examination. Some of the top recruiters that
        recruit SVCET’s students include IBM, Cognizant, Infosys, Wipro, Polaris etc. 
    </body>  
</html>
```
convectionhall.html :

```
<!DOCTYPE html>
<html>
    <head>
        <title>The Convection Hall</title> 
    </head>  
    <body>
        <img src="C:\Users\admin\Downloads\convectionhall.jpeg" alt="Convention Hall Image" style="width:100%">
        <br>
        <br>
        RLN Convection Hall:
        <br>
        <br>
        <h1>THE CONVECTION HALL </h1>
        <br>
        This convection hall is more popular in our town.
        Every big function will be do in that function hall only.
        The function hall will be so nice so that every one will
        do in that function hall. Firstly, the parking area is
        comfortable, and this function hall has the facility of
        two halls in one building, without disturbance; one is
        for Muslim function, the other Hindu function and others.
        This function hall has more comfortable place in that area.
    </body>  
</html>
```
home.html :
```
<!DOCTYPE html>
<html>
    <head>
        <title>HOME</title> 
    </head>  
    <body>
        <br>
        <br>
        HOME:
        <br>
        <br>
        <h1>SRI VENKATESWARA NILAYAM</h1>
        <br>
        My house name is Sri Venkateswara Nilayam. It was built in 1987. For that house 
        have more history. I like that house so much. Besides, my house will be more trees,
        it will be so beautiful weather, and in 50 meters the beach will be. The climate of my house will be so beautiful,
        the surroundings of my house will be so beautiful.
    </body>  
</html>
```
tabunhotel.html :
```
<!DOCTYPE html>
<html>
    <head>
        <title>Tabun Hotel</title> 
    </head>  
    <body>
        <img src="C:\Users\admin\Downloads\tabunhotel.jpg" alt="Tabun Hotel Image" style="width:100%">
        <br>
        <br>
        Tabun Hotel:
        <br>
        <br>
        <h1>The TABUN HOTEL</h1>
        <br>
        The Tabun hotel is a multicuisine restaurant. This restaurant is more popular in our town; every
        one will go to this restaurant only. Why? Because in this restaurant, the taste will be nice,
        so that everyone will go to this restaurant. Beautiful Mandi biriyani experience. Multi-cuisine restaurant,
        but best for Arabian cuisine. Mandi biriyani is a must-try for anyone visiting here. The Arabian mixed
        Mandi beats them all as you get a variety of non-veg items with the biriyani. Half Mandi should be sufficient
        for 3 people and the full, for easily 6-7 people. The ambiance was brilliant, staff is well-mannered and it
        was a very different experience altogether in comparison to any other regular restaurant.
    </body>  
</html>
```
temple.html :
```
<!DOCTYPE html>
<html>
    <head>
        <title>Temple</title> 
    </head>  
    <body>
        <img src="C:\Users\admin\Downloads\temple.jpg" alt="Temple Image" style="width:100%">
        <br>
        <br>
        Temple:
        <br>
        <br>
        <h1>SRI RAMA TEMPLE</h1>
        <br>
        This Rama temple has more history and the 
        temple is more powerful. To this temple will come more visitors.
        This temple is more beautiful. Ayodhya is the birthplace of Lord Rama
        and he is known as Purushottam which means the best of men or the Supreme Purusa (personality).
        According to Swami Vivekananda, Shri Rama is "the embodiment of truth, of morality, the ideal son,
        the ideal husband, and above all, the ideal king." Lord Rama was born in Treta Yuga and is also known
        to be the oldest deity worshipped in human form. Various temples are dedicated to Lord Rama all over
        India few of them are listed below.
    </body>  
</html>

```


## Output:
index.html:
![WhatsApp Image 2023-11-21 at 16 27 06_e3bb5d01](https://github.com/SANTHAN-2006/Ex-04-webTech_imagemap/assets/80164014/e67ea816-951e-40b1-bdf9-d90ce515138b)

college.html:
![image](https://github.com/SANTHAN-2006/Ex-04-webTech_imagemap/assets/80164014/eb7fb4da-be42-4af7-aff2-62a55d92d63a)

convectionhall.html:
![image](https://github.com/SANTHAN-2006/Ex-04-webTech_imagemap/assets/80164014/7bb42eb8-309e-4a72-b071-b78fc530df67)

tabunhotel.html:
![image](https://github.com/SANTHAN-2006/Ex-04-webTech_imagemap/assets/80164014/1da529d0-685f-4960-aeaa-9ccfb537fd49)

temple.html:
![image](https://github.com/SANTHAN-2006/Ex-04-webTech_imagemap/assets/80164014/87544148-9424-4094-b33b-f3e325cdce1a)


## Result:
image-maps has been created succesfully
