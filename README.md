# Computational GWAS Pipeline in Python
Implementation of a simplified Genome-Wide Association Study (GWAS) using simulated SNP data, statistical association testing, and genomic visualization.

## 🔬 Skills Demonstrated

- GWAS statistical modeling
- Logistic regression
- P-value interpretation
- Manhattan & QQ plot visualization
- Data pipeline structuring

- This project implements a simplified Genome-Wide Association Study (GWAS) pipeline using simulated genotype data.

The objective is to:

Simulate SNP genotype data

Generate a phenotype with true causal variants

Perform association testing

Identify significant SNPs

Visualize results using Manhattan and QQ plots

This project was implemented in Google Colab and results are saved to Google Drive.

🧠 Methods Used
1️⃣ Data Simulation

500 individuals

1000 SNPs

Genotypes coded as 0, 1, 2

First 5 SNPs set as causal variants

2️⃣ Association Testing

Logistic regression using statsmodels

P-values extracted for each SNP

3️⃣ Visualization

Manhattan Plot

QQ Plot

Top 10 significant SNPs ranking

📊 Results

Significant SNPs clearly detected

QQ plot shows deviation from null expectation

True causal SNPs ranked among top hits

📂 Project Structure
Mini-GWAS-Project/
├── data/
├── results/
├── Mini_GWAS_RSV.ipynb
├── requirements.txt
└── README.md
🛠 Technologies Used

Python

NumPy

Pandas

Matplotlib

SciPy

Statsmodels

Google Colab

How to Run

Clone the repository

Install dependencies:

pip install -r requirements.txt

Run the notebook in Jupyter or Google Colab

 Author

Bioinformatics Master's Student
Focus: Genomics & Machine Learning
