# Pac-Man Animation

This project is a simple Pac-Man animation where Pac-Man moves back and forth across the screen, bouncing off the edges, while switching between open and closed mouth images. The animation is implemented using HTML, CSS, and JavaScript.

## Demo

You can view a live demo of the project [here](#).  
*(Replace the `#` with the URL to your hosted project, if available.)*

## Features

- Pac-Man character that animates between open and closed mouth images.
- Smooth movement across the screen.
- Bounces off screen edges and reverses direction.
- Dynamic switching between right-facing and left-facing images depending on the direction of movement.
- Game starts when the "Start" button is clicked.

## How It Works

This project demonstrates simple DOM manipulation and animation using JavaScript:
- **HTML** provides the structure with a `button` and an `img` element for Pac-Man.
- **CSS** styles Pac-Man’s size and position on the screen.
- **JavaScript** manages Pac-Man's movement, animation frame switching, and direction changes when it reaches the edges of the screen.

### Main Concepts
1. **Image Switching**: The Pac-Man image changes every 200ms, alternating between two images for open and closed mouths.
2. **Movement**: Pac-Man moves across the screen by adjusting its `left` property in small increments, and reverses direction when it hits the screen edges.
3. **Direction Handling**: Pac-Man flips between right-facing and left-facing images based on its current direction.

## Installation

To run this project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/pacman-animation.git
   cd pacman-animation
   open index.html
## Usage
After opening the project in your browser, click the "Start" button to begin the animation. Pac-Man will start moving across the screen, bouncing off the edges and switching between open and closed mouth images.

Modifications:
You can adjust the speed of Pac-Man by changing the vel variable in the JavaScript code.
The images for Pac-Man can be updated by replacing the image files in the imagesRight and imagesLeft arrays with your own images.
