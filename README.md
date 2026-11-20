# Prachi Khatri

Final-year CSE student at KIIT (graduating 2027), looking for software engineer and ML roles.

[Portfolio](https://portfolio-kappa-smoky-83.vercel.app) / [LinkedIn](https://linkedin.com/in/p2506) / [LeetCode](https://leetcode.com/u/prachi_2506) / prachikhatri2506@gmail.com

## Projects

**[AI Auction Arena](https://github.com/prachi-2506/AI-Auction-Arena)** - Two neural-network bidders learn first-price auction strategy from scratch with REINFORCE self-play (120,000 episodes), benchmarked against the Nash strategy b(v)=0.5v and regret matching. Each agent trains for 2,000 episodes against a frozen opponent before they swap, so neither chases a moving target. [Live demo](https://ai-auction-arena.streamlit.app)

**[CircuitGuard](https://github.com/prachi-2506/Circuit-Guard)** - PCB defect detection with YOLO11m (0.982 mAP@50, 0.560 mAP@50-95 across 6 defect classes). A FastAPI inference service sits behind a Streamlit UI that exports batch results as PDF, CSV and ZIP.

**[NagarMitra](https://github.com/prachi-2506/NagarMitra_Eurekon)** - Civic complaint platform built for SIH 2025 with a team of six; I wrote the Express/MongoDB backend (39 REST endpoints across 7 route modules, presigned S3 uploads, a Telegram status bot). MobileNet runs in-process with TensorFlow.js and its labels are mapped to six civic categories, so there is no separate ML service to host.

**[PashuMitra](https://github.com/prachi-2506/PashuMitra-translator)** - Multilingual livestock biosecurity portal, built with a team in 5 days after our SIH problem statement hit its entry cap. The Node backend calls IndicTrans2 through a Python subprocess bridge and caches translations for an hour.

**[Spendora](https://github.com/prachi-2506/Spendora)** - Expense tracker on React 18 and Firebase with CSV import and Recharts analytics. Firebase listeners keep the dashboard in sync, and a budget warning fires at 80 percent of the limit.

**[LeetCode duplicate finder](https://github.com/prachi-2506/Leetcode-duplicate-question-identifier)** - Embeds LeetCode problem titles with a small MLP over TF-IDF features, trained with a cosine loss on similar and random title pairs. Search runs through a Streamlit app.

## Achievements

**Amazon ML Summer School 2025** - Selected from about 60,000 applicants (~3,000 selected).

**Amazon HackOn 2025** - Top 50 Female Coder nationally, out of 60,000+ participants.

**Smart India Hackathon 2025** - Team Lead; 3rd of 521 teams at the KIIT internal round.

**Stack:** Python, PyTorch, Node.js, Express, MongoDB, React, Firebase, FastAPI, Streamlit, TensorFlow.js, Ultralytics YOLO, AWS S3.
