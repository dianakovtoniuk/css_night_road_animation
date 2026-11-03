# Night Mode Road Animation

A small day/night scene built with HTML, CSS and a few lines of JavaScript. Cars drive across a looping city road, and clicking the sun switches between day and night.

## Features

- Endlessly scrolling road background using a CSS keyframe animation
- Two cars driving in opposite directions at different speeds (the second one is mirrored with `rotateY`)
- Click the sun to toggle night mode: the sky darkens and the sun turns into a crescent moon
- Smooth transitions between the two states

## How it works

`main.js` listens for a click on the sun and toggles a `night` class on the scene. All the visual changes happen in CSS through the `.scene.night` selectors, so the script stays tiny.

## Structure

```
night-mode-road-animation/
├── index.html
├── style.css
├── main.js
├── bg.png
├── car.gif
└── ImageSource.txt
```

## Usage

Clone the repo and open `index.html` in a browser. No build step or dependencies are needed. Click the sun to toggle night mode.

## Customization

- Change the road scroll speed in the `animateBg` animation (`25s`)
- Change the car speeds in the `car1` and `car2` animations
- Edit the sky colors in the `.scene` and `.scene.night` rules
- Add more cars by duplicating an `<img>` tag and defining a new animation

## Credits

Illustrations are from Freepik. See `ImageSource.txt` for the original authors and links. All credit goes to the original creators.
