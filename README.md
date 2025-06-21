README.md# Itinerary Builder PWA

A mobile-first Progressive Web App (PWA) for creating daily itineraries for Christian pilgrimages and tour groups.

Designed to be used directly in the browser — with no account or installation required — this tool makes it easy to:

- Set a tour name and travel dates
- Automatically generate day-by-day sections
- Select activities and sites from a built-in, categorized database
- Manually enter or edit activities for each day
- Export and share the full itinerary in a clean, printable format

## ✨ Features

- Offline-capable (via Service Worker)
- PWA installable on iOS and Android
- Grouped activity selection with live search
- Smart formatting for itinerary text
- Share button using the native Web Share API

## 🔗 Live Demo

Try it here:  
[https://titoguide.github.io/Itinerary-pwa/](https://titoguide.github.io/Itinerary-pwa/)

## 📁 File Structure

Itinerary-pwa/
├── index.html # Main UI and logic
├── sites.json # Categorized activities database
├── service-worker.js # Enables offline support
└── manifest.json # Defines PWA metadata



## 🛠️ To Update Site Database

Edit the `sites.json` file to add or modify categories and activities.  
Changes will reflect automatically on the next load.

## 📲 Installation

On mobile:
- Open the live demo link
- Tap "Add to Home Screen" from the browser share menu

## 🚀 Deployment

This project is hosted via GitHub Pages.  
Any changes pushed to the `main` branch are automatically published to the live site.

---

Made with ❤️ by [TitoGuide](https://github.com/titoguide)
