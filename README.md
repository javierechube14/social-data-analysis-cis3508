# Love, Consumption and Digitalisation in Spain

### An Exploratory Sociological Analysis of CIS Survey 3508

**An independent research project exploring romantic beliefs, consumption-related relationship rituals and attitudes towards dating apps in Spain.**

## 1. Project Overview

This project examines how different understandings of romantic relationships coexist in contemporary Spanish society.

Using microdata from **Study 3508 of the Spanish Centre for Sociological Research (CIS)**, I explore three dimensions:

- **Romantic beliefs:** agreement with selected traditional ideas about romantic love.
- **Romantic consumption rituals:** the importance attributed to activities such as romantic dinners, trips and gifts.
- **Digital dating attitudes:** respondents' attitudes towards dating applications.

The main objective is to explore whether these dimensions are associated and identify different attitudinal profiles within the population.

This is an **exploratory quantitative study**, not a causal analysis.

## 2. Research Questions

The project addresses three main questions:

1. How are romantic beliefs, consumption-related rituals and attitudes towards dating apps associated?
2. Are there differences in these attitudes across sociodemographic groups, particularly by age and gender?
3. Can distinct profiles of romantic attitudes be identified through exploratory clustering?

## 3. Data Source

- **Institution:** Centro de Investigaciones Sociológicas (CIS)
- **Study:** 3508
- **Country:** Spain
- **Data type:** Survey microdata
- **Original language:** Spanish

Official source: [CIS – Study Catalogue](https://www.cis.es/)

The analysis uses selected questionnaire variables. The original survey data should be obtained from the CIS.

## 4. Methodology

The analysis was developed using **Python and Google Colab**, combining data preparation, descriptive statistics and exploratory statistical techniques.

### Data Preparation

- Identification and treatment of missing and non-substantive responses.
- Recoding of selected survey variables.
- Construction of three composite indices on a 0–100 scale.

### Statistical Analysis

- Descriptive comparisons between sociodemographic groups.
- Exploratory statistical tests.
- Weighted descriptive analyses where applicable.
- K-Means clustering to identify attitudinal profiles.

### Composite Indices

| Index | Variables | Interpretation |
|---|---|---|
| Romantic Beliefs | `P4_3`, `P4_4` | Agreement with selected romantic beliefs |
| Romantic Consumption Rituals | `P7`, `P8`, `P9` | Importance attributed to selected relationship rituals |
| Digital Dating Attitudes | `P16_6`, `P16_7` | Attitudes towards dating applications |

These indices are operational measures based on a limited number of survey items. They should not be interpreted as comprehensive measures of romantic ideology, actual consumer expenditure or dating-app usage.

Further details are available in the methodological documentation.

## 5. Main Exploratory Findings

The exploratory K-Means analysis identified three attitudinal profiles based on the selected romantic beliefs, consumption-related rituals and digital dating indices.

| Profile | Weighted Share | Romantic Beliefs | Consumption Rituals | Digital Dating Attitudes |
|---|---:|---:|---:|---:|
| Pragmatic / Less Romantic | 28.5% | 35.20 | 41.38 | 36.70 |
| Traditional / Digitally Sceptical | 34.2% | 71.39 | 85.62 | 13.12 |
| Romantic / Digitally Receptive | 37.3% | 61.42 | 87.18 | 59.38 |

*Index values range from 0 to 100. The percentages represent the weighted distribution reported in the exported cluster summary.*

The most notable exploratory finding is the coexistence of relatively strong romantic beliefs, high importance attributed to consumption-related rituals and favourable attitudes towards digital dating in the third profile.

This suggests that openness towards dating technologies does not necessarily involve rejecting traditional romantic ideals.

The profiles are descriptive and depend on the selected variables, index construction and clustering procedure. They should not be interpreted as fixed population categories or causal explanations.
## 6. Tools and Skills

**Programming and analysis**
- Python
- pandas and NumPy
- SciPy and statsmodels
- scikit-learn
- Matplotlib and Seaborn

**Research methods**
- Survey microdata processing
- Variable recoding
- Composite index construction
- Descriptive and comparative statistics
- Exploratory clustering
- Critical interpretation of quantitative results

## 7. Repository Structure

- **`README.md`** — Project overview and documentation in English.
- **`requirements.txt`** — Python package dependencies.
- **`docs/`** — Full research report in Spanish and methodological documentation.
- **`output_plots/`** — Exported analytical results, including the weighted cluster summary.
- **Python notebook (`.ipynb`)** — Data preparation, analysis and statistical procedures, available in the repository.

## 8. Reproducibility

To reproduce the analysis:

1. Download the original microdata for CIS Study 3508 from the official CIS website.
2. Open the Python notebook in Google Colab or a compatible Jupyter environment.
3. Install the dependencies listed in `requirements.txt`.
4. Adjust the dataset path to match your local or Colab environment.
5. Run the notebook, checking the recoding decisions described in the methodological documentation.

The original CIS microdata are not included in this repository.

## 9. Limitations

Several limitations should be considered:

- The selected questionnaire items capture specific aspects of romantic beliefs and digital dating attitudes, rather than these concepts in their entirety.
- Attitudes towards dating applications are not equivalent to actual app usage.
- The consumption-related variables do not directly measure expenditure.
- Clustering is exploratory and depends on methodological decisions.
- Descriptive associations cannot establish causality.

These limitations are important when interpreting the results.

## 10. About the Author

I am a **Sociology student at the University of Valencia (Spain)**, interested in quantitative social research, social inequalities and the relationship between social change and digital technologies.

This project is part of my independent learning process in Python and data analysis. My aim is to develop a portfolio that combines sociological theory, empirical research and reproducible analytical methods.

**Research report:** Available in Spanish in the `docs/` folder.

**Project language:** English documentation; Spanish research report.

Bash
pip install -r requirements.txt
Run CIS_3508_Analisis_Amor_Multidimensional (1).ipynb in Google Colab or Jupyter Lab.

Author: Javier Echube Bestue | Sociology Student & Aspiring Social Data Analyst
