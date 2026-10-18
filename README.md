# Spanish Affective Dynamics & Digital Dating Analysis

Quantitative research project analyzing romantic beliefs, consumption patterns, and dating app adoption in Spain using official microdata from the **CIS Survey 3508** (*Centro de Investigaciones Sociológicas*).

## 📌 Project Overview
This study explores how traditional romantic ideals interact with commercialized dating rituals and digital dating platforms across different demographics in Spain. Using **Python**, the project applies data cleaning protocols, synthetic index construction, and unsupervised **K-Means clustering** to identify latent behavioral profiles.

## 🛠️ Tech Stack & Methods
- **Language & Tools:** Python (Pandas, NumPy, SciPy, Scikit-Learn, Statsmodels, Seaborn).
- **Data Source:** CIS Survey 3508 (`3508.sav` SPSS microdata).
- **Data Pipeline:**
  1. Strict handling of survey non-responses and structural filter values (NS/NC/NAP).
  2. Construction of 0–100 synthetic indices: *Romantic Myths*, *Romantic Consumption*, and *Digital Dating Acceptance*.
  3. Sample weighting (*PESO*) adjustment for population representativeness.
  4. Unsupervised segmentation via **K-Means Clustering** (evaluated through Elbow Method & Silhouette Analysis).
  5. Weighted Least Squares (**WLS**) regression modeling.

## 📊 Key Findings & Latent Clusters
- **Cluster 0 ("Detached Pragmatists" - 25.9%):** Low adherence to traditional romantic myths, moderate consumption, and lower app acceptance. Predominantly older demographic.
- **Cluster 1 ("Analog Traditionalists" - 36.6%):** High romantic idealization and consumption rituals, but complete disconnect/rejection of digital dating apps.
- **Cluster 2 ("Digital Romantics" - 37.5%):** Highest representation of Gen Z and Millennials. Successfully integrates dating app usage with high valuation of romantic rituals and traditional myths.

## 📁 Repository Structure
├── docs/                                               # Methodological documentation & full report
│   ├── metodologia_recodificacion.md
│   └── El_amor_en_la_Espana_digital.pdf                # Full research report (Spanish)
├── output_plots/                                       # Visualizations & cluster CSVs
│   ├── resumen_clusters_ponderado.csv
│   ├── grafico_perfiles_clusters.png
│   └── grafico_inferencial_mitos.png
├── CIS_3508_Analisis_Amor_Multidimensional (1).ipynb   # Jupyter Notebook with full code
├── README.md                                           # Project overview (English)
└── requirements.txt                                    # Python dependencies

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/javierechube14/social-data-analysis-cis3508.git](https://github.com/javierechube14/social-data-analysis-cis3508.git)
   Install dependencies:

Bash
pip install -r requirements.txt
Run CIS_3508_Analisis_Amor_Multidimensional (1).ipynb in Google Colab or Jupyter Lab.

Author: Javier Echube Bestue | Sociology Student & Aspiring Social Data Analyst
