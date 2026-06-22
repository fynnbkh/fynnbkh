<div align="center">

# Hey, I'm Fynn 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fynn-barkhausen/)

</div>

---

## 🎓 About me

I'm finishing an MSc in Analytics & AI at ESMT Berlin. Before the master's I spent time in management consulting and BI consulting, and earlier than that in production and industrial roles. The part I actually enjoy is the bit between the data and the people who have to act on it: figuring out what the real question is before building anything to answer it.

- MSc Analytics & AI, ESMT Berlin
- Background in consulting (management and BI) plus earlier industrial roles
- Most interested in the point where an analysis changes a decision someone actually makes
- Based in Berlin

---

## 🛠️ Skills & technologies

### 🐍 Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### 📊 Data & AI

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

### ⚙️ Tools & platforms

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### ☁️ Cloud & deployment

![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex%20AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Cloud Run](https://img.shields.io/badge/Cloud%20Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### 💼 Business & productivity

![Microsoft Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Microsoft PowerPoint](https://img.shields.io/badge/PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)
![Microsoft Word](https://img.shields.io/badge/Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)

---

## 📂 Selected work

**Master's thesis: minimum-wage reform and short-term rentals**

Does a sharp minimum-wage increase move prices and occupancy in the Airbnb market?   
I'm testing this on Montenegro's "Europe Now" reform, using a matched difference-in-differences design with Albania as the control. The dataset is roughly 33,000 listings from AirDNA.
The estimation runs in Python with `pyfixest`: coarsened exact matching on host and listing characteristics, listing and year fixed effects, standard errors clustered by listing, and the price outcomes split apart so the labour-cost channel can be tested on its own rather than assumed. Code and writeup will go public after submission. The AirDNA data is licensed, so it stays out of the repo.
`Python` `pyfixest` `pandas` `causal inference`

**Analytics consulting project: predicting sales outcomes in a CRM**

A three-month ESMT team project on real CRM data from a German company. The brief was to forecast how individual sales opportunities resolve: whether each deal is won or lost, when it closes, and what the predictions add up to once aggregated across business units, regions, and product groups. I led the close-timing piece, a survival model that estimates when a deal lands rather than only whether it does. The finding that stuck with me was less about model accuracy than about the data underneath it: a large share of the win-probability fields in the CRM had never been moved off their default value, so much of the existing pipeline forecast rested on numbers nobody had actually set. The models are now in discussion for a trial deployment, and the work became the basis for rethinking how sales reps are incentivised.
`Python` `XGBoost` `survival analysis` `scikit-learn`

**End-to-end ML deployment on Google Cloud**

A group project where we picked the problem and data ourselves, then took a model the whole way to a running cloud service rather than stopping at a notebook. We split the pipeline into containerised steps (feature engineering, training, inference), pushed the images to Artifact Registry, ran them as Cloud Run Jobs, and chained them into a Cloud Workflows DAG. The model is served behind a FastAPI endpoint, with logging and basic monitoring on top. The part I find most useful in hindsight is how much of the work is everything around the model: deployment strategy, versioning, and knowing when something has quietly broken in production.
`Python` `Docker` `GCP` `Vertex AI` `Cloud Run` `FastAPI`

---

## 📬 Get in touch

Happy to talk. Easiest way to reach me is LinkedIn.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fynn-barkhausen/)

</div>
