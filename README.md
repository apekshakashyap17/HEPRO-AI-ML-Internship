# HEPro AI — AI/ML Internship

Work completed during an AI/ML internship at HEPro AI (Jan 2026 – Mar 2026), focused on building an intelligent student mentoring and risk segmentation system.

## What it does

Identifies at-risk students from behavioral and academic data, segments them into risk tiers, and automatically matches them to specialist mentors based on their specific deficit areas.

## How it works

1. Student dataset is loaded and preprocessed — feature engineering across 15+ behavioral and academic indicators
2. K-Means Clustering segments 110 students into 4 risk tiers
3. A rule-based scoring engine computes a Student Readiness Index (SRI) for each student
4. PCA dimensionality reduction, Min-Max normalization, and class balancing applied for model robustness
5. A Priority-Greedy allocation algorithm matches at-risk students to mentors based on domain deficit scores (Academic, Wellness, Career)

## Results

- 100% allocation rate for high-risk cases
- 92% expertise-alignment across mentor assignments

## Tech Stack

- **Clustering:** Scikit-learn (K-Means)
- **Preprocessing:** PCA, Min-Max normalization, class balancing
- **Language:** Python
- **Notebooks:** Jupyter

## Files

- `notebook.ipynb` — main clustering and SRI pipeline
- `mentors.ipynb` — mentor allocation algorithm
- `students_updated_SRI.csv` — student dataset with computed SRI scores
- `final_recommendations.csv` — final mentor assignment output
- `Activity 2 Scoring logic and thresholds.pdf` — scoring methodology
- `Activity 3 cluster interpretation.pdf` — cluster analysis report
