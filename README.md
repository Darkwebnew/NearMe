# EX 04 Places Around Me
## DATE:03/10/2023

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
## MAIN CODE
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>My Home Town</title>
  </head>
  <body>
    <h1 align="center">
      <font color="black">
        <b>MY HOME TOWN</b>
      </font>
    </h1>
    <h3 align="center">
      <font color="black">
        <b>SRIRAM V (23013561)</b>
      </font>
    </h3>
    <center>
      <img src="map.jpg" usemap="#MyHomeTown" height="1041" width="1825" />
      <map name="MyHomeTown">
        <area target="_blank" alt="CNR MATRICULATION SCHOOL" title="CNR MATRICULATION SCHOOL" href="CNR MATRICULATION SCHOOL.html" coords="726,324,763,366" shape="rect">
        <area target="_blank" alt="RUS PIZZA" title="RUS PIZZA" href="RUS PIZZA.html" coords="800,402,837,442" shape="rect">
        <area target="_blank" alt="Sri Varatharaja Perumal Temple" title="Sri Varatharaja Perumal Temple" href="Sri Varatharaja Perumal Temple.html" coords="1185,484,1222,524" shape="rect">
        <area target="_blank" alt="VANI STATIONARY" title="VANI STATIONARY" href="VANI STATIONARY.html" coords="290,411,330,458" shape="rect">
        <area target="_blank" alt="HOME" title="HOME" href="HOME.html" coords="786,755,836,800" shape="rect">
      </map>
    </center>
  </body>
</html>
```
## CNR MATRICULATION SCHOOL CODE
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>CNR MATRICULATION SCHOOL</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>Walaja</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>CNR MATRICULATION SCHOOL</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        Cnr Mat S Walajah School is Located in walaja municipality , walajah
        east Block and vellore District . it is Private School . The exact
        Address of the schools is walaja municipality , walajah east , vellore ,
        Tamil Nadu . PIN- 632513 , Post - Walajapet . It is one of the Old
        School in this area . It is Established in 1972 Year . Total 40 batches
        completed in this School from past 40 years . Classes running in this is
        School are upto 8 th . And it is Co-educatinal School .</font>
    </p>
  </body>
</html>
```
## RUS PIZZA CODE
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>RUS PIZZA</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>Walaja</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>RUS PIZZA</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        Rus Pizza in Ranipet HO, Ranipet Pizza is one of the most relished
        Italian foods all over the world. Even in our country, many of us enjoy
        a pizza that has a good filling and cheese on top. Pizza Outlets in
        Ranipet are experts in making delicious pizza. They ensure that the best
        quality produce is used to prepare the same. If you are a pizza lover,
        we strongly suggest you check out Rus Pizza in Ranipet HO, Ranipet. They
        are famous for making some lip-smacking pizza and offering a variety of
        options to their customers. Not only do they provide high-quality pizza
        at the best prices, but also offer services such as Home Delivery
        etc.</font>
    </p>
  </body>
</html>
```
## Sri Varatharaja Perumal Temple CODE
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Sri Varatharaja Perumal Temple</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>Walaja</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>Sri Varatharaja Perumal Temple</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        Sri Varadharaja Perumal Temple, also called Hastagiri and Attiyuran, is a
        Hindu temple dedicated to Vishnu located in the city of vellore,
        Tamil Nadu, India. It is one of the Divya Desams, the 108 temples of
        Vishnu believed to have been visited by the 12 poet saints, or the
        Alvars.</font>
    </p>
  </body>
</html>
```
## VANI STATIONARY CODE
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>VANI STATIONARY</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>Walaja</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>VANI STATIONARY</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        Vani Stationery & Xerox in Vellore is one of the leading businesses in
        the Stationery Shops. Established in the year 2016, Vani Stationery &
        Xerox in Jolarpettai, Vellore is a top player in the
        category Stationery Shops in the Vellore. This well-known establishment
        acts as a one-stop destination servicing customers both local and from
        other parts of Vellore. Over the course of its journey, this business
        has established a firm foothold in it's industry. The belief that
        customer satisfaction is as important as their products and services,
        have helped this establishment garner a vast base of customers, which
        continues to grow by the day. This business employs individuals that are
        dedicated towards their respective roles and put in a lot of effort to
        achieve the common vision and larger goals of the company. In the near
        future, this business aims to expand its line of products and services
        and cater to a larger client base. In Vellore, this establishment
        occupies a prominent location in Jolarpettai. It is an effortless task
        in commuting to this establishment as there are various modes of
        transport readily available.</font>
    </p>
  </body>
</html>
```
## HOME CODE
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>HOME</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>Walaja</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>HOME</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        A home, or domicile, is a space used as a permanent or semi-permanent
        residence for one or more human occupants, and sometimes various
        companion animals. It is a fully- or semi-sheltered space and can have
        both interior and exterior aspects to it. Homes provide sheltered
        spaces, for instance rooms, where domestic activity can be performed
        such as sleeping, preparing food, eating and hygiene as well as
        providing spaces for work and leisure such as remote working, studying
        and playing.</font>
    </p>
  </body>
</html>
```
## OUTPUT
![map home](https://github.com/Darkwebnew/NearMe/assets/143114486/b8b7be51-407b-401f-9e10-0703c376d0c6)
![CNR MATRICULATION SCHOOL](https://github.com/Darkwebnew/NearMe/assets/143114486/73e49b11-a38e-475e-8684-2c36dcfd40f2)
![RUS PIZZA](https://github.com/Darkwebnew/NearMe/assets/143114486/d62efd20-f511-40d4-baaf-7f43a556a46c)
![Sri Varatharaja Perumal Temple](https://github.com/Darkwebnew/NearMe/assets/143114486/1ff1df53-ccbb-4ea4-871c-9af7267369ed)
![VANI STATIONARY](https://github.com/Darkwebnew/NearMe/assets/143114486/c2dbb9e2-def5-4652-a42b-542591b270cd)
![HOME](https://github.com/Darkwebnew/NearMe/assets/143114486/85740ba6-7642-4281-8f2c-ef4d1019852e)
## RESULT
The program for implementing image maps using HTML is executed successfully.
