# 👋 Corey Jones — Developer & Machine Learning Engineer

Hi! I’m Corey, a Python developer and ML engineer with a foundation in education, automation, and research-based AI systems. I work across disciplines to build reliable tools and intelligent workflows for solving real-world problems.

My projects span:

- **Applied machine learning** in NLP, classification, and reinforcement learning  
- **Automation and data pipelines** using modern scraping and API tools  
- **Interactive applications** for education, research, and end-user analysis  
- **Research replications** of academic ML papers with scalable results

---

## 🔍 Featured Projects

### 🎮 [PokeBot – Reinforcement Learning for Pokémon Red](https://github.com/CoreyJness/pokebot)  
A faithful implementation of [“Pokémon Red via Reinforcement Learning” (arXiv:2502.19920)](https://arxiv.org/abs/2502.19920), training an agent to reach Cerulean City using PPO + LSTM in a long-horizon, multi-reward setting.

**Highlights**:
- 50M+ steps of training with hybrid observations (RAM + visual)  
- Multi-component reward shaping + animation fixation detection  
- Academic PPO configuration with milestone-based tracking (Mt. Moon, Pewter Gym, etc.)  
- Full training logs via TensorBoard and modular config system  

🧪 Reproduces research-level performance in a high-complexity gaming environment.

---

### 🧠 [Studybot – Question Difficulty Classifier](https://github.com/CoreyJness/studybot_da_capstone)  
A fine-tuned BERT model with a custom **dual attention mechanism** (DualBert) to classify educational questions by **grade level (3rd–12th)**.

**Highlights**:
- Inspired by Song et al.'s attention modeling architecture  
- Trained on [QxGrade Dataset](https://www.kaggle.com/datasets/coreyjjness94/qxgrade-dataset)  
- ~70% accuracy on held-out educational questions  
- Deployable via Streamlit for real-time inference  
- Built with PyTorch, Hugging Face, and Google Colab for training  

📘 Future development includes Bloom's Taxonomy tagging and deeper complexity modeling.

---

### 📊 [GrantFundingDataPipeline – State Education Grant Analysis](https://github.com/CoreyJness/GrantFundingDataPipeline)  
An end-to-end ETL pipeline for scraping and analyzing **state-level education funding** from Excel spreadsheets published across U.S. education departments.

**Highlights**:
- Scrapes files using Playwright and automates uploads to Google Drive  
- Consolidates multi-tab spreadsheets with Google Apps Script  
- Outputs clean pivot tables by state in Google Sheets  
- Asynchronous I/O with secure Google OAuth2 integration  
- Designed for transparency, maintainability, and rapid use by analysts  

📈 Enables policy-facing insights into state-level education grant distributions.

---

## 📁 Notable Dataset

### 🏷️ [QxGrade Dataset (Kaggle)](https://www.kaggle.com/datasets/coreyjjness94/qxgrade-dataset)  
A curated dataset of Common Core-aligned educational questions labeled by grade level (3–12), designed to support text classification and ed-tech research.

- Labeled by pedagogical level
- Suitable for training and evaluation of NLP models
- Used in the `Studybot` project above

---

## 🧰 Tech & Tools

**Languages**: Python, SQL  
**ML & NLP**: PyTorch, Hugging Face Transformers, scikit-learn  
**Data**: pandas, NumPy, openpyxl, Google Sheets API  
**Automation**: Playwright, Selenium, Google Drive API, Google Apps Script  
**Apps & UI**: Streamlit, Jupyter, Google Colab  
**Monitoring & Ops**: TensorBoard, GitHub Actions

---

## 🗂️ Project Summary

| Project                  | Description                                      | Key Tools                               |
|--------------------------|--------------------------------------------------|------------------------------------------|
| **PokeBot**              | RL agent for Pokémon Red game                   | PPO, LSTM, Gym, TensorBoard              |
| **Studybot**             | Classifier for grade-level question difficulty  | BERT, Dual Attention, Streamlit, Colab   |
| **GrantFundingPipeline** | ETL pipeline for state education grants         | Playwright, Google APIs, Excel, Colab    |
| **QxGrade Dataset**      | Grade-labeled question dataset (3–12)           | Kaggle, CSV, CCSS-aligned annotation     |

---

## 📬 Contact

- 📧 **Email**: coreyjness@gmail.com  
- 🔗 [GitHub](https://github.com/CoreyJness)  
- 🔗 [LinkedIn](https://www.linkedin.com/in/coreyjness)

---

### 📄 License & Usage
All repositories follow open-source or fair-use licensing. Please cite original sources where applicable, especially for research-based implementations such as PokeBot.

