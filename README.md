# Applied Machine Learning Case Studies

Applied investigations in image recognition, customer churn, traffic signs, face recognition and clustering.

**Author:** Mohammed Alaa Eddine GUERBOUZ  
**University:** University of Ghardaia, Department of Mathematics and Computer Science  
**Academic period:** 2023–2025 master coursework where confirmed; some items have unverified dates  
**Portfolio curated:** 2026

## What this work demonstrates

This repository preserves practical assignments and projects completed during the academic programme, reorganized by problem rather than original archive names. It contains actual submitted code and reports, enhanced notebook introductions and descriptive folder names. It is not a claim of recent creation or independent production deployment.

## Project catalog

### 2024-2025 · projects

| Work | Problem addressed |
|---|---|
| [Bike-share Trip Clustering](projects/2024-2025/bike-share-trip-clustering/README.md) | Find patterns or groups in urban bike-share trip records. |
| [Customer Churn Prediction with an ANN](projects/2024-2025/customer-churn-ann/README.md) | Predict whether customers are likely to leave a service. |
| [ORL Face Recognition](projects/2024-2025/orl-face-classification/README.md) | Distinguish identities from a small academic face image dataset. |
| [Traffic Sign Recognition: SVM versus CNN](projects/2024-2025/traffic-signs-svm-vs-cnn/README.md) | Compare classical image features and convolutional models for road-sign classification. |
### undated · projects

| Work | Problem addressed |
|---|---|
| [Iris ANN: Early Coursework Variant](projects/undated/iris-ann-early-variant/README.md) | Build a small neural-network classifier on Iris flower measurements. |

## Working with the notebooks

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
jupyter lab
```

Open and run a notebook from its project folder so relative paths work. Some datasets are not included; each experiment README identifies missing local or remotely downloaded inputs. GPU-enabled TensorFlow, older APIs and Colab-specific shell commands may require compatible environments. R coursework also requires R/RStudio and packages used by the original code.


## Notes about the original sources

- Original notebook **code cells were not refactored or rewritten**. A clearly labeled Markdown introduction was added to notebooks for provenance and readability.
- Original DOCX reports and supporting images were only renamed and moved; their content remains byte-for-byte identical.
- Some notebooks rely on missing datasets, local Windows paths, network downloads, old libraries or GPU resources and **have not been rerun or benchmarked**. No unverified accuracies are claimed.
- Notebook years in the original headers are usually **Master 1 2023–2024** or **Master 2 2024–2025**. Where the period is inferred from a neighboring numbered TP series or not explicit in a particular source notebook, the project README says so. Other dates are sourced from the original notebook headers.
- Review licenses/redistribution rights for third-party datasets before pushing publicly. Large binary datasets, generated artifacts and serialized R workspaces should not be committed without review.

For original filename-to-new-path tracking, see `PORTFOLIO_INVENTORY.csv` at the top level of the consolidated download (not included in this individual repository).
