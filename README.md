# Transformer-Based Question Answering System

## Overview

This project focuses on building and evaluating Transformer-based models for an Extractive Question Answering (QA) task. The objective is to develop models capable of understanding a given context and identifying the most relevant answer span in response to a question.

The project explores different modeling approaches, compares their performance, and evaluates their effectiveness using appropriate QA evaluation metrics.

## Repository Contents

```text
Question-Answering-Transformers/
│
├── QA_Transformer_Models.ipynb
├── Project_Report.pdf
└── README.md
```

| File | Description |
|---|---|
| `QA_Transformer_Models.ipynb` | Complete implementation, data preprocessing, model training, and evaluation experiments. |
| `Project_Report.pdf` | Final project report describing the problem, dataset, proposed approaches, architectures, experimental setup, results, and conclusions. |
| `README.md` | Project documentation. |

## Project Objectives

- Explore Transformer-based architectures for Question Answering.
- Preprocess and prepare the dataset for model training and evaluation.
- Implement different approaches to extractive Question Answering.
- Train and evaluate the proposed models.
- Compare experimental results and analyze model performance.

## Methodology

The project follows these main stages:

1. **Dataset Preparation:** Loading, inspecting, and preprocessing the Question Answering dataset.
2. **Data Processing:** Preparing context-question pairs and corresponding answer spans.
3. **Model Implementation:** Implementing and experimenting with Transformer-based architectures.
4. **Training:** Training the models using the selected experimental configurations.
5. **Evaluation:** Assessing model performance using Question Answering evaluation metrics.
6. **Comparison:** Comparing the experimental results and drawing conclusions.

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Jupyter Notebook / Google Colab
- NumPy
- Pandas

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

### 2. Navigate to the Project Directory

```bash
cd YOUR_REPOSITORY
```

### 3. Install Dependencies

```bash
pip install torch transformers datasets numpy pandas scikit-learn
```

Additional dependencies may be required depending on the notebook environment.

### 4. Run the Notebook

Open `QA_Transformer_Models.ipynb` using Jupyter Notebook or Google Colab and execute the cells sequentially.

**Note:** Training the models from scratch may require substantial computational resources. Google Colab with GPU acceleration is recommended.

## Results and Discussion

The experimental results, model comparisons, evaluation metrics, and performance analysis are documented in the Jupyter Notebook and the accompanying project report.

Refer to `Project_Report.pdf` for a concise summary of the complete project and its findings.

## Documentation

The complete implementation and experimental workflow are available in the notebook.

The final project report is available as `Project_Report.pdf` in this repository.

## Author

**Muhammad Taha Raees**

---

*This project was developed as part of an academic assignment on Transformer-based Question Answering systems.*
