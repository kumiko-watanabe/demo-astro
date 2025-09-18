# Astro.js IT Conference LP Blueprint

## 1. Project Overview

**Purpose:** An entertainment-focused, single-page landing page for an IT conference.

**Target Audience:** Tech-savvy individuals in their 30s with a high level of interest in the industry.

**Core Concept:** A stylish and modern one-page site built with Astro.js, designed to be fast, engaging, and easy to maintain.

## 2. Core Features & Design

### General
*   **Technology:** Astro.js
*   **Language:** Japanese
*   **Structure:** Single-Page Application (SPA)
*   **Content Management:** Content (text, images) will be centralized in the main page file for easy updates.

### Design
*   **Theme:** Stylish & Modern
*   **Background Color:** `#111111`
*   **Typography:** A modern, readable sans-serif font will be used.
*   **Layout:** Inspired by the provided reference site (`https://game-future-summit.jp/`), focusing on a clean, visually balanced presentation.

## 3. Implemented Features
*   Hero Section
*   About Section
*   Conference Features (3 Columns)
*   Past Event Highlights (with YouTube embed)
*   Speaker Profiles
*   Event Schedule (2 Days)
*   Venue Floor Map
*   FAQ Section
*   Contact & Social Media Links

## 4. Current Task: Add New Content Sections

**Plan:**

1.  **Create `src/components/Features.astro`:** This component will display the key features of the conference in a 3-column layout.
2.  **Create `src/components/Highlights.astro`:** This component will feature a brief text about last year's event and an embedded YouTube video.
3.  **Create `src/components/Speakers.astro`:** This component will introduce the speakers with their photos, names, and profiles.
4.  **Create `src/components/Schedule.astro`:** This will display the schedule for the two-day event.
5.  **Create `src/components/FloorMap.astro`:** This component will show the floor map of the conference venue.
6.  **Update `src/pages/index.astro`:** Import and arrange the newly created components in the main page.
