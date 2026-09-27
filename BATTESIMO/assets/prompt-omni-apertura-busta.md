# Prompt Gemini Omni per Animazione Apertura Busta Battesimo

File immagine iniziale di riferimento (Frame 0):
`BATTESIMO/assets/busta-sigillo-4k.jpg`

---

### Impostazioni consigliate su Google AI Studio / Gemini Omni:
* **Modello:** Gemini 1.5 Flash / Omni Video Preview
* **Aspect Ratio:** 9:16 (Verticale / Portrait)
* **Risoluzione:** 4K UHD (2160 × 3840) oppure 1080p (1080 × 1920)
* **Durata:** 3 - 4 secondi
* **Thinking Level:** High
* **Immagine di partenza:** Caricare `busta-sigillo-4k.jpg` come First Frame / Reference Image

---

### Prompt Ottimizzato (con vincoli direzionali anti-burst e anti-fumo):

```text
Cinematic 4K high-angle static shot starting from this exact textured cream paper envelope with the golden cross wax seal.

Action:
1. The top triangular flap smoothly and realistically folds open upwards, lifting the golden wax seal with it.
2. A soft, diffuse white light and milky-white exposure haze begins strictly from the BOTTOM of the frame (underneath the lower edge of the envelope) and rises upward.
3. The soft white glow sweeps smoothly from bottom to top, progressively washing over the front of the envelope like a gentle vertical light sweep.
4. The entire frame smoothly becomes 100% solid, pure, uniform cream-white with zero visible borders or shadows.

Constraints & Negative Prompts:
- NO central radial burst, NO lens flare in the middle of the screen, NO sun explosions.
- NO physical smoke, NO vapor, NO steam, NO liquid, NO milk, NO clouds.
- The light transition is a directional soft sweep moving from bottom to top until completely pure white.
- Photorealistic paper texture and smooth wax seal physics.
```

---

### Note di utilizzo e integrazione:
* Il video attivo sul sito è salvato in `BATTESIMO/assets/apertura-busta-omni-4k.mp4`.
* Il trigger JavaScript in `BATTESIMO/index.html` fa sparire la busta a 1800ms non appena il bianco invade lo schermo a tutto campo, rivelando il sito senza scatti.
