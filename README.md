# Speak Ease  

A **real-time web application** designed to deliver **accurate speech recognition**, specifically tailored for individuals with **dysarthria (speech impairment)**.  

---

## **Problem Statement**  
Dysarthria **traps thoughts** within a body that struggles to articulate them, **isolating individuals** and making communication a constant challenge. This not only **affects relationships** but also diminishes **confidence and independence**.  

- Dysarthria significantly **impacts communication**, reducing the quality of life and autonomy.  
- It affects **millions worldwide**, including:
  - **41-53% of stroke survivors**
  - **44-88% of individuals with Parkinson’s disease**
  - People with other **neurological disorders**  
- The **aging population** and the rise in **neurological conditions** are making this a growing concern.  

This solution has the potential to **greatly enhance communication** and **quality of life** for an underserved population, positioning it as a **breakthrough healthcare innovation**.  

---

## **High-Level Solution Overview**  
We will develop a **state-of-the-art, end-to-end speech recognition model** with high accuracy. Initially, the model will be **trained on extensive datasets of standard speech**, ensuring high **Automatic Speech Recognition (ASR) accuracy**.  

Once a strong base model is established, we will proceed with **fine-tuning specific components** to cater to individuals with **speech impairments**.  

### **Our Approach:**
- Train a **base model** on a **large dataset** of normal speech.
- Use **transfer learning** to fine-tune the model on a **smaller dataset** of slurred or impaired speech.
- Personalize the model by adapting it to **individual speakers** with speech impairments.

---

## **Model Architecture**  
![Model Architecture](https://user-images.githubusercontent.com/42781233/135641230-4775970a-479f-4d40-9707-6c50c9b0bb5b.png)  

---

## **Base Model Performance**  
The **base ASR model** was trained on **100 hours** of the **Librispeech Dataset**, achieving:  
- **Final Epoch Average Loss:** **0.46**  
- **Final Epoch Average Character Error Rate (CER):** **0.10**  
- **Final Epoch Average Word Error Rate (WER):** **0.11**  

---

## **Dataset Preparation**  
Once the ASR model is successfully trained on **hundreds of hours of typical speech**, we will proceed with **fine-tuning it for impaired speech recognition**.  

To achieve this, we need to **collect a dataset of impaired speech samples**. For this purpose, we are developing a **web application using the Django framework** to facilitate **data collection and user interaction**.

