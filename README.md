# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨




<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Styled Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <h1 id="main-title">Welcome to My Page</h1>

  <p class="intro">This is a simple webpage styled with an external CSS file.</p>

  <img src="example.jpg" alt="Example Image" class="styled-image">

  <div class="box">
    <p>This box has margin, padding, and a border!</p>
  </div>

</body>
</html>






/* 1. ID selector */
#main-title {
  color: #2c3e50;
  font-family: 'Georgia', serif;
  text-align: center;
  margin-top: 30px;
}

/* 2. Class selector */
.intro {
  color: #555;
  font-family: Arial, sans-serif;
  font-size: 18px;
  margin: 20px;
  padding: 10px;
}

/* 3. Element selector */
body {
  background-color: #f0f8ff;
  margin: 0;
  padding: 0;
  font-family: 'Verdana', sans-serif;
}

/* Style for image */
.styled-image {
  display: block;
  margin: 20px auto;
  border: 4px solid #3498db;
  padding: 5px;
  width: 300px;
  border-radius: 10px;
}

/* Another class with padding, margin, and border */
.box {
  margin: 30px auto;
  padding: 20px;
  width: 80%;
  border: 2px dashed #8e44ad;
  background-color: #fff;
  font-size: 16px;
}

