# Natours — Exciting Tours for Adventurous People

A responsive nature tour landing page built with **HTML**, **CSS**, and **Sass (SCSS)**, showcasing advanced CSS animations, transitions, and modern layout techniques.

## Overview

Natours is a fictional outdoor adventure travel platform. The project focuses heavily on CSS animations, creative UI components, and a fully responsive float-based grid system built from scratch.

## Sections

- **Header** — Full-screen hero with animated heading and a call-to-action button
- **About** — Two-column layout with a floating overlapping photo composition
- **Features** — Four-column grid highlighting key benefits with icon fonts
- **Popular Tours** — Three tour cards with a CSS 3D flip effect on hover, each showing details on the front and pricing/booking on the back:
  - *The Sea Explorer* — $297, 3 days, easy
  - *The Forest Hiker* — $497, 7 days, medium
  - *The Snow Adventurer* — $897, 5 days, hard
- **Stories** — Customer testimonials with a background video, shape-clipped portrait images, and a hover caption effect
- **Booking Form** — Reservation form with animated floating labels, custom radio buttons, and a background image blend effect
- **Footer** — Responsive logo with `<picture>` / `srcset` and navigation links
- **Popup Modal** — Pure CSS booking popup triggered via anchor links

## Tech Stack

- HTML5
- CSS3
- Sass (SCSS)
- Float-based custom grid system
- Google Fonts — *Lato*
- Icon fonts for feature icons

## Key CSS Concepts Practised

- CSS keyframe animations (`@keyframes`) for the hero section entrance
- 3D card flip effect using `perspective`, `rotateY`, and `backface-visibility`
- Custom float grid system (halves, thirds, quarters)
- Responsive images with `srcset`, `sizes`, and `<picture>` for art direction
- Shape-clipped images with `clip-path` and `shape-outside`
- Background video with `<video>` as a decorative section background
- Animated floating form labels using the adjacent sibling selector
- Pure CSS modal/popup with `:target` pseudo-class
- CSS checkbox hack for the fullscreen navigation overlay
- BEM naming convention throughout

## Project Structure

```
natours-project/
├── index.html
├── assets/
│   └── css/
│       └── main.css
├── sass/
│   └── main.scss
└── img/
```
