# LLMs for Academic Workflows: An Evaluation of Literature Reviews Generated with Short and Long Context Windows of LLMs

This repository contains the code, data, and results associated with the paper **"Evaluating Large Language Models with Long Context Windows in Academic Literature Reviews."** The study explores how context window size affects the quality, depth, and reliability of AI-generated literature reviews, highlighting key advantages and limitations.

## 📂 Repository Structure

- **`data/`** – Contains datasets used for evaluation, sourced from **Semantic Scholar** and **ArXiv**.
- **`code/`** – Includes Python scripts for **data preprocessing, model execution, and evaluation**.
- **`results/`** – Stores AI-generated literature reviews and performance analysis.
- **`figures/`** – Contains visualizations related to evaluation metrics and findings.
- **`README.md`** – This document.

## 🚀 Getting Started

### Prerequisites

Ensure you have **Python 3.x** installed, along with the following dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib transformers
```

### Running the Model

1. Clone the repository:
   ```bash
   git clone https://github.com/VeraciousAI/Long_Context_Paper.git
   cd Long_Context_Paper
   ```

2. Preprocess the dataset:
   ```bash
   python preprocess.py
   ```

3. Run the model with different context window settings:
   ```bash
   python run_model.py --context_size long
   python run_model.py --context_size short
   ```

4. Evaluate the results:
   ```bash
   python evaluate.py
   ```

## 📊 Evaluation Metrics

The AI-generated literature reviews were assessed across **15 dimensions**, including:
- **Organization & Structure**
- **Critical Analysis & Synthesis**
- **Citation Quality & Relevance**
- **Grammar & Readability**
- **Accuracy & Comprehensiveness**

## 🔍 Key Findings

- **Long context window models** incorporate broader information but tend to **repeat content** and lack analytical synthesis.
- **Short context models** avoid redundancy but may **miss key references** and lack comprehensiveness.
- **Human oversight** is essential for refining AI-generated literature reviews to meet academic standards.

## 📖 Citation

If you use this repository in your research, please cite:

```bibtex
@article{Author2025,
  title={Evaluating Large Language Models with Long Context Windows in Academic Literature Reviews},
  author={Author, A. and Author, B.},
  journal={Journal of AI Research},
  year={2025},
  volume={10},
  pages={123-456}
}
```

## ⚖️ License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

💡 **Contributions and feedback are welcome!** Feel free to open an issue or submit a pull request.
