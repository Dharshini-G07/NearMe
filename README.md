# Ex04 Places Around Me
## Date: 22/4/2025

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
    <title>Image App</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Chidambaram</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Priyadharshini G(212224230209)</b></font>
        </h3>
        <center>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Temple" title="Temple" href="Thillai Nataraja.html" coords="450,272,34" shape="circle">
    <area target="" alt="Supermarket" title="Supermarket" href="Thangam Maligai.html" coords="121,340,409,388" shape="rect">
    <area target="" alt="Hotel" title="Hotel" href="Vandayar Hotel.html" coords="648,249,650,244,832,247,697,349,775,338,655,302,645,269" shape="poly">
</map>
</center>
    </body>
</html>

Thangam Maligai.html
<html>
    <head>
        <body bgcolor="cyan">
            <h1 align="center">
                <font color="red"><b>Shop</b></font>
            </h1>
            <h3 align="center">
                <font color="blue"><b>Thangam Maligai</b></font></b></font>
            </h3>
            <hr size="3" color="red">
            <p align="justify">
                <font face="Georgia" size="5">
                    A supermarket is a self-service shop offering a wide variety of food, beverages and household products, organized into sections.Thangam Maligai Shop is a 13 years 1 month old Proprietorship Firm incorporated on 01-Mar-2012, having its registered office located at 2, Thangam Maligai Shop, Orathur, Mariyamman Kovil Street, Cuddalore, Tamil Nadu.
                    The major activity of Thangam Maligai Shop is Trading For Availing Benefits Of Priority Sector Lending Psl Only , Sub-classified into Food and beverage service activities and is primarily engaged in the Activities of food service contractors e g for transportation companies .
                    Thangam Maligai Shop is classified as Micro enterprise in the financial year 2022-23. It has its unit situated at Cuddalore, Tamil Nadu.
                </font>
            </p>
    </head>
</html>

Thillai Nataraja.html
<html>
<head>
    <body bgcolor="cyan">
        <h1 align="center">
            <font color="red"><b>Temple</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Thillai Nataraja</b></font></b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                The temple was constructed during the 10th Century when Chidambaram used to be the capital of the Chola dynasty. The Cholas considered Lord Shiva as Nataraj as their family deity. The Nataraj temple has undergone damage, renovation and expansion throughout the 2nd millennium.The Chidambaram temple complex proudly boasts of being one of the oldest temple complexes in Southern India. The most unique characteristic of the Nataraj Temple is the bejewelled image of Nataraj. The temple has five main Halls or Sabhas namely the Kanaka Sabha, the Cit Sabha, Nritta Sabha, Deva Sabha and Raja Sabha.
            </font>
        </p>
</head>
</html>

Vandayar Hotel
<html>
    <head>
        <body bgcolor="cyan">
            <h1 align="center">
                <font color="red"><b>Hotel</b></font>
            </h1>
            <h3 align="center">
                <font color="blue"><b>Vandayar Hotel</b></font></b></font>
            </h3>
            <hr size="3" color="red">
            <p align="justify">
                <font face="Georgia" size="5">
                    Everyone needs a place to lay their weary head. For travellers visiting Chidambaram, Vandayar Hotel is an excellent choice for rest and rejuvenation. Well-known for its family-friendly environment and proximity to great restaurants, Vandayar Hotel makes it easy to enjoy the best of Chidambaram.Our hotel sits at the best land point on Chidambaram, with nearest access to the Nataraja Temple and Annamalai University. Enjoy our bar, High Class Vegetarian Restaurant, and Multicuisine Restaurant.

                    Vandayar hotel founded in 2001, and today is the Chidambaram’s largest and best hotel. The alliance has over 70 staffs, 1 veg restaurant, 1 non veg restaurant, 1 dine bar and 1 party hall.
                </font>
            </p>
    </head>
</html>

```

## OUTPUT
![alt text](<Screenshot 2025-04-22 202454.png>)
![alt text](<Screenshot 2025-04-22 204941.png>)
![alt text](<Screenshot 2025-04-22 205148.png>)
![alt text](<Screenshot 2025-04-22 205340.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
