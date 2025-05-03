# AI-powereed-stastical-analysis-tool

# AI-Powered SCD Analysis Tool

This project is a Streamlit-based web application designed to automate statistical analysis of Single-Case Design (SCD) data in behavioral studies. It supports multiple design types (ABA Reversal, Alternating Treatment, Multiple Baseline), offering both classical and Bayesian analysis methods.

---

Final_Submission/
├── Source Code/
│   ├── AIpowered statistical analysis tool.py
│   ├── DATASETS/
│       ├── ABA_reversal.xlsx               # Dataset for ABA Reversal Design
│       ├── Multiple-baseline.xlsx          # Dataset for Multiple Baseline Design
│       ├── SCD Hypothetical Datasets.xlsx  # Main dataset for hypothetical SCD scenarios
├── Final_Report.docx    
├── Final_Report.pdf
├── REFERENCES                               #Reference papers on statistical methods &Effcetive sixe caluclation 
├── README.md                                # Project documentation (current file)
├──requirements.txt                          # Required Python libraries
---

## 📋 Features

- Supports **ABA Reversal**, **Alternating Treatment**, and **Multiple Baseline** designs
- Performs statistical tests:
  - t-test, Wilcoxon Signed-Rank Test
  - Randomization Test, Friedman Test
  - Bayesian Logistic Regression
- Effect size calculations (PND, PEM, IRD)
- APA-style output for results
- Built-in normality checks and visualizations
- Interactive UI via Streamlit

---

## ✅ Requirements

- Python 3.8+
- Streamlit
- pandas, numpy, matplotlib, seaborn, scipy, statsmodels

You can install all dependencies using:

```bash
pip install -r requirements.txt






###If requirements.txt is not available, install manually:

pip install streamlit pandas numpy matplotlib seaborn scipy statsmodels


##How to Run the Application:

1.Open a terminal or command prompt.

2. Navigate to the directory containing your Python file:

cd "path/to/Source Code"

3.Launch the Streamlit app:

streamlit run "AIpowered statistical analysis tool.py"


##Dataset Format Guidelines
      Upload .xlsx (Excel) file via sidebar

      Each condition or phase should be a separate column

     Each row = one time point or measurement

     For multiple baseline: include Subject, Phase, and Value columns

##How to Use
    Select your Design Type (ABA, ATD, or MBD)

    Upload a dataset via the left sidebar

    Choose columns and statistical methods as prompted

##View:

       Visualizations

       Normality results

      Statistical test results

      APA-style formatted text

      Effect size metrics

##Final Report
The report includes:

      Problem Statement

      Methodology

      Implementation Screenshots

##Output Analysis

    Future Enhancements

    Both .docx and .pdf versions are included in the root folder.


##Notes
Make sure all your Excel files are correctly formatted.

The app trims data to the last 5 sessions in each phase to standardize comparisons.

The Bayesian module uses a Beta distribution with visual plots of posterior.





