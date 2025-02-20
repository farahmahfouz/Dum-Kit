# JavaScript Drum Kit

This project is a simple drum kit that allows users to play different drum sounds by pressing specific keys on their keyboard.

## Features
- Press a key (A, S, D, F, G, H, J, K, L) to play a corresponding drum sound.
- Visual feedback when a key is pressed.
- Sounds restart when a key is pressed multiple times.

## Technologies Used
- HTML
- CSS
- JavaScript

## How It Works
1. The HTML file contains a set of `<div>` elements representing the drum keys and `<audio>` elements containing the sound files.
2. JavaScript listens for `keydown` events, finds the corresponding audio element, and plays the sound.
3. CSS transitions provide a visual effect when a key is pressed.

## Deployment
This project is deployed on Vercel. You can check it out here:
[Vercel Deployment Link](https://dum-kit-farah-mahfouzs-projects.vercel.app/)

## How to Run Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/farahmahfouz/Dum-Kit.git
   ```
2. Navigate to the project folder:
   ```sh
   cd js-drum-kit
   ```
3. Open `index.html` in your browser.

## License
This project is open-source and available under the MIT License.

