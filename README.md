# RescueLink — Website

A responsive landing website introducing **RescueLink**, a mobile application designed to provide emergency assistance information, safety resources, and essential support services.

The website presents the application's features, interface previews, and project information through a clean, accessible, and bilingual user experience.

## Overview

RescueLink Website serves as the official introductory platform for the RescueLink mobile application. It provides visitors with an overview of the application's purpose, key features, available services, and interface.

The website supports both Bengali and English, allowing users to explore the platform in their preferred language.

## Features

- **Responsive Design:** Optimized for desktop, tablet, and mobile devices.
- **Bilingual Interface:** Supports Bengali and English with persistent language preferences.
- **Application Preview:** Showcases screenshots of the RescueLink mobile application.
- **Interactive Navigation:** Includes mobile navigation and active section highlighting.
- **Scroll Animations:** Provides smooth reveal effects while navigating the page.
- **Contact Section:** Allows visitors to compose inquiries through their default email application.
- **Lightweight Implementation:** Built without external JavaScript frameworks or build tools.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and semantic content |
| CSS3 | Styling, responsive layouts, and animations |
| Vanilla JavaScript | Interactive functionality and language management |
| Inline SVG | Interface icons and vector graphics |
| Google Fonts | Hind Siliguri typography |

## Project Structure

```text
RescueLink/
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── images/
│   │   ├── logo.png
│   │   ├── logo-full.png
│   │   ├── favicon.png
│   │   ├── hero-app.png
│   │   ├── app-home.jpeg
│   │   ├── app-sos.jpeg
│   │   ├── app-map.jpeg
│   │   ├── app-shelters.jpeg
│   │   ├── app-services.jpeg
│   │   └── app-profile.jpeg
│   └── icons/
└── README.md
```

## Getting Started

### Prerequisites

- A modern web browser.
- An internet connection for loading Google Fonts.

### Installation and Execution

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd RescueLink
   ```

3. Open `index.html` in your preferred web browser.

No dependency installation, build process, or development server is required.

## Application Screenshots

The website includes visual previews of the RescueLink mobile application.

| Asset | Description |
|---|---|
| `app-home.jpeg` | Application home screen |
| `app-sos.jpeg` | Emergency SOS interface |
| `app-map.jpeg` | Map and location interface |
| `app-shelters.jpeg` | Nearby shelter information |
| `app-services.jpeg` | Emergency services information |
| `app-profile.jpeg` | User profile and settings |

### Image Guidelines

- Maintain an approximate aspect ratio of 9:19.2 (e.g., 1242 × 2656 pixels).
- Do not include additional phone frames in screenshots; the website provides its own presentation frame.
- `hero-app.png` generally uses a copy of the home screen image.
- Update the corresponding `data-alt` descriptions in `index.html` whenever screenshots are replaced.
- Remove sample-preview notices from the application preview section when actual screenshots are used.

## Language Configuration

The website supports Bengali and English.

- Bengali is the default language.
- Users can switch languages through the navigation bar.
- Language preferences are stored in the browser using local storage.
- Bengali content is maintained in `index.html`.
- English translations are maintained in the `I18N` mapping at the beginning of `script.js`.

**Translation Maintenance:** Whenever Bengali content is modified in `index.html`, its corresponding entry in the `I18N` mapping must be updated to ensure accurate English translations. All newly added text, form validation messages, and status messages should also include their English translations.

## Branding and Assets

The following image assets are used throughout the website:

| File | Usage |
|---|---|
| `logo.png` | Navigation bar and footer |
| `logo-full.png` | Social sharing previews |
| `favicon.png` | Browser tab icon |
| `hero-app.png` | Hero section application preview |

If an SVG version of the logo is available, it may be placed in `assets/images/logo.svg`, with the corresponding image references updated in `index.html`.

## Contact Configuration

The website currently uses the placeholder email address:

`hello@rescuelink.example`

Before deployment, replace this address with the official project email in all relevant locations within `index.html`, including:

- Contact information section
- Contact form's `data-email` attribute
- Footer

The contact form generates an email through the visitor's default email application. It does not submit messages to a backend server or store user information.

## Limitations and Disclaimer

- The website is an informational platform introducing the RescueLink mobile application.
- Feature descriptions represent the application's planned or implemented capabilities and should be kept consistent with the actual development status.
- The website itself does not transmit emergency alerts or request access to visitors' locations.
- It does not provide direct emergency communication with authorities.
- Application screenshots and feature descriptions should accurately represent the current state of the mobile application.

## Course and Team Attribution

**Academic Information**

| Field | Details |
|---|---|
| Course | CSE 416 — Software Project Design and Development |
| Institution | University of Information Technology and Sciences (UITS) |
| Department | Computer Science and Engineering |
| Supervisor | Dr. Mahfida Amjad Dipa |

**Project Team**

| Role | Name |
|---|---|
| Project Lead & Full-Stack Developer | Rowshon Jahan Poddo |
| Collaborator | Abdur Rahman Jayed |

---

*RescueLink — Connecting people with emergency assistance and essential safety information.*
