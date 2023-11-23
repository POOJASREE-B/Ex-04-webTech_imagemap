NAME : POOJASREE B

REGISTER NUMBER : 23012790

DEPARTMENT : COMPUTER SCIENCE AND ENGINEERING
# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1
Create a folder 'static' under the project folder 'myproj'
## Step 2
In 'static',create another folder 'html',under which the file 'index.html' should be created
## Step 3
Go to google maps and take a screenshot of your home on it along with some places around it.
## Step 4
Go to image-maps.com and make 5 locations on it using the shapes used in maps.
## Step 5
Copy the html code for the map and add it to 'index.html'
## Step 6
Create the html documents to be displayed when clicked on the location in the image map
## Step 7
Take screenshots of the output
## Step 8
Push it to 'README.md' and push it to the repository

# Code:
## map.html
```
<!DOCTYPE html>
<html>
    <body>
        <h2>IMAGE MAP</h2>
        <P>You can click on Dr.Ambedkar playground, sri neelaganteswar alayam, muvarasnpattu eri, 
        Good shepherd school and Abi aqua gold water company:
        to read more about the topic:</P>
        <img src="https://res.cloudinary.com/dwuw0wizr/image/upload/v1700628613/imagemap_e01rij.png" 
        alt="Workplace" usemap="#workmap" width="1000" height="600">
        <map name="workmap">
            <area shape="rect"  coords="309, 285, 435, 436"    alt="ground"
            href="ground.html"> 
            <area shape="rect" coords="571, 193, 692, 306"  alt="watercompany" href="watercompany.html">
            <area shape="rect"  coords="313, 131, 451, 257 " alt="school" href="school.html">
            <area shape="rect" coords="862, -4, 1147, 310" alt="lake" href="lake.html">
            <area shape="rect"  coords="8, 410, 112, 535" alt="temple" href="temple.html">
          </map>
    </body>
</html
```

## ground.html
```<!DOCTYPE html>
<head>
    <body>
        <h1>DURAIKANNU MEMORIAL DR.AMBEDKAR PLAYGROUND</h1>
        <ul>
            <li>Duraikannu Memorial Dr.Ambedkar Play Ground is a Playground located at Kavitha Pannai, 
            Duraikannu Salai, Murugesapuram, Old Pallavaram, Chennai, Tamil Nadu  600117, IN.</li>
            <li>The establishment is listed under playground category.</li>
            <li>It has received 275 reviews with an average rating of 4.3 stars.</li>
        </ul>
    </body>
</head>
```

## watercompany.html
```<!DOCTYPE html>
<head>
    <body>
        <h1>ABI AQUA GOLD PACKAGED DRINKING WATER</h1>
        <ul>
            <li>No. 1 Rangaswamy Street,Tirusulam, Near All Amar School, Murugesapuram, Chennai-600117, Tamil Nadu, India</li>
            <li>Established in the year 2007</li>
            <li>Timings
                Mon - Sat 
                6:30 am - 6:45 pm 
                Sun 
                6:15 am - 2:00 pm </li>
        </ul>
    </body>
</head>
```

## school.html
```<!DOCTYPE html>
<head>
    <body><h1>GOOD SHEPHERD SCHOOL</h1>
        <li>Boading Schools are schools where students can complete their education as well as acquire training for a plethora of extracurricular activities while staying away from parents or guardian. Such schools teach children to be independent from an earkly age.These schools train students to be disciplined, weel-mannered and become resposible citizens of the world in the future.</li>
        <li>If you are on the hunt for a boarding school for your child, then we suggest you to visit Good Shepherd School in Old Pallavram,Chennai,Situated near Housing bord, it is one of the best boarding schools.If you are looking for a school that aids in the hostilic development of your child, then this is the one.</li>
        
    </body>     
        
</head>
```

## temple.html
```<!DOCTYPE html>
<head>
    <body>
        <h1>SRI NEELAGANTESWARAR TEMPLE</h1>
        <ul>
            <li>A good 1000 year old temple and possibly built when Thirusulanathar Temple was built. This temple is about 10 mins drive from the famous Tirusulanadhar temple. Small and peaceful temple. The goddess is Tirupurasundari,  same name as the goddess at Tirusulanafhar temple and even looks similar.</li>
            <li>The Ambal inside the grabhagraham is known as Sri Nirmalambal. Very beautiful statue of Ambal in the standing posture with her head slightly tilted. </li>
            <li>The Navagrahas are along with their Devis which is very rare and can be seen in very few temples.The temple has Dhwajadthambam, Bali peedam and a beautiful prakaram. It has a small temple tank. There is Arasa Maram and Neem tree together joined at the root itself.
                The temple has a south entrance and the temple facing East.</li>
        </ul>            
    </body>
</head>
```

## lake.html
```<!DOCTYPE html>
<head>
    <body>
        <h1>MUVARSANPATTU ERI</h1>
        <ul>
           <li>Muvarasnpattu eri is a tourist attraction located in Chennai, Tamil Nadu.</li>
           <li> The average rating of this place is 4.80 out of 5 stars based on 4 reviews.</li>
           <li> The street address of this place is X57J+55R, Muvarasanpattu Eri, Keelkattalai, Chennai, Tamil Nadu 600043, India.</li>
           <li>It is about 1.65 kilometers away from the Tirusulam railway station.</li>
        </ul>
    </body>
</head>
```



# Output:

![Alt text](<Screenshot 2023-11-23 091338.png>)

![Alt text](<Screenshot 2023-11-23 091411.png>)

![Alt text](<Screenshot 2023-11-23 091433.png>)

![Alt text](<Screenshot 2023-11-23 091448.png>)

![Alt text](<Screenshot 2023-11-23 091503.png>)

![Alt text](<Screenshot 2023-11-23 091515.png>)


# Result:
The output was verified successfully

