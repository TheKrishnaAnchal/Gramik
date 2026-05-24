# Gramik 🌾 - AI Agricultural Intelligence

Gramik is an offline-first, AI-powered agricultural intelligence application optimized for low-resource and low-connectivity environments. It integrates local data queuing, on-device machine learning inference, and asynchronous alert systems into a unified mobile interface.

---
🛠️ System Architecture & Tech Stack
Gramik utilizes an open-source stack with zero licensing costs, reducing server dependency via on-device inference:

Frontend: React Native (Expo) designed for high-fidelity, low-latency rendering.

Computer Vision: EfficientNet (CNN) deployed for localized crop disease detection and diagnostics.

Weather Forecasting: Temporal Fusion Transformer (TFT) for short-term climate and storm modeling.

Market Intelligence: LightGBM utilized for price forecasting and market trend analysis.

Database & Backend Sync: Encrypted SQLite local queues ensure zero data loss during network drops.

Geospatial Processing: PostGIS integration for mapping community disease heatmaps on a 50m grid.

🧩 The 5 Core Modules
Gramik's architecture is divided into five specific intelligence modules that communicate through a centralized Decision Engine:

1. Crop Disease Detection: Instantly identifies plant health issues through a simple photo and generates a prescriptive recovery plan.

2. Weather & Crop Advisory: Analyzes short-term climate risks to trigger precise, localized alerts for sowing, irrigating, or harvesting.

3. Financial & Market Intel: Processes live market price trends to deliver actionable, data-backed advice on whether to sell or hold harvests.

4. Waste Value Creation: Replaces harmful practices like waste burning by providing step-by-step guidance on composting or repurposing agricultural biomass.

5. Multilingual AI Bot & Schemes Gateway: An NLP-based intent gateway that processes voice and text inputs across 12+ vernacular languages, sending proactive alerts regarding market spikes and government schemes.

Developed by Team Terminal Titans @ Delhi Technological University Project for the KRITI Social Impact Challenge 2026
