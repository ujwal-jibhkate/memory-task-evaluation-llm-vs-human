# Memory Task Evaluation: LLM vs. Human

This project explores the performance of Large Language Models (LLMs) in comparison to humans on five cognitive memory tasks. By evaluating Free Recall, Lexical Decision, Cued Recall, Single Recognition, and Associative Recognition, we aim to understand the strengths and weaknesses of LLMs in memory-related tasks.

---

## 📖 Overview

Memory tasks are widely used in cognitive science to measure human memory performance. This project adapts these tasks to LLMs to evaluate their capabilities and compare them to human responses. By leveraging prompt engineering and study-test pipelines, the project benchmarks LLMs using real-world experimental data.

---

## 🛠️ Tools and Frameworks

- **Python**: Programming language for data processing, prompt generation, and evaluation.
- **HuggingFace Transformers**: Library for LLMs.
- **PyTorch**: Backend for LLM execution and fine-tuning.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Data visualization for results.
- **Git**: Version control.

---

## 📂 Dataset

The dataset used for this project can be downloaded from the following link: [OSF Dataset - Memory Tasks](https://osf.io/dd8kp/).

You only need to download the file named **`all_data.csv`**, which contains the necessary data for all five memory tasks.

---
## 🔬 Memory Tasks

### 1. **Free Recall**
Participants and LLMs recall words from a list without cues. Performance was evaluated using accuracy and precision.

### 2. **Lexical Decision**
Determine if a given string is a valid English word. Metrics included binary accuracy.

### 3. **Cued Recall**
Recall a word associated with a cue after studying cue-response pairs. Evaluated for exact matches.

### 4. **Single Recognition**
Identify whether a word was previously studied or is new. Compared model vs. human binary responses.

### 5. **Associative Recognition**
Determine whether a pair of words was studied together. Metrics included pair-level accuracy.

---

## 📊 Results and Insights

- **Metrics**: Accuracy, precision, recall, and F1-score were calculated for each task.
- **Visualization**: Plots comparing human vs. LLM performance across tasks highlight LLMs' pattern recognition abilities and limitations in associative memory.
- **Findings**: LLMs perform well in structured tasks (e.g., lexical decision) but struggle with nuanced associative tasks.

---

