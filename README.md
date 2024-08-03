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


Understanding the CSS Code
Gradient Background
The provided CSS code creates a dynamic gradient background for an element with the class .gradient-background.

background: linear-gradient(300deg, #00bfff, #ff4c68, #ef8172);: This line defines a linear gradient with three color stops: #00bfff, #ff4c68, and #ef8172. The angle of the gradient is set to 300 degrees.
background-size: 180% 180%;: This line sets the size of the gradient to 180% in both width and height, creating a stretched and repeating effect.
animation: gradient-animation 18s ease infinite;: This line applies an animation named gradient-animation to the element. The animation lasts 18 seconds, uses an ease timing function, and repeats infinitely.
The @keyframes rule defines the gradient-animation by changing the background position over time, creating a smooth transition of the gradient.

Text Styles
The rest of the CSS code defines styles for various text elements on the page:

.top-text: Sets text alignment, font style, font family, and color for top-level text.
.name: Styles the name with a specific font, size, and color.
.pronouns: Styles the pronouns with a specific font, color, and size.
.logo: Styles the logo text with a specific font, color, and size.
.nav-text: Styles the navigation text with a specific font, size, and color.
.btn: Styles buttons with white color and larger font size.
.btn1: Styles another type of button with white color, solid border, margin, and padding.
General Styles
The code also includes general styles:

* { background-color: rgb(18, 18, 18); }: Sets a black background color for all elements.
.home: Styles the main content area with specific colors, outline, and margins.
.text-hero: Styles hero text with white color and larger font size.
.image: Adds margin-top to the image container.
.container: Centers the container element.
.w-container: Sets a maximum width for the container.
.nav-item: Styles navigation items with larger font size and italic style.
.section: Adds padding to sections.
.navpad: Adds padding to the navigation area.
.namepad: Adds padding to the name section.
.manpad: Adds padding to the recent works section.
.card-text: Styles card text with color and font size.
.card-title: Styles card titles with color and font size.
.mantxt, .cartxt: Styles section titles with specific font, size, and color.
.follow-along: Styles the follow-along section with color, padding, and text alignment.
.social-link: Styles social media links with border, padding, and rounded corners.
.moth: Positions the moth image with z-index, margin, and display properties.
