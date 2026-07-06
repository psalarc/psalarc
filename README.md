# Pablo Salar Carrera — Data Scientist & ML Engineer

**M.S. Data Science** — New Jersey Institute of Technology (December 2024)
**B.A. Mathematics & Actuarial Science** — Rider University (May 2023)
📍 Short Hills, NJ | [LinkedIn](https://www.linkedin.com/in/pablo-salar-carrera) | psalarc@gmail.com

---

## About

I build production-ready machine learning systems end-to-end: data ingestion pipelines, model training and rigorous evaluation, and deployment via REST APIs. My work spans supervised classification, deep RL agents (DQN, Value Iteration), and generative AI systems (RAG pipelines with LLM integration and vector search). I bring unusual statistical rigor — grounded in actuarial science and probability theory — to model evaluation, uncertainty quantification, and experimental design.

**Published Research:** [Machine Learning Algorithms for Diabetes Diagnosis Prediction](https://dl.acm.org/doi/10.1145/3655755.3655781) — ACM Digital Library, IVSP 2024

---

## Technical Skills

**Languages:** Python, SQL, R

**ML & Deep Learning:** PyTorch, TensorFlow, Keras, scikit-learn — supervised/unsupervised learning, deep neural networks, LSTM, DQN, Value Iteration, Policy Iteration

**Generative AI & NLP:** Retrieval-Augmented Generation (RAG), LangChain, LLM API integration (OpenAI, Anthropic), Hugging Face Transformers, vector databases (FAISS, Chroma), semantic search, embeddings, prompt engineering, text classification

**Data & Analytics:** Pandas, NumPy, Matplotlib, Seaborn, Tableau, association rule mining (Apriori, FP-Growth), clustering (K-Means), dimensionality reduction

**MLOps & Deployment:** Docker, MLflow (experiment tracking), FastAPI, AWS (S3, EC2), Git/GitHub, Jupyter, VS Code

**Evaluation & Rigor:** Cross-validation, hyperparameter tuning, AUC-ROC, precision/recall, F1, SHAP interpretability, ablation studies, A/B testing

---

## Featured Projects

### [Clinical RAG QA System](https://github.com/psalarc/Medical-RAG-QA-System) *(Private — available on request)*

A full Retrieval-Augmented Generation pipeline that answers clinical medical questions grounded in a curated knowledge base. Built with Python, LangChain, LLM APIs, and FAISS vector search. Implements chunking strategy optimization, embedding selection, and retrieval quality evaluation.

### [DQN Agent for ConnectX](https://github.com/psalarc/DQN-ConnectX-Agent)

Deep Q-Network agent trained to play ConnectX via PyTorch. Experiments across 8 architectural configurations (1–4 hidden layers, 64–512 units), quantifying the compute/performance trade-off. Key finding: shallow architectures match deeper networks at ~40% training cost.
**Stack:** Python, PyTorch, Reinforcement Learning, DQN

### [Gambler's Problem — Dynamic Programming RL](https://github.com/psalarc/RL-Dynamic-Programming-GamblersProblem)

Implements Value Iteration and Policy Iteration (from Sutton & Barto) to solve the Gambler's Problem. Analyzes the effect of discount factor γ and coin-flip probability p_h on the optimal policy.
**Stack:** Python, NumPy, Dynamic Programming, MDP

### [Market Basket Analysis — Apriori & FP-Growth](https://github.com/psalarc/Market-Basket-Analysis-Apriori-FPGrowth)

Association rule mining on multi-retailer transaction data (Amazon, BestBuy, Nike, Supermarket). Surfaces high-confidence cross-sell rules; FP-Growth benchmarked against Apriori for runtime and rule quality at scale.
**Stack:** Python, mlxtend, scikit-learn, Pandas

### [Supervised ML Benchmark — Binary Classification](https://github.com/psalarc/Supervised-ML-Benchmark-Binary-Classification)

Benchmarks Random Forest, LSTM, KNN, and Naïve Bayes on a binary classification task under identical conditions. Compares models on accuracy, F1, and AUC-ROC with cross-validation and confusion matrix analysis.
**Stack:** Python, TensorFlow, scikit-learn, Pandas

### [ML-Based Diabetes Risk Prediction](https://github.com/psalarc/DiabetesPredictionProject)

Benchmarks six ML classifiers (Ridge, Random Forest, Decision Tree, KNN, SVC, Naïve Bayes) across two diabetes datasets. Best results: Ridge Classifier 83.12% accuracy (Pima, n=768); Random Forest & Decision Tree 95% accuracy (Diabetes 2019, n=952). Published at ACM IVSP 2024.
**Stack:** Python, scikit-learn, Pandas, NumPy, SHAP

---

*Actively seeking ML engineering and applied AI roles. I bring production-systems thinking, rigorous statistical grounding, and hands-on experience with deep learning, reinforcement learning, and RAG architectures.*
