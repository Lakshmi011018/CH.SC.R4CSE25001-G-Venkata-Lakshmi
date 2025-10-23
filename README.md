# Cross-Modal Gated Attention (CMGA) Framework for Multimodal Clinical Risk Stratification Using Synthetic Electronic Health Records

**Student Name:** G V Lakshmi  
**Roll Number:** CH.SC.R4CSE25001 
**Department:** CSE, Amrita Vishwa Vidyapeetam, Chennai  

---

## Project Overview

This project implements a multimodal deep learning framework to predict patient health risk levels using **structured vital signs** and **unstructured clinical notes**. The primary goal is to classify patients into **Low, Medium, or High risk** categories, enhancing clinical decision support with interpretable AI models.

The project evaluates and compares four models:  
1. **Baseline Concat (Early Fusion)**  
2. **Late Fusion**  
3. **Simple Cross-Attention**  
4. **CMGA (Cross-Modal Gated Attention – Proposed Model)**  

CMGA introduces **bidirectional gated attention**, improving robustness to noisy or incomplete inputs while providing clinically interpretable predictions.  

---

## Dataset

- **Type:** Synthetic yet clinically relevant Electronic Health Records (EHRs)  
- **Records:** 20,000 patient records  
- **Features:**  
  - **Vitals:** Temperature, SpO₂, Heart Rate, Respiration Rate, Systolic & Diastolic Blood Pressure  
  - **Clinical Notes:** Physician narratives including symptoms, diagnosis, and observations  
- **Splits:**  
  - Training: 70% (14,000)  
  - Validation: 15% (3,000)  
  - Test: 15% (3,000)  


---

## Dependencies

- Python >= 3.8  
- PyTorch >= 2.1  
- Hugging Face Transformers >= 4.35  
- NumPy, pandas, scikit-learn, matplotlib, seaborn  

Install all dependencies using:

```bash
pip install -r requirements.txt


## Project Structure

