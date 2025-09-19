# Astro.js IT Conference LP Blueprint

## 1. Project Overview

**Purpose:** An entertainment-focused, single-page landing page for an IT conference, "IT CONFERENCE 2024".

**Target Audience:** Tech-savvy individuals in their 30s with a high level of interest in the industry.

**Core Concept:** A stylish and modern one-page site built with Astro.js, designed to be fast, engaging, and easy to maintain.

## 2. Core Technologies & Design Principles

### General
*   **Technology:** Astro.js with Tailwind CSS for styling.
*   **Language:** Japanese
*   **Structure:** Single-Page Application (SPA) with section-based navigation.
*   **Content Management:** Components are self-contained, making content updates modular and straightforward.

### Design
*   **Theme:** Stylish, Modern, and Energetic.
*   **Color Palette:** Dark mode theme with a base of gray-900/950, accented with vibrant colors like teal, green, purple, and orange for interactive elements and highlights.
*   **Background:** Deep dark gray (`bg-gray-900`) for the main body, with a slightly darker shade (`bg-gray-950`) for the full-screen menu to create depth.
*   **Typography:** A modern, readable sans-serif font is used throughout. Font weights and sizes are varied to create a clear visual hierarchy (e.g., large hero text, bold section titles).
*   **Layout:** A single-page layout with distinct sections. Responsive design ensures optimal viewing on both mobile and desktop devices.
*   **Interactivity:** Smooth scrolling for navigation links, interactive buttons, and a full-screen mobile menu with enhanced UX.

## 3. Implemented Components & Features

This section details all the components and features implemented in the application.

### 3.1. Header (`Header.astro`)
*   **Functionality:** A fixed navigation bar that remains at the top of the screen.
*   **Desktop View:** Displays the conference title and navigation links to all major sections.
*   **Mobile View:** Features a hamburger menu icon that opens a full-screen navigation overlay.
*   **Full-Screen Menu:**
    *   Dark, immersive background (`bg-gray-950`).
    *   Includes a prominent "close" button.
    *   Menu items are large, centered, and have hover effects for better usability.
    *   Selecting a link smoothly scrolls to the section and automatically closes the menu.
    *   Disables body scroll when active.
*   **Branding:** The "IT CONFERENCE 2024" title acts as a link to the homepage (`/`).

### 3.2. Hero Section (`Hero.astro`)
*   **Content:** A large, impactful headline with the conference title and date. Features a call-to-action button for registration.
*   **Visuals:** A dynamic background with animated gradient shapes to create a modern, tech-focused feel.

### 3.3. About Section (`About.astro`)
*   **Content:** Provides a brief, engaging introduction to the conference's purpose and what attendees can expect.

### 3.4. Features Section (`Features.astro`)
*   **Content:** Highlights three key aspects of the conference using a card-based layout. Each card has an icon, a title, and a description.
*   **Visuals:** Utilizes icons and a clean layout to present information clearly.

### 3.5. Highlights Section (`Highlights.astro`)
*   **Content:** Showcases key attractions of the event, such as "Latest Technology," "Networking," and "Special Contents."
*   **Layout:** Uses a visually distinct card layout with background images and gradient overlays to draw attention.

### 3.6. Speakers Section (`Speakers.astro`)
*   **Content:** Introduces the conference speakers. Each speaker has a photo, name, title, and a short bio.
*   **Layout:** A grid-based layout that is responsive. Photos are styled in a circular frame.

### 3.7. Schedule Section (`Schedule.astro`)
*   **Content:** A detailed timeline of the day's events, including session times, titles, and descriptions.
*   **Layout:** A vertical timeline format that is easy to follow. Different event types are visually distinguished.

### 3.8. Floor Map Section (`FloorMap.astro`)
*   **Content:** An SVG-based map of the conference venue, showing the locations of the main stage, booths, and entrance.
*   **Visuals:** A simple, clear vector map with labels. Includes a disclaimer that the layout is subject to change.

### 3.9. FAQ Section (`FAQ.astro`)
*   **Content:** An accordion-style list of frequently asked questions and their answers.
*   **Interactivity:** Users can click on a question to expand and see the answer. Initially, all answers are hidden.

### 3.10. Contact Form (`Contact.astro`)
*   **Functionality:** A form for users to send inquiries.
*   **Fields:** Includes fields for name, email address, and message.
*   **Layout:** A clean and simple form layout with a clear "Submit" button.

### 3.11. Sponsors Section (`Sponsors.astro`)
*   **Content:** Displays the logos and names of 6 fictional sponsors.
*   **Visuals:** Features colorful, custom-designed SVG logos for each sponsor. The sponsor name is displayed below each logo.

### 3.12. Follow CTA (`FollowCTA.astro`)
*   **Content:** A call-to-action section encouraging users to follow the event on social media (X/Twitter).
*   **Visuals:** Includes the X logo and a prominent "Follow Us" button.

### 3.13. Footer (`Footer.astro`)
*   **Content:** Contains information about the fictional organizing company ("MiraiTech Innovations"), social media links, and a copyright notice.
*   **Layout:** A standard footer layout with centered text.
