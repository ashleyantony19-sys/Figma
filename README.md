# Ex09 Event Registration Web Application
## Date:20-03-2026

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
home page
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="image"><img class="screenshot" src="img/screenshot-2026-03-20-125138-1.png" /></div>
  </body>
</html>

style1.css
.image {
  width: 592px;
  height: 1060px;
}

.image .screenshot {
  position: fixed;
  top: 67px;
  left: 74px;
  width: 446px;
  height: 967px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

event page
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="screenshot" src="img/screenshot-2026-03-20-125138-2.png" />
      <div class="text-wrapper">Cultural Day Events</div>
      <p class="solo-singing-solo">
        Solo Singing<br /><br />Solo Dancing<br /><br />Ramp walk<br /><br />Drama<br /><br />Group Singing<br /><br />Group
        dancing
      </p>
    </div>
  </body>
</html>

style2.css

.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 438px;
  min-height: 967px;
  position: relative;
}

.iphone .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 438px;
  height: 967px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 110px;
  left: 63px;
  width: 468px;
  height: 49px;
  display: flex;
  align-items: center;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .solo-singing-solo {
  position: absolute;
  top: 159px;
  left: 70px;
  width: 274px;
  height: 444px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

final page
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="screenshot" src="img/screenshot-2026-03-20-125138-3.png" />
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <div class="rectangle"></div>
      <div class="div">Name</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">Year</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">Department</div>
      <div class="rectangle-4"></div>
      <div class="events-to-register">Events to&nbsp;&nbsp;Register</div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-4">REGISTER</div>
    </div>
  </body>
</html>

style3.css

.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 434px;
  min-height: 967px;
  position: relative;
}

.iphone .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 434px;
  height: 967px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 109px;
  left: 81px;
  width: 304px;
  height: 57px;
  display: flex;
  align-items: center;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle {
  position: absolute;
  top: 193px;
  left: 42px;
  width: 343px;
  height: 60px;
  background-color: #d9d9d9;
}

.iphone .div {
  position: absolute;
  top: 216px;
  left: 70px;
  height: 19px;
  display: flex;
  align-items: center;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-2 {
  position: absolute;
  top: 309px;
  left: 42px;
  width: 343px;
  height: 57px;
  background-color: #d9d9d9;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 325px;
  left: 71px;
  height: 19px;
  display: flex;
  align-items: center;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-3 {
  position: absolute;
  top: 426px;
  left: 42px;
  width: 343px;
  height: 58px;
  background-color: #d9d9d9;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 442px;
  left: 59px;
  height: 19px;
  display: flex;
  align-items: center;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-4 {
  position: absolute;
  top: 543px;
  left: 42px;
  width: 343px;
  height: 71px;
  background-color: #d9d9d9;
}

.iphone .events-to-register {
  position: absolute;
  top: 563px;
  left: 65px;
  height: 19px;
  display: flex;
  align-items: center;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-5 {
  position: absolute;
  top: 726px;
  left: 96px;
  width: 230px;
  height: 99px;
  background-color: #22f313;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 763px;
  left: 152px;
  width: 146px;
  height: 29px;
  display: flex;
  align-items: center;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}


```
## OUTPUT:
![alt text](<Screenshot (25).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
