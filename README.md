# Omnifood — Responsive Food Subscription Website
<img width="1897" height="1004" alt="Screenshot 2026-07-11 111303" src="https://github.com/user-attachments/assets/dfe89780-ae3e-4ae0-b6a8-790ff240167a" />
[Click Here To See The Demo](http://nimarhm.github.io/Omnifood)
A fully responsive landing page for Omnifood, food subscription service that delivers healthy, personalized meals every day.

This project is based on the course **Build Responsive Real-World Websites with HTML and CSS**.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Built With](#built-with)
- [Sections](#sections)
- [Responsive Design](#responsive-design)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [JavaScript Functionality](#javascript-functionality)
- [Credits](#credits)

## Overview

Omnifood is a modern marketing website for a fictional meal subscription platform. The website presents personalized meal planning, food delivery, pricing plans, customer testimonials, and a sign-up form.

The project focuses on building a clean, accessible, and responsive user interface using vanilla HTML, CSS, and JavaScript.

## Features

- Fully responsive layout for desktop, tablet, and mobile devices
- Modern hero section with calls to action
- Sticky navigation bar
- Mobile navigation menu
- Smooth scrolling between page sections
- Responsive CSS Grid layouts
- Meal cards with nutrition details and dietary tags
- Testimonials and food gallery
- Pricing plans
- Contact and sign-up form
- Dynamic footer year
- Flexbox gap fallback for older browser support

## Built With

- HTML5
- CSS3
- JavaScript
- CSS Grid
- Flexbox
- Google Fonts — Rubik
- Ionicons
- Smooth Scroll Polyfill

## Sections

The page includes the following sections:

- **Header:** Navigation links and mobile menu button
- **Hero:** Main introduction and call-to-action buttons
- **Featured In:** Brand logo showcase
- **How It Works:** Three-step explanation of the Omnifood process
- **Meals:** Sample meal cards and supported diet types
- **Testimonials:** Customer feedback and image gallery
- **Pricing:** Starter and Complete subscription plans
- **Features:** Benefits of using Omnifood
- **Call to Action:** Sign-up form for a free first meal
- **Footer:** Contact details, social links, navigation, and resources

## Responsive Design

The website is optimized for a wide range of screen sizes using media queries.

- **Large screens:** Multi-column layouts for hero, meals, pricing, and footer content
- **Tablet screens:** Adjusted typography, spacing, gallery layout, and mobile navigation
- **Mobile screens:** Single-column sections, stacked call-to-action layout, resized buttons, and compact content spacing

## Getting Started

To run the project locally:

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/omnifood.git
   ```

2. Navigate to the project directory:

   ```bash
   cd omnifood
   ```

3. Open `index.html` in your browser.

You can also use the **Live Server** extension in Visual Studio Code for a better development experience.

## Project Structure

```text
omnifood/
│
├── index.html
├── css/
│   ├── general.css
│   ├── style.css
│   └── queries.css
│
├── js/
│   └── script.js
│
├── img/
│   ├── app/
│   ├── customers/
│   ├── gallery/
│   ├── logos/
│   ├── meals/
│   ├── favicon.png
│   ├── hero.webp
│   └── omnifood-logo.png
│
├── manifest.webmanifest
└── README.md
```

## JavaScript Functionality

The JavaScript file provides several interactive features:

- Updates the copyright year automatically
- Opens and closes the mobile navigation menu
- Enables smooth scrolling for internal navigation links
- Closes the mobile menu after selecting a navigation link
- Adds a sticky header after scrolling past the hero section
- Detects Flexbox `gap` support and applies a fallback class when necessary

## Credits

This project is based on the course:

**Build Responsive Real-World Websites with HTML and CSS**

