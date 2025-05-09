# Ex09 Event Registration Web Application
## Date:09/05/2025

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
NAME: A PRANEYA
REGISTER NO: 212224110045
```
HOMEPAGE 

HTML
```

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="loginpage-1">
<img src="images/logo-1-2.png" class="logo-1-2" alt="logo-1" />
<img src="images/node-3.png" class="node-3" alt="0be9422fa52b33d9296fc549e2cef66e-1" />
<p class="text-4"><span class="text-rgb-255-157-74">SAVEETHA’S SPEAKERS FORUM </span></p>
<p class="text-5"><span class="text-rgb-245-238-220">THREADLINE  SPEECH 
</span></p>
<p class="text-6"><span class="text-rgb-245-238-220">CONTEST</span></p>
<img src="images/rectangle-2-7.svg" class="rectangle-2-7" alt="rectangle-2" />
<img src="images/rectangle-3-8.svg" class="rectangle-3-8" alt="rectangle-3" />
<p class="text-9"><span class="text-black">LOGIN</span></p>
<p class="text-10"><span class="text-black">REGISTER</span></p>
</div>

</body>
</html>
```
CSS
```

/* Add font files for Lilita One */
@font-face {
  font-family: 'Lilita One';
  src: url('fonts/lilita-one.woff2') format('woff2'),
       url('fonts/lilita-one.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Inknut Antiqua */
@font-face {
  font-family: 'Inknut Antiqua';
  src: url('fonts/inknut-antiqua.woff2') format('woff2'),
       url('fonts/inknut-antiqua.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-lilita-one: 'Lilita One', sans-serif;
  --font-family-inknut-antiqua: 'Inknut Antiqua', sans-serif;
  --text-rgb-255-157-74: rgba(255, 157, 74, 1);
  --text-rgb-245-238-220: rgba(245, 238, 220, 1);
  --text-black: rgba(0, 0, 0, 1);
}

.text-rgb-255-157-74 {
  color: var(--text-rgb-255-157-74);
}

.text-rgb-245-238-220 {
  color: var(--text-rgb-245-238-220);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.logo-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-lilita-one);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-255-157-74);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-lilita-one);
  font-weight: normal;
  font-size: 35px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-245-238-220);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-lilita-one);
  font-weight: normal;
  font-size: 35px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-245-238-220);
}

.rectangle-2-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 50px;
  fill: rgba(105, 202, 240, 1);
  border: none;
  outline: none;
}

.rectangle-3-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 50px;
  fill: rgba(105, 202, 240, 1);
  border: none;
  outline: none;
}

.text-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inknut-antiqua);
  font-weight: normal;
  font-size: 25px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inknut-antiqua);
  font-weight: normal;
  font-size: 25px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.loginpage-1 {
@media (max-width: 1440px) {
  .loginpage-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .loginpage-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```
RULES AND REGULATION PAGE

HTML
```

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="rulesnreg-1">
<img src="images/node-2.png" class="node-2" alt="dark-purple-lights-h472i7rf9dlsqtov-1" />
<p class="text-3"><span class="text-rgb-255-157-74">RULES AND REGULATIONS</span></p>
<div class="rectangle-4-4"></div>
<img src="images/ellipse-2-5.svg" class="ellipse-2-5" alt="ellipse-2" />
<p class="text-6"><span class="text-rgb-245-238-220">A team must have 3 members.

The prompt will be given on-spot.

2 minutes pre-talk time.

Induldge the emotion or tone during talk.</span></p>
<img src="images/ellipse-1-7.svg" class="ellipse-1-7" alt="ellipse-1" />
<img src="images/ellipse-3-8.svg" class="ellipse-3-8" alt="ellipse-3" />
<img src="images/ellipse-4-9.svg" class="ellipse-4-9" alt="ellipse-4" />
<img src="images/ellipse-5-10.svg" class="ellipse-5-10" alt="ellipse-5" />
</div>

</body>
</html>
```
CSS
```

/* Add font files for Lilita One */
@font-face {
  font-family: 'Lilita One';
  src: url('fonts/lilita-one.woff2') format('woff2'),
       url('fonts/lilita-one.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-lilita-one: 'Lilita One', sans-serif;
  --text-rgb-255-157-74: rgba(255, 157, 74, 1);
  --text-rgb-245-238-220: rgba(245, 238, 220, 1);
}

.text-rgb-255-157-74 {
  color: var(--text-rgb-255-157-74);
}

.text-rgb-245-238-220 {
  color: var(--text-rgb-245-238-220);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-lilita-one);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-255-157-74);
}

.rectangle-4-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(110, 74, 167, 1);
  border-radius: 45px;
  opacity: 0.8999999761581421;
}

