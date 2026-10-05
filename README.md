# Pawan & Manisha · Shubha Vivaha

Animated wedding invitation website for **Dr. Pawan Kumar B** and **Dr. Manisha M**.

- Madarangi Shastra: Thursday, 12 November 2026, 11:30 AM
- **Muhurtha**: Friday, 13 November 2026, 10:28 AM (Dhanur Lagna) · Sri Dharmasthala Manjunatha Swamy Kala Bhavana, Belthangady

## What's inside
- Temple-door opening with a petal shower and our song, Naguva Nayana (falls back to a soft Mohanam-raga melody generated in the browser)
- Arch portrait, letter-by-letter names, live countdown to the Muhurtha
- "Our story" photo chapters joined by a red thread that draws as you scroll
- Wedding details with Google Calendar and .ics buttons
- Venue card with QR code and Google Maps directions
- Blessings form that sends a message via WhatsApp, plus a share button
- English / ಕನ್ನಡ switch (top-right) covering all page text

It's a single static page (`index.html` + `assets/img/`), with no build step.

## Run locally
```
python3 -m http.server 8000
# open http://localhost:8000
```

## Publish with GitHub Pages
1. Settings → General → Danger Zone → **Change visibility → Public**. Free GitHub accounts can only host Pages from public repos.
2. Settings → **Pages** → Source: **Deploy from a branch** → Branch: `claude/animated-marriage-website-gvogtb`, folder `/ (root)` → Save.
3. After about a minute the site is live at **https://pawankumar1901-netizen.github.io/Marriage-/**

The WhatsApp/social preview image (`assets/img/og.jpg`) is linked using that address.
