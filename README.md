# Marry Holiday — Genting Tour Operations Console

A lightweight, browser-based operations management console developed for Marry Holiday to oversee Genting tour coach bookings, passenger manifests, schedule coordination, and real-time seat allocations.

---

## Overview

The Genting Tour Operations Console provides front-desk and transport dispatch teams with a unified interface to track daily bus departures, allocate passenger seating across 30-seat VIP coaches (1+2 layout), and verify boarding status without requiring complex server infrastructure.

---

## Key Features

- **Daily Operations Overview**: Real-time aggregation of booking totals, coach utilization metrics, departure timelines, and passenger tallies.
- **Interactive Coach Seating Matrix**: Visual 30-seat floor plan reflecting standard 1+2 VIP coach configurations with status-coded seat allocations (Available, Reserved, Checked-In).
- **Passenger Manifest Management**: Searchable customer rosters with booking references, contact numbers, pickup points, and trip verification tools.
- **Client-Side Architecture**: Fully functional static application with zero backend runtime dependencies, ready for offline local use or static cloud hosting.

---

## Technical Specifications

- **Frontend Core**: Semantic HTML5, Vanilla CSS3, JavaScript (ES6+)
- **Typography**: Geist & Geist Mono (Google Fonts)
- **Dependencies**: None (Zero npm runtime dependencies)
- **Design System**: High-contrast, ink-on-white operational layout tailored for high-efficiency dispatch workflows

---

## Deployment Guide

### GitHub Pages Hosting

1. Push this project repository to GitHub.
2. In your repository settings, navigate to **Settings** > **Pages**.
3. Under **Build and deployment**, select `Deploy from a branch`.
4. Choose the `main` branch and `/ (root)` folder, then click **Save**.
5. The live console will be available at:
   ```text
   https://<organization-or-username>.github.io/<repository-name>/
   ```

---

## Local Development & Usage

To launch the console locally:

1. Open the project folder in your local file explorer.
2. Double-click `index.html` (or `Marry Holiday - Genting Tour Console.html`) to open directly in any modern web browser (Chrome, Edge, Firefox, Safari).
