
## Dataset Link:
[Dataset Link](https://drive.google.com/file/d/1jSjB55xdLlDPrbx_PjeBIp7jfPEcCRpY/view?usp=sharing)

## Project Website:
[MultiCoNER Official Website](https://multiconer.github.io/)

---

# Multilingual Complex Named Entity Recognition (NER)

## Project Overview
This project focuses on **multilingual complex named entity recognition** (NER). The primary objective was to design and evaluate an ensemble-based approach for recognizing and tagging named entities in multilingual text. This includes handling linguistically diverse inputs and addressing challenges related to context, ambiguity, and unseen entities.

### Key Features:
- **Multilingual Support**: Models trained on datasets spanning multiple languages.
- **Complex Entity Recognition**: Focuses on entities like titles, creative works, and ambiguous terms.
- **Ensemble Methodology**: Combines multiple RoBERTa-based models with a voting-based confidence mechanism to improve accuracy.

---

## Files and Structure

### 1. **final-project-2.ipynb**
   - Contains the **main implementation** of the NER task, including:
     - Data preprocessing
     - Model training (RoBERTa ensemble)
     - Evaluation metrics and performance visualizations

### 2. **baseline_model.ipynb**
   - Explores **baseline models** such as BERT, LUKE, and DistilBERT for multilingual NER tasks.
   - Includes initial experimentation and results, which informed the final ensemble approach.

### 3. **anonymyzed_18_report.pdf**
   - Detailed project **report**:
     - Introduction to multilingual NER challenges
     - Literature review of existing methodologies
     - Description of the ensemble approach
     - Experimental results and comparisons with baseline models
     - Conclusions and future work suggestions

---

## Methodology

### Approach:
1. **Baseline Experiments**:
   - Evaluated performance using standard models like BERT, DistilBERT, and LUKE on the MultiCoNER dataset.
2. **Proposed Ensemble**:
   - Multiple RoBERTa models trained on 11 language-specific datasets.
   - Voting mechanism based on confidence scoring to determine final entity tags.

### Dataset:
- Benchmarked on the **MultiCoNER** dataset, a multilingual dataset containing diverse and complex named entities.

### Results:
- The ensemble approach achieved competitive performance, outperforming simpler baselines in multilingual contexts.

---

## Usage

### Requirements:
- Python 3.x
- Jupyter Notebook
- Libraries: PyTorch, Transformers, NumPy, Pandas, scikit-learn, matplotlib

### Steps to Run:
1. Open `final-project-2.ipynb`.
2. Install the required dependencies.
3. Load the dataset (details in the notebook).
4. Train the models or directly load the pre-trained weights for evaluation.
5. Evaluate and visualize results using provided scripts.

---

## Key Insights
- Ensemble methods, despite being simpler, can offer competitive performance in multilingual NER tasks.
- Challenges like semantic ambiguity and unseen entities require innovative approaches combining contextual and linguistic insights.

---

## Future Work
- Extending the ensemble to include external knowledge bases for improved context understanding.
- Enhancing robustness to unseen and overlapping entities across languages.
- Fine-tuning voting mechanisms for better confidence calibration.

---