.ellipse-2-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(245, 238, 220, 1);
  border: none;
  outline: none;
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-lilita-one);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-245-238-220);
}

.ellipse-1-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(245, 238, 220, 1);
  border: none;
  outline: none;
}

.ellipse-3-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(245, 238, 220, 1);
  border: none;
  outline: none;
}

.ellipse-4-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(245, 238, 220, 1);
  border: none;
  outline: none;
}

.ellipse-5-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(245, 238, 220, 1);
  border: none;
  outline: none;
}

.rulesnreg-1 {
@media (max-width: 1440px) {
  .rulesnreg-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .rulesnreg-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(255, 255, 255, 1);
  opacity: 0.9800000190734863;
}
```
REGISTRATION FORM

HTML
```

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="registration-form-1">
<div class="android-compact-2-2">
<img src="images/node-3.png" class="node-3" alt="dark-purple-lights-h472i7rf9dlsqtov-1" />
<p class="text-4"><span class="text-rgb-255-157-74">REGISTRATION FORM</span></p>
<div class="rectangle-4-5"></div>
<p class="text-6"><span class="text-black">TEAM MEMBER 3</span></p>
<div class="rectangle-5-7"></div>
<p class="text-8"><span class="text-black">TEAM MEMBER 1</span></p>
<p class="text-9"><span class="text-black">TEAM MEMBER 2</span></p>
<p class="text-10"><span class="text-rgb-3-0-0">NAME</span></p>
<p class="text-11"><span class="text-rgb-3-0-0">NAME</span></p>
<p class="text-12"><span class="text-rgb-3-0-0">NAME</span></p>
<div class="rectangle-12-13"></div>
<p class="text-14"><span class="text-rgb-3-0-0">DEPT
</span></p>
<p class="text-15"><span class="text-rgb-3-0-0">REG NO.</span></p>
<p class="text-16"><span class="text-rgb-3-0-0">DEPT
</span></p>
<p class="text-17"><span class="text-rgb-3-0-0">DEPT
</span></p>
<p class="text-18"><span class="text-rgb-3-0-0">REG NO.</span></p>
<p class="text-19"><span class="text-rgb-3-0-0">REG NO.</span></p>
<div class="rectangle-13-20"></div>
<div class="rectangle-14-21"></div>
<div class="rectangle-15-22"></div>
<img src="images/rectangle-16-23.svg" class="rectangle-16-23" alt="rectangle-16" />
<div class="rectangle-17-24"></div>
<div class="rectangle-18-25"></div>
<div class="rectangle-19-26"></div>
<div class="rectangle-21-27"></div>
<p class="text-28"><span class="text-black">SUBMIT</span></p>
</div>
</div>

</body>
</html>
```
CSS
```

/* Add font files for Lilita One */
@font-face {
  font-family: 'Lilita One';
  src: url('fonts/lilita-one.woff2') format('woff2'),
       url('fonts/lilita-one.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Londrina Solid */
@font-face {
  font-family: 'Londrina Solid';
  src: url('fonts/londrina-solid.woff2') format('woff2'),
       url('fonts/londrina-solid.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Markazi Text */
@font-face {
  font-family: 'Markazi Text';
  src: url('fonts/markazi-text.woff2') format('woff2'),
       url('fonts/markazi-text.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-lilita-one: 'Lilita One', sans-serif;
  --font-family-londrina-solid: 'Londrina Solid', sans-serif;
  --font-family-markazi-text: 'Markazi Text', sans-serif;
  --text-rgb-255-157-74: rgba(255, 157, 74, 1);
  --text-black: rgba(0, 0, 0, 1);
  --text-rgb-3-0-0: rgba(3, 0, 0, 1);
}

.text-rgb-255-157-74 {
  color: var(--text-rgb-255-157-74);
}

.text-black {
  color: var(--text-black);
}

.text-rgb-3-0-0 {
  color: var(--text-rgb-3-0-0);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-lilita-one);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-255-157-74);
}

.rectangle-4-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(110, 74, 167, 1);
  border-radius: 55px;
  opacity: 0.8999999761581421;
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-londrina-solid);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-5-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(245, 238, 220, 1);
  border-radius: 15px;
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-londrina-solid);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-londrina-solid);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-markazi-text);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-3-0-0);
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-markazi-text);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-3-0-0);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-markazi-text);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-3-0-0);
}

