# ☀️ Daylight – Sunrise and Sunset for Every Day

A beautiful, clean, and fast web application to check solar phases—sunrise, sunset, day length, and solar noon—for any date and any location on Earth.

🌐 **[View Live Demo](#)** [https://zhivkogenadiev.github.io/daylight/](https://zhivkogenadiev.github.io/daylight/)

---

## ✨ Key Features

- **🚀 Fully Client-Side:** Runs entirely in the browser with no server, database, or external API keys required.
- **🔭 Astronomical Precision:** Uses advanced NOAA solar equations to calculate:
  - Exact sunrise and sunset times
  - Solar noon
  - First and last light (civil twilight at 6° below the horizon)
  - Day length and comparison with the previous day
  - Automatic detection of polar days and nights
- **🌅 Interactive Sky Simulator:** Built-in time scrubber (slider) to track the sun's position and real-time sky color transitions throughout the day.
- **📍 Flexible Location Selection:** 
  - Pre-set major world cities
  - Automatic browser geolocation (`Geolocation API`)
  - Manual entry of geographic coordinates (latitude and longitude)
- **📅 14-Day Forecast Panel:** A list showing solar data for the upcoming two weeks with visual day-length progress bars.
- **🎨 Modern Design & Dark Mode:** Clean typography (*Fraunces* and *Instrument Sans*), seamlessly adapting to the system's dark/light color scheme.

---

## 🛠️ Tech Stack

- **HTML5 & CSS3** (Custom Properties, Flexbox, Grid, Media Queries)
- **Vanilla JavaScript (ES6+)**
- **SVG** (For dynamic rendering of the sun's arc and sky background)
- **NOAA Solar Equations** (Astronomical algorithms for solar positioning)

---

## 🚀 How to Run Locally

The project is lightweight and contained within a single main file (`index.html`). No Node.js installation or package manager is required.

1. Clone the repository or download the files:
   ```bash
