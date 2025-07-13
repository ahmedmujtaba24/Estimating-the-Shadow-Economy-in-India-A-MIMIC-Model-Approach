# 🕵️ Estimating the Shadow Economy in India (2011–2022)  
**A MIMIC Econometric Modeling Approach using Python + Macroeconomic Data**

---

## 📌 Overview
This repository contains the full codebase, data, model outputs, and figures from a research paper titled:

> **"Estimating the Shadow Economy in India: A MIMIC Model Approach"**

The study explores one of the most persistent challenges in development economics — the **hidden or informal economy** — which remains outside the scope of official statistics yet plays a major role in employment and output in countries like India.

We estimate the size, evolution, and structure of India’s shadow economy over 2011–2022 using a **proxy-based MIMIC (Multiple Indicators Multiple Causes) model**, with rigorous time-series validation, ARIMA forecasting, and causal interpretation.

---

## ❓ What Does This Paper Answer?
- How large is India’s shadow economy, and how has it evolved since 2011?
- What economic or institutional factors influence its size? (e.g., unemployment, tax burden, inflation, EoDB)
- Can observable indicators like **nighttime light intensity** and **money supply (M2)** help measure this latent sector?
- How did major events like **GST**, **demonetization**, and **COVID-19** impact informal activity?

---

## 📊 Key Highlights
- ✅ Constructs a **latent index** of the shadow economy using standardized causal variables
- 📈 Regresses four robust indicators (M2 supply, labor force participation, nighttime lights, tax revenue)
- 🔬 Applies **residual diagnostics**: VIF, Breusch-Pagan (heteroskedasticity), Ljung-Box (autocorrelation)
- 📉 Forecasts 2023–2027 shadow economy using ARIMA modeling
- 💡 Estimates that **India’s shadow economy was ~20.9% of GDP in 2022**, valued at ₹5.59 lakh crore

---

## 🧰 Tools & Libraries
- Python (pandas, statsmodels, numpy, matplotlib, seaborn)
- Jupyter Notebook (.ipynb)
- Excel (for data cleaning & preprocessing)

---

## 📁 File Structure

```
shadow-economy-india/
├── data/                   # Raw + processed macroeconomic datasets  
├── models/                # MIMIC model + ARIMA + regression scripts  
├── missing_data/          # Interpolation + assumptions  
├── notebooks/             # Jupyter analysis walkthroughs  
├── figures/               # PNGs of graphs, diagnostics, outputs  
├── output/                # CSVs with shadow economy estimates + forecasts  
├── README.md              # Project summary and documentation  
├── requirements.txt       # Python dependencies  
└── LICENSE                # Open license (MIT)
```

---

## 📌 Use Cases
- Undergraduate or Master's thesis in **Development Economics**
- IMF/UNDP-style modeling of latent variables
- Public policy evaluation of India's informal sector
- Teaching econometrics with real India-specific data

---

## 👤 Author
**Mujtaba Ahmed**  
B. Borooah College – Economics Hons. (Quantitative Stream)  
Working on research in shadow economy, financial inclusion, and causal modeling.

📫 *Let's connect:* [LinkedIn](https://www.linkedin.com/in/mujtabaahmed24/) • [GitHub](https://github.com/ahmedmujtaba24) • [Email](mailto:ahmedmujtabamp4@gmail.com)

---

> This repository was created as part of a research submission for international academic publication.
> For collaboration, reproduction, or questions, feel free to reach out.
