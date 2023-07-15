# WaveLoader
HTML file:
1. `<!DOCTYPE html>`: Declares the document type as HTML.
2. `<html>`: Opens the HTML document.
3. `<head>`: Begins the head section of the document.
4. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Sets the viewport properties for responsive design.
5. `<title>Water Effect</title>`: Specifies the title of the web page.
6. `<link rel="stylesheet" href="styles.css">`: Links the external CSS file named "styles.css" to the HTML document.
7. `</head>`: Closes the head section of the document.
8. `<body>`: Begins the body section of the document.
9. `<div class="water"></div>`: Creates a `<div>` element with the class "water". This represents the water effect in the HTML document.
10. `</body>`: Closes the body section of the document.
11. `</html>`: Closes the HTML document.


CSS File:

1. `body`: Targets the body element and sets its properties.
   - `width: 100%`: Sets the body's width to 100% of the viewport.
   - `height: 100vh`: Sets the body's height to 100% of the viewport height.
   - `background-color: #555`: Sets the background color of the body to a dark gray.
   - `display: flex`: Specifies the body to use flexbox for its layout.
   - `justify-content: center`: Centers the content horizontally within the body.
   - `align-items: center`: Centers the content vertically within the body.

2. `.water`: Targets elements with the class "water" and sets their properties.
   - `width: 200px`: Sets the width of the element to 200 pixels.
   - `height: 200px`: Sets the height of the element to 200 pixels.
   - `background-color: rgb(6, 216, 244)`: Sets the background color to a light blue shade.
   - `border-radius: 50%`: Rounds the corners of the element, making it a perfect circle.
   - `position: relative`: Positions the element relative to its normal position.
   - `box-shadow`: Adds a box shadow effect to the element, with an inset shadow for inner glow and a normal shadow for a drop shadow effect.
   - `overflow: hidden`: Hides any content that overflows the element's boundaries.

3. `.water:before, .water:after`: Targets the `before` and `after` pseudo-elements of elements with the class "water" and sets their properties.
   - `content: ''`: Adds content to the pseudo-elements.
   - `position: absolute`: Positions the pseudo-elements absolutely within their parent element.
   - `width: 200px`: Sets the width of the pseudo-elements to 200 pixels.
   - `height: 200px`: Sets the height of the pseudo-elements to 200 pixels.
   - `top: -60px`: Positions the pseudo-elements 60 pixels above the main element.
   - `background-color: #fff`: Sets the background color of the pseudo-elements to white.

4. `.water:before`: Targets the `before` pseudo-element of elements with the class "water" and sets additional properties.
   - `border-radius: 45%`: Rounds the corners of the pseudo-element, creating an oval shape.
   - `background: rgba(255, 255, 255, .7)`: Sets the background color of the pseudo-element to a semi-transparent white.
   - `animation: wave 5s linear infinite`: Applies an animation called "wave" to the pseudo-element, with a duration of 5 seconds, linear timing function, and infinite repetition.

5. `.water:after`: Targets the `after` pseudo-element of elements with the class "water" and sets additional properties.
   - `border-radius: 35%`: Rounds the corners of the pseudo-element, creating an oval shape.
   - `background: rgba(255, 255, 255, .3)`: Sets the background color of the pseudo-element to a more transparent white.
   - `animation: wave 5s linear infinite`: Applies the same "wave" animation as before to the pseudo-element.

6. `@keyframes wave`: Defines the animation called "wave" using `@keyframes`.
   - `0%`: Specifies the starting keyframe of the animation.
      - `transform: rotate(0)`: Sets the rotation of the pseudo-elements to 0 degrees.
   - `100%`: Specifies the ending keyframe of the animation.
      - `transform: rotate(360deg)`: Sets the rotation of the pseudo-elements to 360 degrees.

Output:


<img width="244" alt="Screenshot 2023-07-15 113218" src="https://github.com/AmishaSharma12002/WaveLoader/assets/92213190/d2f5c8f6-ba8e-423a-830f-e916424e96b5">

