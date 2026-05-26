# 🎵 Audra — *Music You Can Feel*

![WCAG](https://img.shields.io/badge/WCAG-2.1_AA-1D9E75?style=flat-square) ![HTML](https://img.shields.io/badge/Built_with-HTML_CSS_JS-D4537E?style=flat-square)

---

## Why Audra exists

Most music apps are built for **people who can hear everything.** Hearing aids filter out specific frequency ranges — the shimmer of a cymbal, the brightness of a voice, the warmth of a high melody. Those frequencies don't reach the listener. The music is still playing, but ***something essential is missing.***

Audra was built to fill that gap. Not by fixing the audio — but by creating a **parallel visual channel** that carries everything the sound carries:

- 🌊 **Rhythm**
- 🎨 **Emotion**
- 📐 **Structure**
- 💬 **The feeling of a chorus building toward something**

> It started with one person who loves music. It was built for everyone who does.

---

## ✨ Features

| Layer | What it does | Who it's for |
|---|---|---|
| 🌊 **Frequency landscape** | Real-time waveform that breathes with the music | Everyone — makes sound visible |
| 🎨 **Emotion map** | Translates mood into color and shape | Users who want to *feel* a song before hearing it |
| 💬 **Animated lyrics** | Words move with the weight of how they're sung | Hearing-impaired listeners following along |
| 🔲 **Rhythm grid** | Bass, mid, high, treble mapped to a visual pulse | Users who experience music through rhythm |
| 🎛 **Hearing profile** | Frequency sliders tuned to your hearing aid | Personalised to each listener's needs |
| ⚡ **Screen flash alerts** | Subtle full-screen pulse on beat drops | Users who feel music physically |

---

### How to use it

1. **Load a song** — click *"Load a song"* and choose any MP3 from your device
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

**Rithika Machani** — UX/UI designer and developer focused on accessible technology.

This project grew out of a *Harvard CS560 accessibility project*, research into the **frequency gaps between hearing aids and standard music apps**, and a personal drive to build technology that meets people where they are — not where it's convenient to design for.

Multiple JavaScript iterations. WCAG 2.1 standards applied throughout. Tested with a real hearing-impaired listener whose feedback shaped every design decision.

---

## 📄 License

**MIT** — open source and free to use.

---

*Designed for hearing-impaired listeners. Built for everyone.*
