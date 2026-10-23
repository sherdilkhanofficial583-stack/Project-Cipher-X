# Cipher-X Omega - NASA Space Apps 2026 Challenge: SPHEREx

**Tagline: فائل نہیں، یادداشت | Memory over Files**

**The Problem:** SPHEREx gives 102 spectral bands for 2.4B sky pixels. Traditional image subtraction is noisy and slow.

**Our 1000-Year Ahead Solution:**
1.  **Chemical Fingerprint:** We don't look at brightness. We convert each pixel's 102 bands into a chemical vector (Water, Carbon, Iron).
2.  **Living Memory (Vector DB):** Each sky location has a memory stored in Qdrant. Change detection is O(1) - memory mismatch, not image comparison.
3.  **Garden UX:** Changes bloom as flowers. Inclusive - blind users can hear changes (sonification). No graphs.
4.  **Future Prediction:** AI predicts next change from chemical trend (e.g., Water up 42% = new planet forming in 6 months).

**Tech Stack:** Next.js + WebGL + FastAPI + Qdrant + NASA IRSA SPHEREx API
**Live Demo:** [Your GitHub Pages Link]
**Demo Note:** For speed, demo uses mock data simulating IRSA API. Real backend ready.

Team: Muridke, Pakistan
