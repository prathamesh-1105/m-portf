# Mahek Lingwat — Product Designer Portfolio

The personal portfolio website of Product Designer Mahek Lingwat.

## Overview

A modern, responsive portfolio displaying product design case studies, interactive project showcases, and design explorations.

### Features
- **Canvas-Scaled Responsive Layout**: Uses a responsive design canvas that dynamically scales to fit any screen resolution smoothly.
- **Interactive macOS Desktop Projects Window**:
  - Live video previews for case studies (*Flebo*, *Menteiz Aviation*, *Kargo360*).
  - Navigation controls, play/pause toggles, and dock icon switching with active indicators.
- **Custom Morphing Cursor**: Context-aware custom cursor that transforms into labels and icons over interactive elements.
- **Choreographed Entry Animations**: IntersectionObserver-driven scroll reveals and WAAPI (Web Animations API) physics simulation for tossed elements.
- **Complete Case Study Pages**:
  - `flebo.html`: Diagnostics booking and report experience redesign.
  - `menteiz.html`: B2B Aviation & Cargo platform redesign.
  - `kargo360.html`: Air cargo flight manifest and pickup operations app redesign.
- **Rich Asset Suite**: High-resolution graphics, responsive assets, and embedded demonstration video clips.

## Project Structure

```text
├── index.html        # Main portfolio homepage
├── styles.css        # Homepage styling, animations, and layout
├── case.css          # Case studies layout and design system
├── flebo.html        # Re-design Flebo case study
├── menteiz.html      # Re-design Menteiz Aviation case study
├── kargo360.html     # Re-design Kargo360 App case study
├── analytics.js      # Interaction tracking and telemetry handlers
├── assets/           # Images, illustrations, icons, posters, and video recordings
│   ├── flebo/        # Flebo case study graphics
│   ├── kargo/        # Kargo360 case study graphics
│   ├── menteiz/      # Menteiz Aviation case study graphics
│   └── projects/     # MP4 screen recordings and video posters
└── README.md
```

## Running Locally

Because the project is built with standard web technologies (HTML5, CSS3, ES6 JavaScript), you can preview it immediately without any build step:

### Option 1: Local Web Server
If you have Python or Node installed:
```bash
# Using Python
python -m http.server 8000

# Using npx
npx serve
```
Then navigate to `http://localhost:8000` (or the port indicated).

### Option 2: Direct file preview
Open `index.html` directly in your favorite modern browser (Chrome, Edge, Safari, Firefox).
