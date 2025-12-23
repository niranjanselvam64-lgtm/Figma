# Ex08 Event Registration Web Application
## Date:23/12/2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
page 1
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="logo" src="img/logo-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">Annual day Event</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="img" src="img/rectangle-3.svg" />
      <div class="div">LOGIN</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">Register</div>
      <div class="rectangle-3"></div>
      <img class="sec-logo" src="img/sec-logo-01as-1.png" />
      <div class="rectangle-4"></div>
      <div class="text-wrapper-3">BY: Niranjan S</div>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #151414;
  overflow: hidden;
  width: 100%;
  min-width: 448px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .logo {
  position: absolute;
  top: 130px;
  left: 112px;
  width: 189px;
  height: 189px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 365px;
  left: 0;
  width: 448px;
  height: 91px;
  background-color: #e31818;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 382px;
  left: 40px;
  width: 393px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 482px;
  left: -332px;
  width: 269px;
  height: 65px;
}

.iphone-pro-max .img {
  position: absolute;
  top: 532px;
  left: 0;
  width: 448px;
  height: 92px;
}

.iphone-pro-max .div {
  position: absolute;
  top: 554px;
  left: 123px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #00ff00;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 694px;
  left: 0;
  width: 448px;
  height: 91px;
  background-color: #eeff07;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 716px;
  left: 112px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 769px;
  left: 127px;
  width: 30px;
  height: 4px;
  background-color: #d9d9d9;
}

.iphone-pro-max .sec-logo {
  position: absolute;
  top: 5px;
  left: 0;
  width: 441px;
  height: 90px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 914px;
  left: 0;
  width: 448px;
  height: 50px;
  background-color: #4c3ab6;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 908px;
  left: 56px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}


page2

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="rectangle"></div>
      <div class="text-wrapper">Annual Day events:</div>
      <img class="star" src="img/star-1.svg" />
      <div class="div">National anthem</div>
      <img class="img" src="img/star-2.svg" />
      <img class="star-2" src="img/star-9.svg" />
      <img class="star-3" src="img/star-8.svg" />
      <img class="star-4" src="img/star-7.svg" />
      <img class="star-5" src="img/star-6.svg" />
      <div class="text-wrapper-2">Group song</div>
      <img class="star-6" src="img/star-3.svg" />
      <img class="star-6" src="img/star-4.svg" />
      <img class="star-7" src="img/star-5.svg" />
      <div class="text-wrapper-3">Group Dance</div>
      <div class="text-wrapper-4">Ramp walk</div>
      <div class="text-wrapper-5">DJ</div>
      <div class="text-wrapper-6">solo speech</div>
      <div class="text-wrapper-7">skit</div>
      <div class="text-wrapper-8">solo dance</div>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #eeff07;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 27px;
  left: 15px;
  width: 409px;
  height: 127px;
  background-color: #fd820e;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 52px;
  left: 39px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .star {
  position: absolute;
  top: 189px;
  left: 16px;
  width: 37px;
  height: 35px;
}

.iphone-pro-max .div {
  position: absolute;
  top: 185px;
  left: 65px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .img {
  position: absolute;
  top: 263px;
  left: 16px;
  width: 40px;
  height: 34px;
}

.iphone-pro-max .star-2 {
  position: absolute;
  top: 551px;
  left: 13px;
  width: 40px;
  height: 34px;
}

.iphone-pro-max .star-3 {
  position: absolute;
  top: 478px;
  left: 13px;
  width: 40px;
  height: 34px;
}

.iphone-pro-max .star-4 {
  position: absolute;
  top: 393px;
  left: 14px;
  width: 40px;
  height: 34px;
}

.iphone-pro-max .star-5 {
  position: absolute;
  top: 638px;
  left: 13px;
  width: 40px;
  height: 34px;
}

.iphone-pro-max .text-wrapper-2 {
  top: 258px;
  position: absolute;
  left: 65px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .star-6 {
  position: absolute;
  top: 326px;
  left: 17px;
  width: 39px;
  height: 36px;
}

.iphone-pro-max .star-7 {
  position: absolute;
  top: 724px;
  left: 14px;
  width: 39px;
  height: 36px;
}

.iphone-pro-max .text-wrapper-3 {
  top: 318px;
  position: absolute;
  left: 65px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 633px;
  left: 65px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 716px;
  left: 65px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-6 {
  top: 388px;
  left: 65px;
  position: absolute;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 476px;
  left: 65px;
  width: 67px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-8 {
  top: 541px;
  left: 72px;
  position: absolute;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}


page3

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <div class="div"></div>
      <div class="event-registration">Event Registration <br />form</div>
      <div class="div-2"></div>
      <img class="rectangle" src="img/rectangle-8.svg" />
      <div class="text-wrapper">Gender</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">Age</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">Mobile NO.</div>
      <img class="img" src="img/rectangle-11.svg" />
      <div class="rectangle-4"></div>
      <div class="text-wrapper-4">Full name</div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-5">SUBMIT</div>
      <div class="text-wrapper-6">Register No.</div>
    </div>
  </body>
</html>


.frame {
  background-color: #00ff00;
  width: 100%;
  min-width: 430px;
  min-height: 925px;
  position: relative;
}

.frame .div {
  position: absolute;
  top: 24px;
  left: 0;
  width: 430px;
  height: 129px;
  background-color: #121212;
  box-shadow: 0px 4px 4px #00000040;
}

.frame .event-registration {
  position: absolute;
  top: 41px;
  left: 26px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #f70606;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .div-2 {
  position: absolute;
  top: 38px;
  left: 30px;
  width: 5px;
  height: 8px;
  background-color: #f7fb0e;
}

.frame .rectangle {
  position: absolute;
  top: 293px;
  left: 26px;
  width: 360px;
  height: 86px;
}

.frame .text-wrapper {
  position: absolute;
  top: 322px;
  left: 80px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-2 {
  position: absolute;
  top: 405px;
  left: 29px;
  width: 356px;
  height: 68px;
  background-color: #ff00d4;
  border-radius: 150px;
  border: 1px solid;
  border-color: #000000;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 424px;
  left: 80px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-3 {
  position: absolute;
  top: 626px;
  left: 33px;
  width: 356px;
  height: 68px;
  background-color: #ff00d4;
  border-radius: 150px;
  border: 1px solid;
  border-color: #000000;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 640px;
  left: 80px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .img {
  position: absolute;
  top: 506px;
  left: 29px;
  width: 356px;
  height: 68px;
}

.frame .rectangle-4 {
  position: absolute;
  top: 197px;
  left: 22px;
  width: 356px;
  height: 68px;
  background-color: #ff00d4;
  border-radius: 150px;
  border: 1px solid;
  border-color: #000000;
}

.frame .text-wrapper-4 {
  position: absolute;
  top: 214px;
  left: 80px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-5 {
  position: absolute;
  top: 772px;
  left: 60px;
  width: 309px;
  height: 73px;
  background-color: #ff0404;
}

.frame .text-wrapper-5 {
  position: absolute;
  top: 789px;
  left: 130px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-6 {
  position: absolute;
  top: 521px;
  left: 80px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}



```

## OUTPUT:
![alt text](<Screenshot (44).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
