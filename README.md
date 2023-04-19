# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Clone the github repository into Theia IDE.
### Step 2:
Create a new Django project.
### Step 3:
Write the needed HTML code.
### Step 4:
Run the Django server and execute the HTML files.

## Code:
map.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Thiruvallur-City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>JAYAKRISHNAN L B L (212222230052)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="571" width="1280">
<map name="MyCity">
<area shape="rectangle" coords="372,228,458,263" href="/static/html/resort.html" title="Varma Resort">
<area shape="rectangle" coords="109,257,229,290" href="/static/html/poorvika.html" title="Poorvika Mobiles">
<area shape="rectangle" coords="455,390,617,508" href="/static/html/theatre.html" title="Theatre">
<area shape="rectangle" coords="537,320,682,412" href="/static/html/railway.html" title="Railway Station">
<area shape="rectangle" coords="664,312,870,412" href="/static/html/school.html" title="Shree Nikethan. High. Sec. School">
</map>
</center>
</body>
</html>
```
resort.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Varma Resort</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Thiruvallur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Varma Resort</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
<li>Varma Resort is very good in all terms. It has good quality and variety food. Its location is also easy to find opposite railway station</li>
<li>Varma Resort is one of the recommended Hotels that offers the best service to the guests. It has essential facilities so that you enjoy a comfortable stay</li></font>
</p>
</body>
</html>
```
poorvika.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Poorvika Mobiles</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Thiruvallur -oil mill</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Poorvika Mobiles</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
"Poorvika Mobiles stands out as a Prominent and Award Winning mobile collections in South India. poorvika Mobiles today has 18 Exclusive Showrooms across South India offering a wide variety of exquisite smart mobiles and electric gadgets."
</font>
</p>
</body>
</html>
```
theatre.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Theatre</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Thiruvallur-City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Rakki Theatre </b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
There is no dearth of good cinemas in Thiruvallur. And, the theatre in Thiruvallur which has become the hub for cinemagoers is Rakki Cinemas Dolby Atmos.Rakki Cinemas Dolby Atmos, Thiruvallur is a chain of theatres in India that exhibit a myriad of movies around the year. Be it a Regional, Bollywood , Hollywood , Kollywood etc..</font>
</p>
</body>
</html>
```
railway.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Railway Station</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Thiruvallur-Railway station</font>
</h1>
<h3 align="center">
<font color="blue"><b> Thiruvallur railway station</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
A railway is a place where train stop for passengers to get on and off the train.
The construction of train stops tends to reflect the level of usage, where stops at busy locations may have shelters, seating, and possibly electronic passenger information systems. 
</b>
</font>
</p>
</body>
</html>
```
school.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Shree Nikethan. High. Sec. School</title>
</head>
<body bgcolor="<!DOCTYPE html>
lime">
<h1 align="center">
<font color="red"><b>Thiruvallur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Shree Nikethan Higher Secondary School</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The main objectives of Shree Nikethan Higher Secondary School are 
<ul>
<li>To impart proper and qualified training to teachers and give them an attractive salary and incentives so that they are not tempted to quit and look elsewhere for jobs.</li>
<li>To provide financial aids and grants wisely and judiciously.</li>
<li>To Frame of syllabus and curriculum.</li>
<li>To set aims and objectives of education.</li>
</ul>
</font>
</p>
</body>
</html>
```
## Output:
![Screenshot 2023-04-19 205300](https://user-images.githubusercontent.com/120232371/233126022-4f3f5ce3-4ad5-4042-933d-ae48f939fecc.png)
![Screenshot 2023-04-19 205120](https://user-images.githubusercontent.com/120232371/233126636-af902743-36d3-404b-9cef-af4c9aae7cfd.png)
![Screenshot 2023-04-19 205018](https://user-images.githubusercontent.com/120232371/233126929-0e44c793-fc6d-4816-91d9-d8199162aef6.png)
![Screenshot 2023-04-19 210649](https://user-images.githubusercontent.com/120232371/233127448-854bdf3a-10bc-4e56-ac27-a744b8ef65a4.png)
![Screenshot 2023-04-19 205230](https://user-images.githubusercontent.com/120232371/233127594-e7108506-50fd-4abe-9830-dadc47ef7ff3.png)
![Screenshot 2023-04-19 205058](https://user-images.githubusercontent.com/120232371/233127884-afdd41ee-b3a4-4d30-9af0-2554bc454480.png)


## Result:
The program for implementing image map is executed successfully.
