# The Trump Countdown

> A satirical doomsday countdown clock tracking the days until (and since) Donald Trump's election, featuring a nuclear video background and email registration.

![Status](https://img.shields.io/badge/status-archived-lightgrey)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Live Demo

[https://izzydoesizzy.github.io/thetrumpcountdown](https://izzydoesizzy.github.io/thetrumpcountdown)

## Overview

"The Trump Countdown" is a tongue-in-cheek doomsday clock that originally counted down the days until the November 9, 2016 U.S. presidential election. Billed as "The 2016 Doomsday Clock: America Edition," the site features a dramatic nuclear explosion video background, a real-time countdown timer (days, hours, minutes, seconds), and a MailChimp-powered email signup for "exclusive survival gear." The tagline reads: "We may have been wrong about Y2K and the Mayan Calendar, but we've got a pretty good feeling about this one."

## Features

- Live countdown timer with days, hours, minutes, and seconds using jQuery downCount plugin
- Fullscreen autoplay nuclear explosion video background (with image fallback for mobile)
- Full-page scrolling navigation powered by fullPage.js
- MailChimp email registration form for "survival gear" updates
- Social sharing integration via AddThis widget
- Google Analytics tracking
- Page loader animation
- Custom 404 error page
- Archive pages for historical snapshots
- Responsive design with Foundation CSS framework

## Screenshots

<!-- ![Screenshot](screenshot.png) -->

## Tech Stack

- HTML5
- CSS3 (Foundation framework, custom styles, responsive breakpoints)
- jQuery 1.11
- fullPage.js (full-page scroll sections)
- jQuery downCount (countdown timer)
- Vegas.js (background slideshow support)
- MailChimp (email signup)
- AddThis (social sharing)
- Google Analytics
- Hosted on GitHub Pages

## Getting Started

### Run Locally

No build step required:

1. **Clone the repository**
   ```bash
   git clone https://github.com/izzydoesizzy/thetrumpcountdown.git
   cd thetrumpcountdown
   ```

2. **Open in browser**
   ```bash
   open index.html
   # or use a local server:
   npx serve .
   ```

### Deploy to GitHub Pages

1. Push to the `gh-pages` branch
2. Go to Settings > Pages > Source: Deploy from branch
3. Site live at `https://izzydoesizzy.github.io/thetrumpcountdown`

## Project Structure

```
thetrumpcountdown/
├── index.html              # Main countdown page
├── 404.html                # Custom 404 error page
├── archive/                # Archived versions of the site
├── css/
│   ├── main.css            # Primary styles
│   ├── main_responsive.css # Responsive breakpoints
│   ├── custom.css          # Custom overrides
│   ├── foundation.min.css  # Foundation framework
│   ├── normalize.css       # CSS reset
│   ├── pageloader.css      # Loading animation
│   └── style-color1.css    # Color scheme
├── js/
│   ├── main.js             # Main application logic
│   ├── jquery.downCount.js # Countdown timer plugin
│   ├── form_script.js      # Form handling
│   └── vendor/             # jQuery, fullPage.js, etc.
├── fonts/                  # OpenSans, Asap web fonts
├── img/                    # Background images, logo
├── vid/                    # Nuclear explosion video (MP4)
├── robots.txt              # Search engine directives
└── Documentation/          # Theme documentation
```

## Tags

`fun-project` `landing-page`

## Created

2016-05

## Status

Legacy -- Originally built for the 2016 U.S. presidential election cycle.

## Author

**Izzy Piyale-Sheard** -- [@izzydoesizzy](https://github.com/izzydoesizzy)
