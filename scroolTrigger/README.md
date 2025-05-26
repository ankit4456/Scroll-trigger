# Scroll-trigger
This project uses GSAP's ScrollTrigger plugin to create scroll-based animations.





🚀 GSAP ScrollTrigger Animation – Avengers Themed
This mini web project demonstrates how to use GSAP and ScrollTrigger to create stunning scroll-based animations. The theme pays tribute to the Avengers universe by animating iconic content as you scroll.

🔥 Features
GSAP Animation: Smooth entrance animations using scaling, rotation, and opacity.

ScrollTrigger Integration: Scroll-based reveal of headings using horizontal motion and fading.

Responsive Layout: Designed with flexbox and styled for full-screen display on any device.

Marvel Tribute: Includes a clickable Avengers logo leading to the official Marvel site.

🛠️ Tech Stack
HTML5

CSS3

JavaScript (ES6+)

GSAP 3.13.0

GSAP ScrollTrigger Plugin

🎥 Animation Overview
Element	Animation Type	Trigger
#page1	Scale from 20 → 1, fade in, rotate 120°	On page load
#page2 h2	Slide in from right → center	Scroll into view (70% of viewport)
#page2 h3	Slide in from left → center	Scroll into view (70% of viewport)

Markers are enabled for debugging and alignment.

📁 File Structure
plaintext
Copy
Edit
/ (root)
│
├── index.html        → Main HTML structure
├── style.css         → Styling for layout and animations
├── script.js         → GSAP + ScrollTrigger animation logic
├── favicon.png       → Favicon for browser tab
🧠 How It Works
gsap.from() is used to animate elements from an initial state.

ScrollTrigger watches when elements enter the viewport and triggers the defined animation.

toggleActions controls what happens on entering and leaving the scroll position.

📸 Preview

✅ Setup Instructions
Clone this repo or download the files.

Open index.html in your browser.

Scroll down to see the animation in action.

📌 Where to Put the Code
HTML: Save the HTML content in a file called index.html.

CSS: Save the CSS inside style.css in the same folder.

JavaScript: Save the GSAP code inside script.js in the same folder.

Favicon: Place a favicon image named favicon.png in the same directory.

