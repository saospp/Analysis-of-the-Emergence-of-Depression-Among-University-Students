[README.md](https://github.com/user-attachments/files/35414225/README.md)
# Analysis of the Emergence of Depression Among University Students

## Project Overview
Mental health among university students is a critical issue influenced by academic demands, lifestyle habits, and socioeconomic pressures. This project presents an Exploratory Data Analysis (EDA) of the **Student Depression Dataset** (27,901 student records across 18 initial features) to uncover key demographic, academic, and lifestyle patterns associated with student depression.

---

## Repository Structure
* `Student Depression Dataset.csv` — Raw dataset containing student survey records.
* `data_analysis.ipynb` — Data cleaning, missing value imputation, feature engineering, and statistical exploration.
* `data_viz.ipynb` — Visual exploration of distributions, correlations, and risk factors.

---

## Key Methodology & Workflow

### 1. Data Cleaning & Preprocessing (`data_analysis.ipynb`)
* **Missing Value Handling:** Applied statistical median imputation to preserve data integrity.
* **Feature Selection:** Removed zero-variance and non-informative columns (`id`, `Work Pressure`, `Job Satisfaction`).
* **Encoding:** Converted binary categorical variables into numerical format for statistical analysis.

### 2. Feature Engineering (`data_analysis.ipynb`)
* **`Total_Pressure`:** Combined academic pressure and financial stress metrics into a unified stress indicator.
* **`Age_Group`:** Segmented continuous age data into distinct student age brackets for comparative analysis.

### 3. Visual Exploration (`data_viz.ipynb`)
* Analyzed the relationship between depression rates and key risk factors, including:
  * Sleep duration and dietary habits
  * Academic workload and financial stress levels
  * Family history of mental illness and history of suicidal thoughts

---

## Tech Stack
* **Language:** Python 3
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/saospp/Analysis-of-the-Emergence-of-Depression-Among-University-Students.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Analysis-of-the-Emergence-of-Depression-Among-University-Students
   ```
3. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
4. Launch Jupyter Notebook and open `data_analysis.ipynb` or `data_viz.ipynb`:
   ```bash
   jupyter notebook
   ```
