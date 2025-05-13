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




/* styles.css */

/* Element Selector (h1) */
h1 {
  color: #2c3e50; /* Dark blue-gray */
  font-family: 'Arial', sans-serif;
  text-align: center;
  margin-bottom: 20px;
}

/* Class Selector (.intro) */
.intro {
  font-size: 1.1em;
  color: #555; /* Medium gray */
  line-height: 1.5;
  margin-bottom: 30px;
  padding: 10px;
  border-left: 4px solid #3498db; /* Blue accent border */
  background-color: #f9f9f9;
}

/* ID Selector (#main-content) */
#main-content {
  background-color: #ffffff;
  padding: 20px;
  border-radius: 8px; /* Rounded corners */
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Subtle shadow */
  margin-bottom: 30px;
}

#main-content p {
  margin-bottom: 16px;
  color: #444;
}

/* Image Styling */
img {
  border-radius: 50%; /* Make it a circle */
  width: 150px; /* Fixed width */
  height: 150px; /* Fixed height */
  object-fit: cover; /* Ensure image covers the whole area */
  border: 5px solid #8e44ad; /* Purple border */
  margin: 20px auto; /* Center the image */
  display: block;
}

/* Button Styling */
.button {
  background-color: #3498db;
  color: white;
  padding: 12px 25px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 1em;
  transition: background-color 0.3s ease;
  margin-top: 10px;
}

.button:hover {
  background-color: #217dbb;
}

