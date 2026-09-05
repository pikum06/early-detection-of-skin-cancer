# Early detection of skin cancer through human-computer collaboration

## Abstract 

Skin cancer is a perilous disease due to which a lot of people suffer every year. The disease transpires on the skin of people and spreads all over the skin rapidly as shown in Figure 5.1. This occurs due to the peculiar growth of skin cells. Skin cancer is broadly classified into three distinct categories. These are basal cell cancer (BCC), squamous cell cancer (SCC), and melanoma. Melanoma is the most fatal of all the skin cancer types. It is difficult to detect melanoma from the naked eye.
Most people get affected by skin cancer due to being exposed to ultraviolet radiation. People who have lighter skin are more prone to suffer from this disease. Body parts like the torso, or upper extremities or lower extremities, etc. are severely affected by skin cancer. By the end of 2018, there were around 300,000 patients with skin cancer. Over 1 million people have been identified with BCC or SCC in 2018. If we talk about melanoma, the worldwide cases for melanoma alone were around 150,000 by the year 2020. People of Australia and New Zealand were found to be highly infectious as shown in figure 5.2 [1]. The melanoma rates of Australian and New Zealand males were significantly high compared to other countries as shown in Figure 5.3.
---

## Key Features

* **ResNet-50 Architecture**: Fine-tuned deep convolutional neural network for automated dermatological feature extraction.
* **7-Class Classification**: Classifies skin lesions into seven distinct diagnostic categories from the HAM10000 dataset.
* **Flask Web Interface**: Interactive web application environment for uploading skin lesion images and retrieving real-time diagnostic predictions.

---

## Dataset & Classification

The model is trained on the **HAM10000 ("Human Against Machine with 10000 training images")** benchmark dataset, covering the following 7 diagnostic classes:

1. **Actinic Keratoses / Intraepithelial Carcinoma (akiec)**
2. **Basal Cell Carcinoma (bcc)**
3. **Benign Keratosis-like Lesions (bkl)**
4. **Dermatofibroma (df)**
5. **Melanoma (mel)**
6. **Melanocytic Nevi (nv)**
7. **Vascular Lesions (vasc)**

---

## Repository Structure

```text
.
├── Flask_Framework.ipynb      # Web application deployment & API framework logic
├── Major project 2021.ipynb   # Primary end-to-end training, evaluation & metrics notebook
├── MP.ipynb                   # Model prototyping & pipeline experimentation
└── content/                   # Stored artifacts, assets, and sample data
