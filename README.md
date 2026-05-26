# 🎵 Audra — *music you can feel*

![WCAG](https://img.shields.io/badge/WCAG-2.1_AA-1D9E75?style=flat-square) ![HTML](https://img.shields.io/badge/Built_with-HTML_CSS_JS-D4537E?style=flat-square)

---

Most music apps are built for people who can hear everything. However, hearing aids filter out specific sound frequency ranges and nobody had designed around that gap. Not streaming platforms. Not accessibility tools. Not even AI-powered solutions that claimed to help. Music taught me something: communication doesn't require a single channel. A melody can be felt, not just heard. Rhythm can be seen, not just counted. Emotion can be read in a color, not just a chord. The music is still playing, but ***something essential is missing.***

Audra was built to fill that gap, by creating a **parallel visual channel** that carries everything the sound carries:

- **Rhythm**
- **Emotion**
- **Structure**

> It started with one person who loves music. It was built for everyone who does.

---

## ✨ Features

| Layer | What it does | Who it's for |
|---|---|---|
| 🌊 **Frequency Landscape** | Real-time waveform that breathes with the music | Everyone — makes sound visible |
| 🎨 **Emotion map** | Translates mood into color and shape | Users who want to *feel* a song before hearing it |
| 💬 **Animated lyrics** | Words move with the weight of how they're sung | Hearing-impaired listeners following along |
| 🔲 **Rhythm grid** | Bass, mid, high, treble mapped to a visual pulse | Users who experience music through rhythm |
| 🎛 **Hearing profile** | Frequency sliders tuned to your hearing aid | Personalised to each listener's needs |
| ⚡ **Screen flash alerts** | Subtle full-screen pulse on beat drops | Users who feel music physically |

---

### How to use it

1. **Load a song** — click *"Load a song"* and choose any MP3 from your device or connect your Spotify account
2. **Press play** — the waveform and rhythm grid activate immediately
3. **Switch tabs** — explore the Emotion map and tune your Hearing profile
4. **Toggle layers** — turn individual visual layers on or off in the Profile tab
5. **Save your profile** — frequency settings are remembered automatically between sessions

---

## ♿ Accessibility

Audra is built to the **WCAG 2.1 AA standard** throughout:

- [x] All interactive elements are **keyboard accessible**
- [x] Color contrast meets **AA requirements** in both dark and light mode
- [x] **Font scaling** supported via Large Text toggle in Profile
- [x] **Reduce Motion** toggle for users sensitive to animation
- [x] **Screen flash** toggle — can be disabled for photosensitive users
- [x] **No data collected** — hearing profiles stored locally on your device only
- [x] Designed for compatibility with **VoiceOver** and **TalkBack** screen readers

---

## 🛠 Tech stack

```
HTML / CSS / JavaScript       — core structure and styling
Web Audio API                 — real-time audio capture and frequency analysis
Canvas API                    — waveform and emotion map rendering
FFT (Fast Fourier Transform)  — frequency band decomposition
Beat detection                — rhythm grid synchronization
localStorage                  — hearing profile persistence across sessions
DM Sans + DM Mono             — accessible, legible typography
```

## 🙋 Built by

**Rithika Machani** 
Freshman [at] UIUC, majoring in Information Sciences and Data Science

This project grew from my research into the **frequency gaps between hearing aids and standard music apps**, and a personal drive to build technology that meets people where they are, dedeicated to my grandfather who has hearing aids. 

---

## 📄 License

**MIT** — open source and free to use.

---

*Designed for hearing-impaired listeners. Built for everyone.*
