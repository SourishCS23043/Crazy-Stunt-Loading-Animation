# Crazy Stunt Loading Animation

A vibrant and energetic loading animation inspired by wild stunt performances, created using SVG and CSS animations. This animation offers a visually engaging loading indicator that’s lightweight, smooth, and fully responsive.

---

## Table of Contents

- [Demo](#demo)  
- [How It Works](#how-it-works)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Customization](#customization)  
- [Browser Support](#browser-support)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Demo

You can see the animation live by opening the `index.html` file in any modern browser.  
*(Add a GIF or link to live demo if available)*

---

## How It Works

The animation is built using:

- **SVG graphics**: A scalable vector graphic composed of circles and paths that form the "stunt" shapes.  
- **Linear gradients and masks**: These create smooth color transitions and layered effects on the SVG shapes.  
- **CSS animations**: Keyframe animations manipulate stroke dash offsets and rotation transforms to produce dynamic, looping motion reminiscent of stunt movement.  

The main animated elements are:

- `.sp__ring`: The base circular ring that serves as a subtle background.  
- `.sp__worm1`, `.sp__worm2`, `.sp__worm2-1`: Different path segments that animate with stroke dash offsets and rotation to create continuous looping motion.  

Animations are timed precisely for a smooth and continuous effect, and colors adapt based on the user’s color scheme preference (light/dark mode).

---

## Features

- Pure SVG + CSS animation — no JavaScript required  
- Responsive size using `em` units, easily scalable  
- Supports light and dark themes using CSS media queries  
- Smooth and continuous looping with easing functions  
- Lightweight and fast-loading  

---

## Installation

1. Clone the repo:

```bash
git clone https://github.com/SourishCS23043/Crazy-Stunt-Loading-Animation.git