.rectangle-12-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(245, 238, 220, 1);
  border-radius: 15px;
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-markazi-text);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-3-0-0);
}

.text-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-markazi-text);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-3-0-0);
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-markazi-text);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-3-0-0);
}

.text-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-markazi-text);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-3-0-0);
}

.text-18 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-markazi-text);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-3-0-0);
}

.text-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-markazi-text);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-3-0-0);
}

.rectangle-13-20 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(245, 238, 220, 1);
  border-radius: 15px;
}

.rectangle-14-21 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(245, 238, 220, 1);
  border-radius: 15px;
}

.rectangle-15-22 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(245, 238, 220, 1);
  border-radius: 15px;
}

.rectangle-16-23 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 15px;
  fill: rgba(245, 238, 220, 1);
  border: none;
  outline: none;
}

.rectangle-17-24 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(245, 238, 220, 1);
  border-radius: 15px;
}

.rectangle-18-25 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(245, 238, 220, 1);
  border-radius: 15px;
}

.rectangle-19-26 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(245, 238, 220, 1);
  border-radius: 15px;
}

.rectangle-21-27 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(81, 117, 93, 1);
  border-radius: 500px;
}

.text-28 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-lilita-one);
  font-weight: normal;
  font-size: 28px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.android-compact-2-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(255, 255, 255, 1);
  opacity: 0.9800000190734863;
}

.registration-form-1 {
@media (max-width: 1440px) {
  .registration-form-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .registration-form-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```
THANK YOU PAGE

HTML
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="thankyou-1">
<div class="android-compact-2-2">
<img src="images/node-3.png" class="node-3" alt="dark-purple-lights-h472i7rf9dlsqtov-1" />
<div class="rectangle-4-4"></div>
<p class="text-5"><span class="text-rgb-255-157-74">THANK YOU!</span></p>
<div class="rectangle-20-6"></div>
<p class="text-7"><span class="text-black"> Contact:
A PRANEYA
praneyaarulkumar@gmail.com
</span></p>
</div>
</div>

</body>
</html>
```
CSS
```

/* Add font files for Luckiest Guy */
@font-face {
  font-family: 'Luckiest Guy';
  src: url('fonts/luckiest-guy.woff2') format('woff2'),
       url('fonts/luckiest-guy.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Libre Bodoni */
@font-face {
  font-family: 'Libre Bodoni';
  src: url('fonts/libre-bodoni.woff2') format('woff2'),
       url('fonts/libre-bodoni.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-luckiest-guy: 'Luckiest Guy', sans-serif;
  --font-family-libre-bodoni: 'Libre Bodoni', sans-serif;
  --text-rgb-255-157-74: rgba(255, 157, 74, 1);
  --text-black: rgba(0, 0, 0, 1);
}

.text-rgb-255-157-74 {
  color: var(--text-rgb-255-157-74);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-4-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(110, 74, 167, 1);
  border-radius: 45px;
  opacity: 0.8999999761581421;
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-luckiest-guy);
  font-weight: normal;
  font-size: 42px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-255-157-74);
}

.rectangle-20-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(51, 48, 48, 0.38);
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-libre-bodoni);
  font-weight: normal;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.android-compact-2-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(255, 255, 255, 1);
  opacity: 0.9800000190734863;
}

.thankyou-1 {
@media (max-width: 1440px) {
  .thankyou-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .thankyou-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```
## OUTPUT:

![alt text](<Screenshot (10).png>)

![alt text](<Screenshot (11).png>)

![alt text](<Screenshot (12).png>)

![alt text](<Screenshot (13).png>)

## RESULT:

The program to design, develop and deploy a web application for event registration is completed successfully.
