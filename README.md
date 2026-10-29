# Pawan & Manisha · Shubha Vivaha

Animated wedding invitation website for **Dr. Pawan Kumar B** and **Dr. Manisha M**.

- Madarangi Shastra: Thursday, 12 November 2026, 11:30 AM
- **Muhurtha**: Friday, 13 November 2026, 10:28 AM (Dhanur Lagna) · Sri Dharmasthala Manjunatha Swamy Kala Bhavana, Belthangady

## What's inside
- Temple-door opening with a petal shower and our song, Naguva Nayana (falls back to a soft Mohanam-raga melody generated in the browser)
- Arch portrait, letter-by-letter names, live countdown to the Muhurtha
- "Our story" photo chapters joined by a red thread that draws as you scroll
- Wedding details with a Google Calendar button
- Venue card with QR code and Google Maps directions
- Blessings form that sends a message via WhatsApp, plus a share button
- English / ಕನ್ನಡ switch (top-right) covering all page text
- Hero photo slideshow (edit the `#heroSlides` images) and a swipeable Pre-wedding strip with a full-screen viewer (edit the `#strip` images)

It's a single static page (`index.html` + `assets/img/`), with no build step.

## Run locally
```
python3 -m http.server 8000
# open http://localhost:8000
```

## Live site
- Pawan's link: **https://jaanpaddhsaga.pawansdroid.in**
- Manisha's link: **https://jaanpaddhsaga.pawansdroid.in/manisha/** (WhatsApp preview reads Manisha & Pawan; it forwards to `/#manisha`) (her name first, her family's Madarangi at 7:00 PM from Sri Ganesha Nilaya, blessings to her WhatsApp)
- Kannada links: **https://jaanpaddhsaga.pawansdroid.in/kannada/** and **https://jaanpaddhsaga.pawansdroid.in/manisha/kannada/** (Kannada WhatsApp preview; they forward to `/#kannada` and `/#manisha-kannada` and open in Kannada without changing the saved language choice)

**https://jaanpaddhsaga.pawansdroid.in** — Netlify is linked to this repository and redeploys on every push to `claude/animated-marriage-website-gvogtb`.

The WhatsApp/social preview (`og:url`, `og:image`) uses that address. GitHub Pages is also enabled at https://pawankumar1901-netizen.github.io/JaanPaddhSaga/ but its builds were stuck in GitHub's queue.
