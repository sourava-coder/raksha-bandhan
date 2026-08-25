Raksha Bandhan - Interactive Web Experience
A simple and interactive Raksha Bandhan digital card experience built with HTML, CSS and vanilla JavaScript.

## Features
Animated opening sequence , Interactive Rakhi animation
, Drag and drop Rakhi tying interaction
,Personalized greeting card
,Custom sibling name input
,Flip card interaction
,Decorative particle effects
,Animated golden thread cursor
,Responsive design for desktop and mobile
,Reduced motion support
,Dynamically generated Rakhi SVG illustrations
 and No JavaScript frameworks or libraries required

## Tech Stack
HTML5
CSS3
JavaScript
SVG
Google Fonts


## Getting Started
Clone the repository
git clone https://github.com/sourava-coder/raksha-bandhan.git
Open the project
cd raksha-bandhan

Open index.html directly in your browser.

Alternatively, use VS Code with the Live Server extension.

## How It Works
The opening animation starts automatically.
Click the gift to begin the experience.
Scroll to the Rakhi interaction section.
Drag the Rakhi onto the wrist.
After successfully tying the Rakhi, the personalized card section becomes available.
Enter the sibling's name.
Click the card to reveal the personalized message.

## Customization
Change the Message

Find the following variable in the JavaScript:

const defaultMsg = "Whatever fights we've had, whatever distance comes between us — this thread says I've still got you. Always.";

Replace it with your own message.

Change the Card Title
<p>Happy Raksha Bandhan</p>
Change the Final Message
<p class="finale-text">Happy Raksha Bandhan</p>
<p class="finale-sub">may the thread outlast every argument</p>
Change the Color Theme

The main colors are defined in the CSS variables:

:root{
  --maroon:#5C0F1F;
  --maroon2:#7A1B2E;
  --beige:#E7D3AC;
  --cream:#FBF3E3;
  --gold:#C9A227;
  --gold-light:#E6C158;
  --ink:#2A140C;
}

Modify these values to create your own color theme.
Responsive Design
The website is designed to work across different screen sizes using responsive CSS, viewport-based sizing, and mobile-specific behavior.
The custom cursor is automatically disabled on touch devices.

## Browser Support
The project works best on modern versions of:
Google Chrome
Microsoft Edge
Mozilla Firefox
Safari
## License
This project is free to use, modify, and customize for personal and educational purposes.

## SOURAVA CODER
Created as an interactive digital Raksha Bandhan experience.
