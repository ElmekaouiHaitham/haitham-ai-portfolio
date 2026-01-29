# AI & Engineering Portfolio | Haitham Elmekaoui
**Specialized in NLP, Generative AI, and Quantitative Machine Learning**

Professional showcase of end-to-end AI solutions, startup leadership, and competitive data science.

---

## 🏆 Key Achievements
* **4th Place Winner - Capgemini Techathon (2025):** Developed a high-impact technical solution under strict competitive constraints within 48 hours.
> ![Capgemini Achievement](assets/capgemini_win.png)

---

## 🚀 Professional Projects (NDA Restricted)
### 1. Intelligent Patent Monitor (USPTO)
**Domain:** NLP / Legal Tech / Lead Generation
* **The Challenge:** Building a system to monitor and classify massive volumes of USPTO patent filings to identify business leads with high precision and low latency.
* **Architecture & Implementation:**
    * **Few-Shot Learning with SetFit:** Implemented **SetFit (Sentence Transformer Fine-tuning)** to bypass the need for massive labeled datasets. This framework allows the model to learn from just a few examples by fine-tuning a Sentence Transformer on a contrastive objective.
    * **Classification Pipeline:** Developed a custom pipeline that ingests raw patent XML, extracts key technical claims, and uses cosine similarity in the embedding space to categorize patents into 50+ specialized business buckets.
    * **Scalability:** Optimized for high throughput, enabling the system to process thousands of filings per hour while maintaining a high F1-score.
* **Tech Stack:** Python, SetFit, HuggingFace Transformers, Pandas, Scikit-learn.
> ![Scott's Testimonial](assets/uspto_testimonial.png)

### 2. Maroc AI Agency Infrastructure
**Domain:** B2B AI Automation / SaaS
* **The Challenge:** Creating a scalable, high-conversion landing and waitlist system for a Moroccan AI startup focusing on B2B agentic automation.
* **Modern Web Architecture:**
    * **Next.js 15 App Router:** Implemented the latest Next.js features, including **Server Components (RSC)** for faster initial page loads and improved SEO performance.
    * **Edge Deployment:** Optimized for low latency using Vercel’s global Edge network to ensure a seamless experience for Moroccan and international users.
    * **Agentic Design:** Architecting the roadmap for LLM-based customer engagement agents using streaming APIs for real-time responsiveness.
* **Tech Stack:** Next.js 15, TypeScript, Tailwind CSS, Vercel, Framer Motion.
* **Link:** [maroc-ai.com](https://marocai.online)

## 🚀 Data science Project:
### Quantitative Financial Modeling (Numerai Tournament)
**Domain:** Quant Finance / Machine Learning
* **The Challenge:** Predicting stock market movements using encrypted, highly non-stationary financial data where feature-target relationships shift over "eras."
* **Advanced Technical Focus:**
    * **Second-Order Optimization (XGBoost):** Leveraged a deep understanding of **XGBoost's Second-Order Taylor Expansion**. Unlike traditional gradient boosting which uses only the first derivative (gradient), I utilized the **Hessian (curvature)** of the loss function to achieve more stable and precise updates in a volatile financial environment.
    * **Feature Neutralization & Exposure:** Implemented linear and non-linear **Feature Neutralization** to decorrelate model predictions from "risky" features. This process involves taking the residuals of the prediction vector through linear regression against the feature matrix, ensuring the model identifies true signal interactions rather than over-relying on high-exposure features.
* **Tech Stack:** Python, XGBoost (Newton Boosting), Scikit-learn, NumerAPI.
* **Link:** [Numerai Profile](https://numer.ai/~mr_x)

---

## 🛠 Skills & Frameworks
* **AI/ML:** PyTorch, Scikit-learn, XGBoost, SetFit, Feature Neutralization.
* **Web:** Next.js (SSR), TypeScript, Node.js.
* **Cloud & DevOps:** Vercel, Git, CI/CD, MLOps.

---

## 📬 Contact
* **LinkedIn:** [Profile](https://www.linkedin.com/in/haitham-elmekaoui-/)]
