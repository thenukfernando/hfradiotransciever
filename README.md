# Power Amplifier & Filter 🔊

The final transmit stage of an 8–16 MHz software-defined radio: a Class-D power amplifier and 5-pole LC output filter on a custom PCB.
- **Designed** in Altium Designer
- **Simulated** in LTspice
- **Validated** with Python

Met all subsystem requirements and was selected for integration into the full SDR, which successfully transmitted signals picked up by receiving radios.

📄 **[Design Review](https://docs.google.com/presentation/d/e/2PACX-1vQim7TKjBv9BcK0RSjp95EhZMRhNs9_ZCG4Xja4aoJUcgHfCgZQ8gfkyMkH6VoPhw/pub?start=false&loop=false&delayms=60000&slide=id.p1)** — architecture, design evolution, bring-up debugging, and test data.

---

## Results

| Requirement | Measured | Status |
|---|---|---|
| Output power 1–10 W into 50 Ω | 1.22 W @ 14 MHz | Pass |
| THD < 10% | 0.73% @ 14 MHz | Pass |
| Transmit enable off during receive | Active-low verified | Pass |
| Efficiency | 37% | Typical for power amplifiers |

---

## Team

**Thenuk Fernando · Luca Mammone · Eshaan Marocha**

