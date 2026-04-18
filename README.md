# Government Aadhar Hackathon Project

Data Analysis and Anomaly Detection on Aadhar Demographic & Enrolment Data

---

## 📌 Project Overview

This project was developed as part of a Government Hackathon focused on analyzing large-scale Aadhar datasets.

The objective is to:

- Analyze demographic and enrolment datasets
- Identify abnormal or suspicious enrollment patterns
- Detect dominant biometric trends by pincode
- Flag potential anomalies for further investigation

---

## 🗂️ Dataset Description

The project uses:

- Aadhar Demographic API Data
- Aadhar Enrolment API Data
- Pincode-based biometric dominance dataset

Data includes:

- Enrollment counts
- Gender distribution
- Biometric type dominance
- Regional (pincode-level) breakdown

⚠️ Large raw datasets are not included in this repository.

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📊 Key Features

- Data cleaning and preprocessing
- Large CSV handling (chunk processing)
- Pincode-level aggregation
- Biometric dominance detection
- Flagging suspicious trends
- Visualization of key insights

---
## 📁 Project Structure

govt_hackathaon/
│
├── main.ipynb # Main analysis notebook
├── flagged_pincode_dominant_bio.xlsx # Output file (if generated)
├── api_data_aadhar_demographic/ # Raw demographic data (ignored in repo)
├── api_data_aadhar_enrolment/ # Raw enrolment data (ignored in repo)
├── problem statement.png # Hackathon problem statement
├── submission guideline.png # Submission guidelines
└── README.md


---

## 🚀 How to Run

### 1️⃣ Clone Repository

```bash
git clone https://github.com/satya-py/Goverment-Adhar-Hackathon.git
cd Goverment-Adhar-Hackathon
pip install pandas numpy matplotlib seaborn openpyxl

jupyter notebook

📈 Output

The notebook generates:

Aggregated statistical summaries
Flagged pincode-level anomalies
Visual insights
Excel output file (if exported)

🔎 Approach
Load large CSV files using chunk processing.
Clean missing or inconsistent values.
Aggregate data at pincode level.
Compute biometric dominance metrics.
Apply threshold-based anomaly detection.
Generate flagged dataset.

⚠️ Limitations
Dependent on dataset completeness.
Threshold-based anomaly detection may require tuning.
Real-time API integration not implemented.


📜 License

This project is for educational and hackathon purposes only.


---








