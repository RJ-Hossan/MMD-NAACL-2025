# Misogyny Meme Detection - DravidianLangTech@NAACL 2025

This repository contains our implementation for the **Shared Task on Misogyny Meme Detection** organized as part of **DravidianLangTech@NAACL 2025**. This task focuses on detecting misogyny in memes using multimodal machine learning models, leveraging both textual and visual elements.

## Task Overview

The shared task challenges participants to classify memes as **Misogynistic** or **Non-misogynistic** in the **Tamil** and **Malayalam** languages. The datasets provided include both text (transcriptions) and image components, requiring participants to develop systems that analyze and integrate multimodal information effectively.

### Key Details:
- **Languages**: Tamil and Malayalam
- **Evaluation Metric**: Macro F1 Score
- **Dataset**: Social media memes containing textual transcriptions and images
- **Objective**: Build a system to classify memes into two categories:
  - **Misogynistic**
  - **Non-misogynistic**
 
For more details, visit [here](https://codalab.lisn.upsaclay.fr/competitions/20856).

## Repository Structure

```plaintext
├── data/
│   ├── train/                # Training data (images and CSV)
│   ├── valid/                # Development data (images and CSV)
│   ├── test/                 # Test data (images and CSV)
├── notebooks/
│   ├── Tamil Submission Notebook
│   ├── Malayalam Submission Notebook
├── requirements.txt          # Required Python libraries
├── README.md                 # Project documentation
```

## Methodology

This section will be updated very soon.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/RJ-Hossan/MMD-NAACL-2025
   cd MMD-NAACL-2025
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the datasets from [this link](https://codalab.lisn.upsaclay.fr/competitions/20856) and place them in the `data/` directory.


## Acknowledgments

We thank the organizers of [DravidianLangTech@NAACL 2025](https://sites.google.com/view/dravidianlangtech-2025/home) for providing the datasets and hosting this important shared task. We also acknowledge the support of the open-source community for tools like PyTorch, Hugging Face Transformers, and torchvision.

---
