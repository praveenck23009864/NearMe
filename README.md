# Ex04 Places Around Me
## Date:07.10.23
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
map.html

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
        <b>praveen ck (23009864)</b>
      </font>
    </h3>
    <center>
      <img src="map.png" usemap="#My Home Town" height="918px" width="1920px" />
      <map name="My Home Town">
        <area target="_blank" alt="high school Ground" title="high school Ground" href="high school Ground.html" coords="518,523,491,477" shape="rect">
        <area target="_blank" alt="SAROJA ILLAM" title="SAROJA ILLAM" href="SAROJA ILLAM.html" coords="820,482,869,538" shape="rect">
        <area target="_blank" alt="SIPCOT industrial Park Pillaipakkam" title="SIPCOT industrial Park Pillaipakkam" href="SIPCOT industrial Park Pillaipakkam.html" coords="1721,519,1750,560" shape="rect">
        <area target="_blank" title="Apotolic Chistian assembly" coords="984,408,1016,452" shape="rect" href="Apotolic Chistian assembly.html" >
        <area target="_blank" alt="Government Higher secondary school" title="Government Higher secondary school" href="Government Higher secondary school.html" coords="601,475,571,439" shape="rect">
      </map>
    </center>
  </body>
</html>
SIPCOT industrial Park Pillaipakkam.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>SIPCOT industrial Park Pillaipakkam</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>sriperumbudur</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>SIPCOT industrial Park Pillaipakkam</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
         SIPCOT has rendered fruitful services to the state by identifying, developing, maintaining
         Industrial Areas in backward and most backward taluk of the State, which had the potential to grow. Establish, develop, maintain and manage Industrial Complexes, parks and growth centres at various places 
         across the State of Tamil Nadu. SIPCOT's role in assisting the industrialization in the State is not only quantitative but also qualitative.
         Instead of just accelerating the pace of industrial growth in already developed and densely populated areas, SIPCOT, as a nodal agency, strives 
         to ensure that disbursal of financial incentives result in spurt of industrial growth in backward and areas yet to develop.
         To ensure a good impact with the available limited resources, SIPCOT has created Industrial Complexes and Parks, strategically located in 
         twenty one places and twelve Districts, which occupy a place of pride in the State's industrial map.
         Very cooperative people. Good Service to public.
         Well connected with major roads and lot of land area</font>
    </p>
  </body>
</html>

SAROJA ILLAM.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>SAROJA ILLAM</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>sriperumbudur</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>SAROJA ILLAM</b></font>
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

high school Ground.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>high school Ground</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>sriperumbudur</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>high school Ground</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        Open school ground all time every morning 5am to 730 am good growed and evg time good growed on ground ,lights more then 
        need to the place ,good school ground ...all public person used the ground so good ,good environmental 
        create to goverment super place ... Wait for .....like him surroundings well develop food and another ext..
     </font>
    </p>
  </body>
</html>

Government Higher secondary school.html


<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Government Higher secondary school</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>sriperumbudur</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>Government Higher secondary school</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        It is government undertaken Higher Secondary School has been located in Sriperumbudur to 
        Tambaram nearby signal and the court, there have classes available upto 12th standard it 
        is running under by State Board education system Tamil medium school, in the school near 
        by have very big playing ground for football and cricket it's a good one for the students</font>
    </p>
  </body>
</html>

Apotolic Chistian assembly.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apotolic Chistian assembly(ACA...)</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>sriperumbudur</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>Apotolic Chistian assembly(ACA...)</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
         feel God's presence.n traditional Christian architecture, the plan view of a church often forms a Christian 
         cross with the center aisle and seating representing the vertical beam and the bema and altar forming the horizontal. 
         Towers or domes may inspire contemplation of the heavens. Modern churches have a variety of architectural styles and 
         layouts. Some buildings designed for other purposes  have been converted to churches, while many original church buildings
          have been put to other uses.</font>
    </p>
  </body>
</html>![Screenshot (5)](https://github.com/praveenck23009864/NearMe/assets/141472050/b479fad7-4472-408a-8833-3e7a2a3356ff)![Screenshot (7)](https://github.com/praveenck23009864/NearMe/assets/141472050/fddb9805-14bc-439d-ae61-1039bdc32c5d)
![Screenshot (6)](https://github.com/praveenck23009864/NearMe/assets/141472050/79f98ff9-6af2-4a99-b5a4-230eb34fc0fb)



```


## OUTPUT

![Screenshot (2)](https://github.com/praveenck23009864/NearMe/assets/141472050/78a33cfc-8b7e-45e6-ab5c-386014603e20)
![Screenshot (3)](https://github.com/praveenck23009864/NearMe/assets/141472050/15a6e575-0ea6-433b-87d1-9c0b3869d13a)

![Screenshot (4)](https://github.com/praveenck23009864/NearMe/assets/141472050/2283d8a1-302f-492a-982a-8429569383cc)
![Screenshot (6)](https://github.com/praveenck23009864/NearMe/assets/141472050/f6f06f0a-97ef-4b3c-8406-d95ad775c949)

![Screenshot (5)](https://github.com/praveenck23009864/NearMe/assets/141472050/4c88e30c-6371-413c-ad1d-83d1a4d05745)
![Screenshot (7)](https://github.com/praveenck23009864/NearMe/assets/141472050/1e53a7e0-bc06-4e60-8a0f-4142c362bdce)

## RESULT
The program for implementing image maps using HTML is executed successfully.
