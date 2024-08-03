# portfolio-website

Vinayak Rohila Portfolio Website
This is the code for Vinayak Rohila's portfolio website. It uses HTML, CSS, Javascript, and Bootstrap to create a visually appealing and informative webpage showcasing Vinayak's skills and experience.

Breakdown of the HTML code:
DOCTYPE Declaration: <!DOCTYPE html> declares the document type as HTML.
HTML Tag: <html lang="en"> defines the root element of the webpage and specifies the language as English.
Head Section:
<head> element contains meta information about the webpage.
<meta charset="UTF-8">: Defines the character encoding as UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Makes the webpage responsive by adjusting the width and initial zoom level for different devices.   
<title>Vinayak</title>: Sets the title of the webpage.
Links to external resources:
<link rel="icon" href="./images/WhatsApp_Image_2023-08-23_at_00.38.08-removebg-preview.png" type="image/x-icon" style="border-radius: 50%;">: Links the website icon (favicon).
Links to Bootstrap CSS and Javascript libraries for styling and interactivity.
Links to Google Fonts for custom fonts used on the webpage.
Scripts to load and configure the custom fonts.
Body Section:
<body class="home">: Defines the visible content of the webpage with a class name "home".
Audio Element: <audio autoplay loop src="./data/Epic Violin Music NO Copyright royalty free music violin soundtrack + download link.mp3">: Plays background music on page load (autoplay) and loops indefinitely.
Container Div: <div class="container navpad">: Creates a container element with class names "container" and "navpad" for layout purposes.
Header: <header class="d-flex flex-wrap justify-content-center py-3 mb-4 ">: Defines the header section with flexbox styling and spacing classes.
Logo and Navigation Links:
Website logo with a link to the homepage.
Navigation links for "Selected Work", "Resume", and "Get In Touch" using Bootstrap button classes.
Hero Section: <section class="namepad">: Defines the hero section with a class name "namepad".
Container element for content positioning.
Hero title: <h1>Vinayak Rohila</h1>
Pronouns: <h2>[he / him]</h2>
Hero subheader describing Vinayak's skills and location.
Recent Works Section: <section class="manpad"> : Defines the recent works section with a class name "manpad".
Container element.
Title: <h2>Recent Works</h2>
Card layout for displaying project descriptions and images using Bootstrap classes.
Additional Sections:
"Sword" section with a decorative image.
"Certificates" section showcasing certificates using a Bootstrap carousel component.
"Achievements" section displaying achievements with a masonry layout for responsive positioning.
"Follow Along" section for social media links.
Scripts:
Links Bootstrap Javascript library for functionalities.
Script for the masonry layout in the "Achievements" section.


## CSS Style Explanation

### Understanding the Code

This CSS code defines various styles for different elements on a webpage. It covers aspects like background, text formatting, layout, and positioning.

### Breakdown of Styles

#### Gradient Background

```css
.gradient-background {
  background: linear-gradient(300deg, #00bfff, #ff4c68, #ef8172);
  background-size: 180% 180%;
  animation: gradient-animation 18s ease infinite;
}

@keyframes gradient-animation {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}
```

* Creates a gradient background with three colors: `#00bfff`, `#ff4c68`, and `#ef8172`.
* Sets the background size to 180% for both width and height to create a repeating pattern.
* Applies an animation called `gradient-animation` which smoothly shifts the gradient position over 18 seconds.

#### Text Styles

```css
.top-text, .name, .pronouns, .logo, .nav-text, .btn, .btn1, .text-hero, .card-text, .card-title, .blockquote, .mantxt, .cartxt, .follow-along, .nav-item {
  /* ... text properties ... */
}
```

* Defines various text styles for different elements using properties like `font-family`, `font-size`, `color`, `text-align`, etc.
* These styles control the appearance of headings, paragraphs, buttons, and other text elements on the page.

#### Layout and Positioning

```css
.home, .container, .w-container, .section, .navpad, .namepad, .manpad, .image, .sword, .moth {
  /* ... layout and positioning properties ... */
}
```

* Applies styles for layout and positioning using properties like `margin`, `padding`, `display`, `position`, `width`, etc.
* Controls the overall structure and placement of elements on the page.

### Key Points

* The code uses a combination of custom and predefined class names to target specific elements.
* It employs various CSS properties to achieve desired visual effects and layout.
* The code includes styles for text formatting, background, animations, and element positioning.

### Additional Notes

* The code uses custom properties like `var(--charcoal)` and `var(--eggshell)` which are likely defined elsewhere.
* The code might be part of a larger stylesheet with additional rules and definitions.
* Some class names like `w-container` might be specific to a particular framework or library.

**Would you like to focus on a specific part of the code, or do you have any questions about how it works?** 
