# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Clone the github repository into Theia IDE.
### Step 2:
Create a new Django project.
### Step 3:
Write the required HTML code
### Step 4:
Run the Django server and execute the HTML files.

## Code:
# Map.html
```python
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>My City</title>
    </head>
    <body>
    <h1 align="center">
        <font color="red"><b>Chennai</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Hariharan A (212222100012)</b></font>
    </h3>
    <centre>
    <img id="Image-Maps-Com-image-maps-2023-05-11-164109" src="map1.png" border="0" width="1364" 
         height="847" orgWidth="1364" orgHeight="847" usemap="#image-maps-2023-05-11-164109" alt=""/>
<map name="image-maps-2023-05-11-164109" id="ImageMapsCom-image-maps-2023-05-11-164109">
<area  alt="" title="Temple" href="temple.html" shape="rect" coords="360,600,647,694" 
      style="outline:none;" target="_self"/>
<area  alt="" title="school" href="school.html" shape="rect" coords="1135,82,1351,187" 
      style="outline:none;" target="_self"/>
<area  alt="" title="beach" href="beach.html" shape="rect" coords="777,626,944,663" 
      style="outline:none;" target="_self"/>
<area  alt="" title="Park" href="park.html" shape="rect" coords="427,542,478,598" 
      style="outline:none;" target="_self"/>
<area  alt="" title="hospital" href="hospital.html" shape="rect" coords="50,663,231,720" 
      style="outline:none;" target="_self"/>
<area shape="rect" coords="1362,845,1364,847" alt="Image Map" style="outline:none;"
      title="Image Map" href="https://www.image-maps.com/"/>
</map>
      </centre>
    </body>
</html>
```
# Temple.html
```python
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Temple</title>
    </head>
    <body bgcolor="#ADDFFF">
        <h1 align="center">
            <font color="red"><b>Shri Ashtalakshmi Temple</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Asthalakshmi Temple</b></font>
        </h3>
        <center>
             <img src ="temple.png"  height="300" width="600" align="center" >
        </center>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                The Ashtalakshmi Kovil is a Hindu temple, which lies on the shorelines near the Elliot's beach, in Chennai, India. 
                The temple is dedicated to the goddess Lakshmi, and her eight primary forms – the Ashtalakshmi – the giver of all eight forms of,
                wealth, namely, offspring, success, prosperity, wealth, courage, bravery, food, and knowledge. 
                The sanctorums are depicted on a multi-tier complex in such a way that visitors could visit all the shrines without stepping over any of the sanctorums.
            </font>
        </p>
    </body>
</html>
```
# School.html
```python
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>School</title>
    </head>
    <body bgcolor="#ADDFFF">
        <h1 align="center">
            <font color="red"><b>Vana Vani Higher Secondry School</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>SCHOOL</b></font>
        </h3>
        <hr size="3" color="red">
        <center>
             <img src ="school.png"  height="300" width="600" align="center" >
        </center>
        <p align="justify">
            <font face="Arial" size="5">
            A school is an educational institution designed to provide learning spaces and learning environments for 
           the teaching of students underthe direction of teachers. Most countries have systems of formal education, 
           which is sometimes compulsory. In these systems, students progress through a series of schools.School is the 
           basic foundation of knowledge being imparted to a child. It gives a chance to children to acquire knowledge on 
           various fields of education, such as people, literature, history, mathematics, politics, and othe numerous subjects.
            </font>
        </p>
    </body>
</html>
```
# Beach.html
```python
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Beach</title>
    </head>
    <body bgcolor="#ADDFFF">
        <h1 align="center">
            <font color="red"><b>Besant Nagar</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Beach</b></font>
        </h3>
        <hr size="3" color="red">
        <center>
             <img src ="beach.png"  height="300" width="600" align="center" >
        </center>
        <p align="justify">
            <font face="Arial" size="5">
                Besant Nagar is an upscale, exclusive residential neighbourhood in South Chennai, India.
                It is located along the coast of Bay of Bengal.
                The neighbourhood is inhabited by highly affluent population and is dotted with many upmarket restaurants, cafes and boutiques. 
                The main attraction is Elliot's Beach, named after Edward Elliot, the former Governor of Madras.
                It forms the end-point of the Marina Beach shore. 
                This has become an attractive spot for youngsters and elders alike with the pleasant sceneries and the ambiance it provides.   
            </font>
        </p>
    </body>
</html>
```
# Park.html
```python
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Park</title>
    </head>
    <body bgcolor="#ADDFFF">
        <h1 align="center">
            <font color="red"><b>Guindy National Park</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>PARK</b></font>
        </h3>
        <hr size="3" color="red">
        <center>
             <img src ="park.png"  height="300" width="600" align="center" >
        </center>
        <p align="justify">
            <font face="Arial" size="5">
                The park is a an open area,often found with trees,benches,statues,etc. There is also lots of nature around, 
              such as flowers,animals, trees, and much more. It is mostly used for recreational activities such as walking, 
              exercising, cycling, playing,etc.to communities because they create a space for community members to congregate 
              safely and enjoy nature; kids can play under their parents' watchful eye and community members can improve their 
              health with equipment, all within a relaxing environment.
            </font>
        </p>
    </body>
</html>
```
# Hospital.html
```python
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Hospital</title>
    </head>
    <body bgcolor="#ADDFFF">
        <h1 align="center">
            <font color="red"><b>Fortis Hospital</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>HOSPITAL</b></font>
        </h3>
        <hr size="3" color="red">
        <center>
             <img src ="hospital.png"  height="300" width="600" align="center" >
        </center>
        <p align="justify">
            <font face="Arial" size="5">
            A hospital is a health care institution providing patient treatment with specialized health science and auxiliary healthcare staff and medical equipment.
            The best-known type of hospital is the general hospital, which typically has an emergency department to treat urgent health problems ranging from fire and accident victims to a sudden illness.
            A district hospital typically is the major health care facility in its region, with many beds for intensive care and additional beds for patients who need long-term care. 
            Specialized hospitals include trauma centers, rehabilitation hospitals, children's hospitals, seniors' (geriatric) hospitals, and hospitals for dealing with specific medical needs such as psychiatric treatment (see psychiatric hospital) and certain disease categories. 
            Specialized hospitals can help reduce health care costs compared to general hospitals.
            Hospitals are classified as general, specialty, or government depending on the sources of income received.
            </font>
        </p>
    </body>
</html>
```
## Output:
# Map:
![image](https://github.com/Mithramukund/places-around-me/assets/121608770/da03c582-d354-4e09-9df7-0d8e1844a3e2)

# Temple:
![image](https://github.com/Mithramukund/places-around-me/assets/121608770/7ff8a9ac-9e97-4e20-8bb7-590ab94b7196)

# School:
![image](https://github.com/Mithramukund/places-around-me/assets/121608770/4c9bdd6a-fb5e-4866-9683-4de228f6b757)

# Beach:
![image](https://github.com/Mithramukund/places-around-me/assets/121608770/abbe8dae-3b64-42d5-a480-f877b9c72f96)

# Park:
![image](https://github.com/Mithramukund/places-around-me/assets/121608770/46d527b5-9596-4766-acf2-902b01e8ea46)

# Hospital:
![image](https://github.com/Mithramukund/places-around-me/assets/121608770/90cbe74f-595c-4d28-b832-c606cde032d8)

## Server Output:
![image](https://github.com/Mithramukund/places-around-me/assets/121608770/0114d661-5797-41b9-9f68-160ef1917b25)

## HTML Validator:
![image](https://github.com/Mithramukund/places-around-me/assets/121608770/45dbe5c3-6b46-451f-b3fe-0c73b4ffea44)

## Result:
The program for implementing image map is executed successsfully.
