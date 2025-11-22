🚂 Hanzel's 2nd Birthday Express Invitation

This is a fun, interactive, and fully responsive web invitation designed for Hanzel Drei's 2nd birthday party, utilizing a scrolling train metaphor powered by GSAP. The background features a dynamic, procedurally generated 3D world built with Three.js that scrolls alongside the content.

✨ Key Features (The Carriages)

The invitation is structured like a train, with each section serving as a carriage detailing essential party information:

Engine (Hero Section): Displays the main announcement, the birthday boy's photo, and a functional Countdown Timer showing the days and hours until departure.

Whistle Interaction: Clickable whistle that triggers a smoke burst (particle system) and a screen shake effect.

Carriage 1 - Special Delivery: The formal invitation letter.

Carriage 2 - Celebration: Details about the event time and catering.

Carriage 3 - Station (Location): Embeds a grayscale Google Map of the venue, which becomes colorized on hover, and provides important checkpoint information (Emirates ID).

Carriage 4 - Trip Rules: Key information for guests (colors, requests).

Caboose (Contacts): Contact details for the party conductors (Marcc & Sandey).

Immersive Background: A continuously running 3D scene (trees, clouds, ground) created with Three.js. The 3D camera moves in sync with the user's scroll position, simulating movement along the track.

⚙️ Technologies Used

This project is built using modern web standards and popular libraries:

HTML5 & JavaScript: Core structure and logic.

Tailwind CSS: Utility-first framework for rapid and responsive styling.

GSAP (GreenSock Animation Platform): Used for all scrolling animations, physics-based carriage entry, and continuous engine/wheel movements.

GSAP ScrollTrigger: Manages the synchronized entry animation for each carriage as the user scrolls.

Three.js: Used for rendering the entire 3D background world (ground, trees, clouds, fog).

🚀 How to View Locally

Since this is a single, self-contained HTML file, running it is simple:

Save the file: Ensure the code is saved as index.html.

Open in Browser: Double-click the index.html file. It will open in your default web browser (Chrome, Firefox, etc.).

No server or compilation steps are required, as all assets (GSAP, Three.js, Tailwind, Font Awesome) are loaded via CDN links.
