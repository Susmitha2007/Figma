# Ex09 Event Registration Web Application
## Date:13-03-2026

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
Layer 1:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-plus-2-1">
<p class="text-2"><span class="text-black">List Of Events</span></p>
<p class="text-3"><span class="text-black">Cricket
Volley Ball
Badminton
100 MTS
200 MTS
400 MTS</span></p>
</div>

</body>
</html>

Layer 2:

:root {
  --font-family-inter: 'Inter', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
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

/* Prototype Links */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.text-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 36px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 300;
  font-size: 48px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.iphone-16-plus-2-1 {
@media (max-width: 1440px) {
  .iphone-16-plus-2-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-plus-2-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(95, 167, 222, 1);
}

## OUTPUT:

<img width="1328" height="670" alt="Screenshot 2026-03-13 111225" src="https://github.com/user-attachments/assets/10a55216-32db-417b-bc1b-d8fed1f9ba8b" />

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
