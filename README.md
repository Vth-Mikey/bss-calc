# digi-bee-drives-calc
bee swarm simulator calculator 

# 🐝 BSS Drive Cost Calculator `v1.0`

A high-precision honey estimation tool for **Bee Swarm Simulator** players. Designed to help you plan your path to 500 White, Red, Blue, or Glitch drives.



## 🚀 Features
* **Dual Mode:** Supports both Colored Drives (250k base) and Glitch Drives (1M base).
* **Endgame Scaling Logic:** Accurately calculates the "Price Wall" that hits after drive 250.
* **Single Lookup:** Instantly find the price of a specific n-th drive (e.g., "How much is my 300th drive?").
* **Mobile Optimized:** Built specifically for use on Android/iOS while you grind.
* **Auto-Save:** Remembers your current count and goals (v1.0).

## 📊 The "Scaling Wall" Logic
In Bee Swarm Simulator, Onett implemented a scaling factor once a player exceeds 250 drives of a single type.
* **Drives 1-250:** Standard $P(n) = 250,000n^2$
* **Drives 251-500:** Applies a dynamic multiplier (approx. $+0.4\%$ per drive) to account for endgame inflation. 
* *Verified: Drive 273 costs ~20.4B Honey.*

## 🛠️ Built With
* HTML5 / CSS3 (Dark Mode)
* JavaScript (Vanilla)
* Hosted on GitHub Pages

---
*Disclaimer: This is a fan-made tool and the Scaling Wall logic is improvised with the help of Ai this is not verified from Onett himself. Bee Swarm Simulator is owned by Onett.*
