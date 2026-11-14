# 👋 Hi, I’m Prithviraj Maurya

AI Engineer II @ Microsoft  
Ex–Amazon | Ex–Thomson Reuters | Ex–Morgan Stanley  
Senior Machine Learning Engineer | Generative AI & LLM Systems

I build production-grade AI/ML systems—from data and models to infrastructure and real-world impact. My work spans multi-modal LLMs, agentic workflows, large-scale MLOps, and applied ML systems serving millions of users.

---

## 🚀 What I Do
- Design and deploy end-to-end ML & LLM systems at scale
- Build multi-modal, agentic AI workflows for real business problems
- Optimize model performance, cost, and latency in production
- Lead MLOps pipelines for fast experimentation and reliable deployment

---

## 💼 Experience

### 🤖 AI Engineer II

Microsoft (Office AI) | Apr 2026 – Present  
Redmond, WA

- Build benchmarks for AI agents in professional workflows with domain experts, improving data quality, analyzing agent failures, and improving the agent.
- Created RL environments from benchmark data that grade an agent's tool use, trajectory, and final outputs.
- Developed an agent skill from scratch: collected eval data, refined grading rubrics with experts, and hill-climbed on the eval.
- Benchmarked open-weight small models (Kimi, Qwen, Gemma) and proprietary models as subagents and as replacements for intermediate workflow steps, comparing task performance against token usage.

---

### 🧠 Software Engineer – AI/ML

Amazon (Social Ads Team) | Aug 2024 – Apr 2026  
Seattle, WA

- Built a full-stack ML system from scratch to production to evaluate influencer-generated ad content quality using Amazon Bedrock and multi-modal LLMs, improving content review speed by 40%.
- Orchestrated an agentic workflow using the open-source Strands SDK, integrated with API Gateway and AWS Lambda, automatically scoring image, video, and metadata.
- Scaled the system to process 2M+ products daily with high reliability and low latency.
- Integrated TikTok Trends API to identify trending content and generate ads aligned with real-time trends, resulting in a 20% uplift in overall ad performance (OPS) versus standard catalog-based ads.

---

### ⚖️ Senior Machine Learning Engineer

Thomson Reuters | Sep 2023 – Aug 2024  
Remote

- Pioneered a state-of-the-art Legal Language Model (LLM) by curating and processing 10TB+ of legal data (LegalBench, proprietary corpora), outperforming LLaMA and Mistral by 15% on legal NLP benchmarks.
- Built a comprehensive AI platform for contract summarization, legal Q&A, and text generation, delivering context-aware legal insights.
- Led the end-to-end MLOps lifecycle—data ingestion, training, evaluation, deployment—reducing training time by 40% and enabling experimentation across 100+ model variants.
- Applied task classification, multi-task learning, and few-shot prompting, achieving GPT-4–level performance on domain-specific benchmarks while using 30% less compute on RTX 3090, V100, and H100 GPUs.

---

### 🧑‍💻 Senior Software Engineer

Morgan Stanley | Aug 2020 – Jul 2022  
Bengaluru, India

- Designed a responsive dashboard for asset managers to manage client profiles and export insights to PDF/PPT, driving a 50% business increase and $2M+ in revenue.
- Built a hybrid Ionic application to manage emails, calls, and meetings—onboarding 30,000+ users with ~70% daily active usage.
- Implemented Cypress-based test automation, reducing production bugs by 30%.
- Developed systems to track and analyze client interaction data stored in NoSQL databases.

---

## 🧪 Selected Projects

### 🦆 MicroDuck Challenges — RL Locomotion for a Bipedal Robot

Reinforcement Learning | PPO | MuJoCo | Hugging Face Jobs

- Train PPO policies that teach a small bipedal robot to walk and sprint in MuJoCo simulation (4,096 parallel environments), competing in the open Microduck Arena 2m sprint challenge.
- Ran single-variable reward experiments against a seed-matched control: a higher velocity-tracking reward cut sprint time by 23% (5.05s to 3.88s, 5/5 trials finished) in the local evaluator, repeated on a second training seed.
- Found via checkpoint sweeps that sprint time peaked at iteration 1,000 of 3,000 while training reward kept rising, so policies are selected by evaluation.
- Studying sim-to-real transfer to the physical robot.

🔗 Repo: https://github.com/prithviraj-maurya/microduck-challenges

### 🗣️ Voice Assistants — Converting the Point of View

Research | NLP | Transformers

- Built a hybrid rule-based + ML system to convert the point of view (POV) of voice assistant messages across multiple languages (Alexa, Siri, Google Assistant).
- Trained sequence-to-sequence transformer models (T5) achieving a BLEU score of 65.9.
- Awarded a State-of-the-Art (SOTA) badge on Papers With Code for best-reported results.
- Published research and open-sourced the work, demonstrating strong applied NLP and research rigor.

### 🍽️ Vision Transformer Replication & Food Vision Big (Deployed)

Computer Vision | Transformers | PyTorch | Hugging Face | Gradio

- Replicated the seminal paper “An Image is Worth 16×16 Words: Transformers for Image Recognition at Scale” from first principles to deeply understand the Vision Transformer (ViT) architecture.
- Implemented ViT end-to-end from scratch, including:
  - Image patching & flattening
  - Learnable patch and positional embeddings
  - Transformer encoder blocks with Multi-Head Self-Attention (MSA) and MLP layers
- Validated correctness by training on the Pizza–Steak–Sushi dataset, reproducing the paper’s core learning behavior.

### 🚀 Food Vision Big — Production-Ready Image Classifier
- Built and deployed Food Vision Big, a real-world food image classifier supporting 101 food categories using the Food101 dataset (101K images).
- Leveraged EfficientNetV2-S with transfer learning for high accuracy and efficient inference.
- Trained locally on NVIDIA RTX 4060, demonstrating large-scale CV training on consumer hardware.
- Developed an interactive Gradio UI and deployed the application on Hugging Face Spaces for public access.

🔗 Live Demo: https://huggingface.co/spaces/prithviraj-maurya/food-vision-big

📓 Key Notebooks:

- 08_pytorch_paper_replicating.ipynb — ViT paper replication
- 09_pytorch_model_deployment.ipynb — Model training & deployment

---

## 🎓 Education

Master of Science in Data Science  
Indiana University Bloomington | Aug 2022 – May 2024

---

## 🧰 Technical Skills

Languages: Python, Java, SQL, R  
ML / AI: PyTorch, TensorFlow, Scikit-learn, Hugging Face, LLMs, Generative AI, NLP/NLU  
Data & MLOps: Apache Spark, MLflow, Docker, CUDA, Airflow  
Cloud: AWS (S3, Lambda, Bedrock, API Gateway), Azure  
Data: NumPy, Pandas, Statistical Modeling, A/B Testing, Data Mining  
Other: Elasticsearch, Hadoop, Data Visualization, Regression, Clustering, Anomaly Detection

---

## 🏆 Achievements
- 🏅 AWS Certified Developer – Associate
- 🧪 Kaggle Expert
- 📚 PyTorch Docathon Contributor
- 📄 Published research on voice assistant NLP models
- 🚀 Built ML systems impacting millions of users in production

---

## 📫 Let’s Connect
- 🔗 LinkedIn: https://www.linkedin.com/in/prithviraj-maurya
- 📧 Email: pmaurya196@gmail.com
- 🧠 Kaggle: https://www.kaggle.com/prithviraj7387
- 🧑‍💻 GitHub: You’re already here 🙂

---

⭐️ I enjoy turning complex ML problems into scalable, elegant systems—always excited to build impactful AI.

---
