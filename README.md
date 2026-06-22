# ChronoPulse AI: Luxury Watch Market Intelligence Engine

ChronoPulse AI is a high-performance, production-ready social listening and Aspect-Based Sentiment Analysis (ABSA) pipeline. It is specifically engineered to solve the market research problem of tracking consumer perception for premium and luxury watch brands across digital touchpoints.

The system extracts unstructured public comments, processes them through an advanced Generative NLP layer, and maps the insights into actionable corporate business metrics.

---

## 📊 Core Business Problems Solved
This project explicitly tracks and quantifies the following luxury market value drivers:
*   **Geographic Manufacturing Perception:** Quantifying how consumers value 'Made in France' vs. 'Swiss Made' vs. Chinese production.
*   **Artisanal Craftsmanship Pillar:** Automatically flagging mentions of watch movements, dial finishing, and *Métiers d’Art* (e.g., hand-lacquering).
*   **Price & Value Elasticity:** Monitoring whether the community perceives products as *Overpriced*, *Fair*, or a *Good Value*.
*   **Sustainability Traction:** Identifying organic consumer focus on eco-friendly practices and sustainable luxury materials.

---

## 🛠️ Architecture & Tech Stack

The pipeline is split into isolated modular layers to protect API quotas and maximize data retrieval efficiency:

*   **Data Ingestion:** Python integration with **YouTube Data API v3** featuring a robust pagination loop to extract 100% of target video comments.
*   **Generative NLP Layer:** High-speed inference using the **Llama 3.1 (8B Instant)** LLM hosted via **Groq Engine** for deep context, sarcasm detection, and linguistic mapping.
*   **Data Aggregation:** **Pandas** for structured data engineering, error-handling, and matrix generation.
*   **Business Intelligence UI:** **Seaborn** & **Matplotlib** for generating brand-ready visual distribution dashboards.

---

