# Pure CSS Animated Image Slideshow

A smooth, responsive, and interactive image slideshow built entirely using *HTML5* and *CSS3* (no JavaScript required). The slideshow functions automatically using CSS @keyframes animations and includes smooth hover interactions.

## 🚀 Features

* *Pure CSS Animation:* Automatic transitions between slides driven by @keyframes.
* *Hover to Pause:* The slideshow automatically pauses its movement when a user hovers over the container.
* *Smooth Zoom Effect:* Images scale up elegantly (scale(1.12)) and brighten when individual slides are hovered.
* *Animated Captions:* Text overlays slide up from the bottom with a smooth gradient background upon hovering over a slide.
* *Responsive Design:* Utilizes flexbox layout and object-fit: cover to maintain aspect ratios perfectly.

## 📁 File Structure

    ├── slidehover.html   # Main HTML file containing the structure and embedded styles
    └── README.md         # Documentation file
    
## 🛠️ Code Breakdown

### 1. HTML Structure
The HTML consists of a main wrapper (.slideshow-container) holding a track (.slides-track) that contains three individual slides (.slide). Each slide contains an image fetched from standard placeholder URLs and a corresponding caption overlay.

### 2. Core CSS Features Used
* *Flexbox Layout:* Active on the body for centering and .slides-track to align all three slides horizontally.
* *CSS Keyframes (@keyframes slide):* Moves the .slides-track using translateX() offsets (0%, -33.333%, and -66.666%) to display each image one after the other.
* *Transitions:* Applied on images and captions for fluid animations (transform, opacity, filter).

## 💻 How to Run the Project

1. Save the code into a file named slidehover.html.
2. Open the file directly in any modern web browser (Google Chrome, Microsoft Edge, etc.).
3. Enjoy the automated slideshow loops and interact by hovering your mouse over it!
