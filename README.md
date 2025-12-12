# Ex04 Places Around Me
## Date: 12-12-2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
  <img src="Screenshot 2025-12-12 201124.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="waterpark" title="waterpark" href="waterpark.html" coords="588,119,173" shape="circle">
    <area target="" alt="guesthouse" title="guesthouse" href="guesthouse.html" coords="784,507,139" shape="circle">
    <area target="" alt="saveethauniversity" title="saveethauniversity" href="saveethauniversity.html" coords="219,332,120" shape="circle">
</map>
    <title>Document</title>
</head>
<body>
    
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>THE SAVEETHA UNIVERSITY<h1>
        <IMG SRC="Screenshot 2025-12-12 205737.png"HEIGHT="600"WIDTH="1200">
        <p><h2>Saveetha Institute of Medical and Technical Sciences (SIMATS), formerly Saveetha University 
           in Chennai, is a prominent private deemed university known for diverse fields like Medicine, 
           Engineering, Dentistry, Law, and Management, offering UG/PG/Super Specialty courses with a 
           focus on practical learning (PBL) and innovation, featuring strong research and placements,
            though it faced scrutiny for citation issues in the past. </p></h2>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <IMG SRC="Screenshot 2025-12-12 205039.png"HEIGHT="600"WIDTH="1200">
    <p><h2>Amaravati Residency is the official guest house within the serene Saveetha University campus 
    (near Thandalam/Sriperumbadur), offering convenient, secure lodging for visiting faculty, 
    delegates, parents, patients, and scholars with essential amenities</p></h2>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <map name="image-map">
    <area target="" alt="waterpark" title="waterpark" href="waterpark.html" coords="588,119,173" shape="circle">
    <area target="" alt="guesthouse" title="guesthouse" href="guesthouse.html" coords="784,507,139" shape="circle">
    <area target="" alt="saveethauniversity" title="saveethauniversity" href="saveethauniversity.html" coords="219,332,120" shape="circle">
</map>
    <h1>THE WATER PARK</h1>
    <IMG SRC="Screenshot 2025-12-12 205644.png"HEIGHT="600"WIDTH="1200">
    <p><h2> Water Park in Kuthambakkam, Chennai, was a popular spot for family fun,
       offering thrilling water slides, wave pools, lazy rivers, and dedicated kids
       'play zones, but recent information suggests the park might be closed down, 
        so it's best to check its current operational status before visiting.</p></h2>
    
</body>
</html>

```


## OUTPUT
![alt text](<Screenshot 2025-12-12 210825.png>)
![alt text](<Screenshot 2025-12-12 210746.png>)
![alt text](<Screenshot 2025-12-12 224239.png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.
