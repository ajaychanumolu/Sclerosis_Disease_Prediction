# 🧠 Predictors of Sclerosis Disease

This project focuses on identifying the **key predictors** for the progression of **Clinically Isolated Syndrome (CIS)** to **Multiple Sclerosis (MS)** using clinical and imaging data. The dataset is derived from patients at the **National Institute of Neurology and Neurosurgery**, Mexico City (2006–2010).

> 🎯 Goal: Enable early MS diagnosis and support more effective treatment strategies through data-driven insights.

---

## 📊 Dataset Overview

The dataset contains various demographic, clinical, and diagnostic attributes for each patient.

### 🧾 Attributes

| Column Name              | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| `ID`                     | Patient identifier (int)                                                    |
| `Age`                    | Age of the patient (in years)                                               |
| `Schooling`              | Time spent in school (in years)                                             |
| `Gender`                 | 1 = Male, 2 = Female                                                         |
| `Breastfeeding`          | 1 = Yes, 2 = No, 3 = Unknown                                                 |
| `Varicella`              | 1 = Positive, 2 = Negative, 3 = Unknown                                     |
| `Initial_Symptoms`       | Encoded values representing symptoms at disease onset                       |
| `Mono_or_Polysymptomatic`| 1 = Mono, 2 = Poly, 3 = Unknown                                              |
| `Oligoclonal_Bands`      | 0 = Negative, 1 = Positive, 2 = Unknown                                     |
| `LLSSEP`                 | Lower Limb Somatosensory Evoked Potential (0 = Negative, 1 = Positive)      |
| `ULSSEP`                 | Upper Limb SSEP (0 = Negative, 1 = Positive)                                |
| `VEP`                    | Visual Evoked Potential (0 = Negative, 1 = Positive)                        |
| `BAEP`                   | Brainstem Auditory Evoked Potential (0 = Negative, 1 = Positive)            |
| `Periventricular_MRI`    | MRI marker presence (0 = Negative, 1 = Positive)                            |
| `Cortical_MRI`           | MRI marker presence (0 = Negative, 1 = Positive)                            |
| `Infratentorial_MRI`     | MRI marker presence (0 = Negative, 1 = Positive)                            |
| `Spinal_Cord_MRI`        | MRI marker presence (0 = Negative, 1 = Positive)                            |
| `initial_EDSS`           | EDSS score at diagnosis                                                     |
| `final_EDSS`             | EDSS score at follow-up                                                     |
| `Group`                  | 1 = CDMS (Confirmed MS), 2 = non-CDMS                                       |

---

## 🧬 Key Medical Terms

| Term | Description |
|------|-------------|
| **BAEP** | *Brainstem Auditory Evoked Potentials* — tests auditory nerve/brainstem function |
| **VEP** | *Visual Evoked Potential* — measures the speed of visual pathway responses |
| **SSEP (LL/UL)** | *Somatosensory Evoked Potentials* — assesses nerve responses in lower/upper limbs |
| **Oligoclonal Bands** | Marker for inflammation in the CNS, often found in MS patients |
| **EDSS** | *Expanded Disability Status Scale* — quantifies disability in MS on a scale of 0–10 |

---

## 📈 Project Goals

- Apply feature selection to find high-impact predictors of MS progression
- Use classification models (like Random Forest, Logistic Regression, etc.)
- Analyze model performance using metrics: **Accuracy**, **ROC AUC**, **Confusion Matrix**
- Identify clinical features that could guide **early diagnosis and intervention**

---

## 💡 Future Scope

- Integrate neuroimaging features for deeper analysis
- Use explainable AI (e.g., SHAP, LIME) to interpret model decisions
- Extend study to multi-center, diverse datasets

