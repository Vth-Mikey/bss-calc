# 🐝 BSS Drive Cost Calculator `v1.1`

<p align="center">
  <img src="img/Hivesticker_party_robo_bear.webp" width="100">
</p>


A high-precision honey estimation tool for **Bee Swarm Simulator** players. Designed to help you plan your path to 500 White, Red, Blue, or Glitch drives.

---

## 🌐 Live Application
You can access the calculator here: 
### 👉 [bit.ly/bsscalculator](https://bit.ly/bsscalc)

---

## 📖 How to Use
1. **Select Drive Type:** Choose between **Colored** (White/Red/Blue) or **Glitch** drives from the dropdown menu.
2. **Set Your Range:** * Enter your **Current** number of drives.
   * Enter your **Target** number of drives.
3. **Check Results:** The calculator will instantly show you the **Total Honey** needed for that specific jump.
4. **Specific Lookup:** Use the "Specific Drive" box to see exactly how much a single future drive will cost (e.g., "What does my 400th drive cost?").
5. **Auto-Save:** Your progress is saved automatically to your browser—feel free to refresh!

---

## 🚀 Features
* **Dual Mode:** Supports both Colored Drives (250k base) and Glitch Drives (1M base).
* **Endgame Scaling Logic:** Accurately calculates the "Price Wall" that hits after drive 250.
* **Responsive Design:** Optimized for both **Desktop** and **Mobile** (Infinix/Android/iOS).
* **Dark/Light Mode:** Toggle between themes for late-night grinding.
* **Open Source:** Lightweight Vanilla JS with zero dependencies.

## 📊 The "Scaling Wall" Logic
In Bee Swarm Simulator, a scaling factor is applied once a player exceeds 250 drives of a single type.
* **Drives 1-250:** Standard $P(n) = \text{Base} \times n^2$
* **Drives 251-500:** Applies a dynamic multiplier (approx. $+0.413\%$ per drive) to account for endgame inflation. 
* *Note: This logic is a high-accuracy estimation based on community data.*

## 🛠️ Built With
* HTML5 / CSS3 (Flexbox & Media Queries)
* JavaScript (Vanilla)
* Hosted on GitHub Pages

---

## 📱 Mobile Tip
For the best experience on Android/iOS, open the link in your browser and select **"Add to Home Screen"**. This will install the calculator as a standalone app on your phone!

## ✉️ Contact & Credits
**Developer:** ✯𝑵𝖎𝖌𝖍𝒕  
**Socials:** [guns.lol/nightnosleep](https://guns.lol/nightnosleep)

---
*Disclaimer: This is a fan-made tool. Bee Swarm Simulator is owned by Onett.*
