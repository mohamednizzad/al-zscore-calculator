# 🎓 Sri Lanka A/L Z-Score Explorer

An interactive web tool that helps Sri Lankan GCE Advanced Level students understand where they stand among all A/L candidates — and how the Z-score is calculated by the University Grants Commission (UGC).

🔗 **Live App:** [mohamednizzad.github.io/al-zscore-calculator](https://mohamednizzad.github.io/al-zscore-calculator/)

---

## Features

- **Interactive bell curve** — drag the slider to any Z-score and see where it falls on the island-wide distribution
- **Percentile calculator** — instantly see what percentage of candidates scored below and above a given Z-score
- **Performance tier indicator** — from Below Average to Exceptional, with course competitiveness context
- **Step-by-step formula explainer** — covers how UGC calculates Z-scores from raw marks, subject means, and standard deviations
- **Try your own marks** — enter your raw marks, subject mean, and standard deviation for all three A/L subjects to compute your personal Z-score

---

## How the Z-Score Works

The UGC uses the following formula to standardise marks across all subjects:

```
Z = (x − μ) ÷ σ

Final Z-score = (Z₁ + Z₂ + Z₃) ÷ 3
```

Where:
- `x` = your raw mark in a subject
- `μ` = island-wide mean mark for that subject
- `σ` = standard deviation of all candidates' marks for that subject

This allows fair comparison across subjects with different difficulty levels and marking schemes.

---

## Usage

No installation needed. Simply open the live link in any browser:

👉 [https://mohamednizzad.github.io/al-zscore-calculator/](https://mohamednizzad.github.io/al-zscore-calculator/)

To run locally, clone the repo and open `index.html` in your browser:

```bash
git clone https://github.com/mohamednizzad/al-zscore-calculator.git
cd al-zscore-calculator
open index.html
```

---

## Tech Stack

- HTML5, CSS3, Vanilla JavaScript
- [Chart.js](https://www.chartjs.org/) for the bell curve visualisation
- Google Fonts (DM Serif Display, DM Sans, DM Mono)
- Hosted via GitHub Pages

---

## ⚠️ Disclaimer

This tool is developed **purely for educational purposes** to help students understand the Z-score system used in Sri Lanka's GCE Advanced Level university admissions process.

- The percentile and Z-score calculations are based on standard statistical models and are **approximations only**
- This tool does **not** use official UGC data, subject-specific means, or standard deviations
- **No academic, university admission, or career decisions should be made based on this tool**
- Always refer to the official [University Grants Commission of Sri Lanka](https://www.ugc.ac.lk) for accurate and authoritative information

---

## Connect

Built by **Mohamed Nizzad**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamednizzad/)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/mohamednizzad/)

---

## License

This project is open source and available under the [MIT License](LICENSE).
