# Youth Unemployment and Education Mismatch in Nigeria
### A Data-Driven Analysis (2016–2024)

**Author:** Onyiobazi Ejemot Aquah  
**Data Source:** [ILOSTAT - International Labour Organization](https://ilostat.ilo.org)  
**Tools:** Excel · Python (Pandas & Matplotlib)  
**Status:** Portfolio Project - Data Analytics  

---

## 📌 Project Overview

Nigeria is one of the youngest countries in the world, yet millions of its young people, many of them formally educated remain unemployed. This project examines youth unemployment in Nigeria between 2016 and 2024, with a specific focus on whether higher education corresponds to better employment outcomes.

The central finding is striking: **educated youth consistently account for between 79% and 87% of all unemployed youth in Nigeria** across every survey year the exact opposite of what economic theory predicts.

This project is grounded in **Human Capital Theory** (Schultz, 1961; Becker, 1964), which predicts that education increases individual productivity and employability. The data tests that prediction directly in the Nigerian context and finds compelling evidence of a **structural education-employment mismatch**.

---

## Dashboard Preview

![Educated Youth as Share of Total Unemployment](charts/chart4_mismatch_trend.png)

> **What this chart shows:** Intermediate and Advanced educated youth, those who completed secondary school through to university degree level, account for between **78.9% and 86.9% of all unemployed youth** across every survey year. This metric never drops below 78.9%, never approaches 50%, and shows no meaningful improvement over eight years. That persistence is the definition of a structural problem.

---

## 🔍 Key Findings

### Finding 1 — Youth Unemployment Is Volatile, Not Resolved

| Year | Unemployed Youth |
|------|-----------------|
| 2016 | 2.83 million |
| 2019 | 2.58 million |
| 2022 | 1.82 million |
| 2023 | 1.49 million |
| 2024 | 2.19 million |

After years of gradual decline, youth unemployment **rebounded sharply by ~700,000 in 2024**; confirming that the problem is structurally embedded, not cyclically resolved.

### Finding 2 — Educated Youth Dominate the Unemployment Pool

| Education Level | 2016 | 2019 | 2022 | 2023 | 2024 |
|----------------|------|------|------|------|------|
| Less than Basic | 11.6% | 2.8% | 5.0% | — | 1.5% |
| Basic | 7.5% | 15.9% | 11.7% | 19.7% | 11.6% |
| Intermediate | 55.1% | 57.3% | 71.8% | 69.0% | 65.1% |
| Advanced | 25.8% | 24.0% | 11.5% | 9.9% | 21.8% |

Youth with little or no education represent the **smallest and declining** share of the unemployed pool. Those who completed secondary school and above make up the **largest and persistent** share directly contradicting Human Capital Theory.

### Finding 3 — The Mismatch Is Structural

The **Mismatch Index** (Intermediate + Advanced share of total unemployment) never falls below 78.9% across any survey year, regardless of economic conditions or government policy cycles. This is not cyclical friction, it is a structural feature of Nigeria's education-to-employment pipeline.

---

## 💡 Result Interpretation

The data tells a clear story: **Nigeria's labour market is not rewarding education the way economic theory promises.**

Human Capital Theory expects a negative relationship between education level and unemployment; more education, less unemployment. In Nigeria, the opposite is true. The most educated youth are the most unemployed. This points to one of two structural failures (or both simultaneously):

1. **Demand-side failure:** Nigeria's formal private sector is too small and too informally structured to absorb the volume of qualified graduates the education system produces. The economy is not generating enough quality jobs for educated workers.

2. **Supply-side mismatch:** The type of education being delivered; its curriculum, its emphasis, its outputs does not correspond to the skills and competencies that Nigeria's labour market actually demands. Graduates are qualified on paper but unprepared for the roles that exist.

The fact that the Mismatch Index has not improved over eight years; through economic cycles, policy changes, and educational expansion confirms that neither the market nor existing policy has corrected this problem. It requires deliberate structural intervention.

---

## Policy Recommendations

**1. Curriculum Reform Tied to Labour Market Data**  
Nigeria's educational curricula must be regularly reviewed against actual employer needs, particularly in high-growth sectors: technology, logistics, financial services, and clean energy. National skills councils, as recommended by Adeagbo et al. (2025) — should drive this process with real-time labour market data.

**2. Expand Technical and Vocational Education**  
The data does not suggest that less education is the answer, it suggests that *different* education is needed. Investment in high-quality, industry-partnered technical and vocational pathways could provide a more direct pipeline to employment than academic qualifications alone.

**3. Private Sector Development as a Youth Employment Strategy**  
Education reform alone cannot solve a demand-side problem. Nigeria's formal private sector must grow, diversify, and create quality employment opportunities. Policy must treat private sector development particularly in non-oil sectors as inseparable from the youth employment agenda.

---

## 📁 Repository Structure

```
youth-unemployment-nigeria/
│
├── data/
│   ├── Nigeria_s_Youth_Unemployment_Dataset_Cleaned_Sourced_From_ILOSTAT.xlsx
│   └── Youth_Unemployment_Dataset_sourced_from_ILOSTAT__2016-2024_.xlsx
│
├── charts/
│   ├── chart1_trend.png
│   ├── chart2_education_share.png
│   ├── chart3_mismatch_2016_vs_2024.png
│   └── chart4_mismatch_trend.png
│
├── report/
│   └── youth_unemployment_nigeria.pdf
│
├── docs/
│   ├── code_documentation.docx
│   └── data_dictionary.docx
│
├── analysis.py
├── requirements.txt
└── README.md
```

---

## How to Run the Analysis

**1. Clone the repository**
```bash
git clone https://github.com/OnyiobaziAquah/youth-unemployment-nigeria.git
cd youth-unemployment-nigeria
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Place the dataset in the same folder as `analysis.py`**  
The script expects: `Nigeria_s_Youth_Unemployment_Dataset_Cleaned_Sourced_From_ILOSTAT.xlsx`

**4. Run the script**
```bash
python analysis.py
```

All four charts will be exported as high-resolution PNG files in the working directory.

---

## References

- Adeagbo, J., Mosobalaje, R., & Olaoye, O. (2025). Educational policies and labour market demands in Nigeria. *Emmanuel Alayande University of Education Journal of Multidisciplinary Studies, 2*(1). https://doi.org/10.60787/eaued-jms.vol2no1.31
- Becker, G. S. (1964). *Human capital.* Columbia University Press.
- Begho, T., & Daubry, T. P. (2025). Reducing youth unemployment in Sub-Saharan Africa through agriculture and agribusiness. *Discover Global Society, 3*, 81. https://doi.org/10.1007/s44282-025-00182-9
- Fox, L., & Gandhi, D. (2021). *Youth employment in sub-Saharan Africa: Progress and prospects* (AGI Working Paper No. 28). Brookings Institution.
- Schultz, T. W. (1961). Investment in human capital. *The American Economic Review, 51*(1), 1–17.
- Spence, M. (1973). Job market signalling. *The Quarterly Journal of Economics, 87*(3), 355–374.

---

## Connect

**GitHub:** [OnyiobaziAquah](https://github.com/OnyiobaziAquah)  

---

*Data sourced from ILOSTAT (International Labour Organization). Analysis conducted independently for portfolio purposes.*
