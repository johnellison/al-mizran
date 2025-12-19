# Al-Mizan (The Balance): Spiritual Soul Tracker

**Al-Mizan** is a mobile-first, single-file web application designed to help users track their thoughts, activities, and emotional states. Unlike standard habit trackers, Al-Mizan aligns its logic with the **five daily prayer times** (Temporal Gates) and offers behavioral prescriptions rooted in **Sufi psychology** and **Essene nature practices**.

It requires no internet connection, no server, and stores all data locally on your device for complete privacy.

## 🌟 Features

*   **Temporal Gates:** Instead of arbitrary timestamps, entries are categorized by the 5 spiritual times of day: *Fajr* (Awakening), *Dhuhr* (Height), *Asr* (Decline), *Maghrib* (Sunset), and *Isha* (Stillness).
*   **The Wisdom Engine:** An algorithmic recommender system that analyzes your mood (Contraction vs. Expansion) and suggests specific spiritual antidotes (Breathwork, Dhikr, Service, or Silence).
*   **Muhasabah (Self-Accounting):** A history log allows you to review your behavioral patterns and emotional states over time.
*   **Privacy First:** Built with "Local Storage" technology. Your thoughts never leave your phone.
*   **Zero Dependencies:** The entire app is contained in a single HTML file. No installation or complex setup required.

## 🕌 The Philosophy

This application is built on the intersection of ancient traditions:

1.  **The Circadian Rhythm (Essene/Islamic):** Recognizing that the energy of the morning differs from the energy of the night, and our behaviors should shift accordingly.
2.  **States of the Heart (Sufi):** Tracking the heart's fluctuation between *Qabd* (Contraction/Anxiety) and *Bast* (Expansion/Joy), providing specific remedies for each state to return to *Mizan* (Balance).

## 🚀 Quick Start

You do not need to install Node.js, Python, or a server to run this.

1.  **Download** the `tracker.html` file from this repository.
2.  **Open** the file in any web browser (Chrome, Safari, Firefox).
3.  **Begin** tracking.

## 📱 Mobile Installation (Add to Home Screen)

For the best experience, save the app to your phone so it looks like a native application.

**On iPhone (Safari):**
1. Open `tracker.html` in Safari.
2. Tap the **Share** button (box with an arrow pointing up).
3. Scroll down and tap **"Add to Home Screen"**.

**On Android (Chrome):**
1. Open `tracker.html` in Chrome.
2. Tap the three dots (menu) in the top right.
3. Tap **"Add to Home screen"**.

## 🛠️ Customization

Because the app is a single file, you can easily modify the "Wisdom Engine" to include your own favorite quotes, scriptures, or affirmations.

1. Open `tracker.html` in a text editor.
2. Search for the section labeled `const wisdomDatabase`.
3. Edit the text inside the quotes to customize the recommendations for "low", "balanced", and "high" moods.

```javascript
// Example Customization
low: [
    "Your custom advice here...",
    "Recite Psalm 23...",
    "Do 5 minutes of box breathing..."
],
