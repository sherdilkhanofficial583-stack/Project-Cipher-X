# Cipher-X Omega | NASA Space Apps Challenge 2026

## 🚀 Overview
**Cipher-X Omega** is a high-performance web-based visualization and anomaly detection dashboard built for the **NASA Space Apps Challenge 2026**, specifically targeting the **Planet X and SPHEREx** challenge[span_7](start_span)[span_7](end_span)[span_8](start_span)[span_8](end_span). 

The system leverages a simulated O(1) **Vector Memory** architecture to process and track spatial and chemical shifts across SPHEREx's 6-month baseline sky mapping[span_9](start_span)[span_9](end_span)[span_10](start_span)[span_10](end_span).

---

## 💡 The Problem
Since 2025, NASA's SPHEREx mission has been mapping the entire sky every six months across 102 bands of near-infrared light, capturing over a billion objects (comets, asteroids, stars, and transient phenomena)[span_11](start_span)[span_11](end_span)[span_12](start_span)[span_12](end_span)[span_13](start_span)[span_13](end_span). Traditional image subtraction methods are computationally heavy, noisy, and slow for analyzing this massive volume of spatial data.

---

## ⚡ Our Solution & Key Features
1. **Vector Memory over Files ($O(1)$ Processing):** Instead of comparing heavy image pixels, our system indexes spectral signatures into a high-speed vector space, allowing instant anomaly and shift detection[span_14](start_span)[span_14](end_span).
2. **Temporal Shift Tracking:** Simulates SPHEREx's 6-month baseline mapping cycles to instantly reveal how objects (asteroids, comets, or transient bodies) have shifted their positions over 6, 12, 18, or 24 months[span_15](start_span)[span_15](end_span).
3. **Chemical Fingerprinting:** Inspects 102 infrared bands, identifying vital chemical components such as Water Ice (Band 23), Carbon signatures (Band 67), and Iron/Metals (Band 91)[span_16](start_span)[span_16](end_span)[span_17](start_span)[span_17](end_span).
4. **Garden UX & Audio Sonification:** Features a responsive, mobile-optimized WebGL canvas with Web Audio API integration, providing tactile audio feedback and an accessible experience for all users.
5. **Future Prediction (6M):** Extrapolates historical movement trends to forecast upcoming spatial and chemical changes in the cosmic neighborhood[span_18](start_span)[span_18](end_span).

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, JavaScript (ES6+), WebGL (HTML5 Canvas API)
* **Audio Engine:** Web Audio API (Real-time synthesized frequency chimes)
* **Architecture Concept:** Python, FastAPI, Qdrant Vector Database, NASA IRSA SPHEREx API[span_19](start_span)[span_19](end_span)

---

## 🌐 Live Demo & Deployment
* **GitHub Repository:** [Project-Cipher-X](https://github.com/sherdilkhanofficial583-stack/Project-Cipher-X)
* **Hosting:** GitHub Pages

*Note: For optimal mobile and desktop browser performance, this frontend prototype uses high-fidelity mock data simulating the NASA IRSA API backend.*

---
**Team:** Muridke, Pakistan  
**Event:** NASA Space Apps Challenge 2026[span_20](start_span)[span_20](end_span)[span_21](start_span)[span_21](end_span)
