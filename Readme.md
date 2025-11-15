# Netflix Clone — README

## Project Overview
This project is a **Netflix Clone landing page** built using **HTML and CSS**. It recreates the look and feel of Netflix's official homepage, including the hero section, trending section, reasons-to-join cards, FAQs, footer, and overall responsive design.
The goal of this project is to practice **responsive web design**, **CSS layout techniques**, and **UI cloning** using pure HTML and CSS.

## Features

### Modern Netflix-style User Interface
The layout matches Netflix's homepage with:
* Logo and top navigation
* Hero section with a dark overlay
* Email sign-up form
* Trending section with ranked cards
* Informational cards on why to join
* FAQ section
* Footer with essential links

### Responsive Design
The UI adjusts smoothly for:
* Desktop (large screens)
* Tablets (768px and below)
* Mobile devices (480px and below)

### Animations & Hover Effects
* Trending cards scale on hover
* Clean transitions and responsive structures

##  Project Structure
*project-folder
*index.html
*style.css
*background_image.jpg
*logo.png 
*images for trending cards

## File Descriptions

### **index.html**

Contains the full structure of the website:

* **header**— Netflix logo, language select, sign-in button
* **section class="hero"** — background banner + email form
* **section class="trending-section"** — trending movies/shows
* **div class="reasons-container"** — key features
* **section class="faq-section"** — common questions
* **section class="email-section"** — email subscription call
* **footer** — links and contact info

### **style.css**
Includes all styling:
* Global styles (fonts, background, reset)
* Header + logo styles
* Hero section overlay effects
* Trending section card layout
* Reasons cards grid layout
* FAQ design
* Footer grid
* Media queries for responsiveness

---

## How the Website Works

###  Header
Displays the Netflix logo, language selection dropdown, and a sign-in button.

### Hero Section
Uses a full-width background image with a dark overlay to improve text visibility. A centered text block introduces the service and contains an email submission form.

### Trending Section
Cards show popular shows/movies with ranking numbers. Hover effect enlarges the cards.

### Reasons to Join
Four cards explaining Netflix's benefits.

###  FAQ
Displays common user questions in simple blocks.

### Footer
Contains customer support number and categorized links.

## Responsiveness
Media queries included:
* **Max-width: 768px** → Tablet layout
  * Header becomes vertical
  * Trending cards adjust to smaller widths
  * Column layout for reasons section

* **Max-width: 480px** → Mobile layout
  * Full-width cards
  * Email input/button stack vertically
These ensure smooth display on any screen size.

## Technologies Used
* **HTML5** — semantic structure
* **CSS3** — flexbox, grid, responsive design, hover effects
No JavaScript is used in this basic version.

