# InSync-AI-Resume-Intelligence-System
This project is an AI-powered Resume Analysis and Career Intelligence System built using Python, NLP, Machine Learning, and LLM-based reasoning.

It analyzes resumes, matches them with relevant job roles, identifies skill gaps, and generates a strategic career improvement report using AI.

## Key Features

* Domain-aware resume classification (Finance, Marketing, Data Science, etc.)
* Hybrid skill extraction using NLP, regex, and taxonomy
* Top 3 job role matching using semantic similarity
* Skill gap and coverage analysis
* AI-generated strategic career report
* RAG-based knowledge retrieval for better insights
* Interactive Streamlit UI

## System Architecture
Resume Input → NER + Skill Extraction → Domain Resolver → Diagnostic Engine → Semantic Job Matching → RAG Knowledge Retrieval → AI Strategist → Strategic Career Report

## Dataset Information
The project uses a multi-domain resume dataset, job descriptions dataset, and a custom skill taxonomy.
Tools & Technologies Used

* Python, Streamlit
* spaCy (NER), Sentence Transformers (Embeddings)
* Scikit-learn, Pandas, NumPy
* LLM + RAG architecture
* YAML & CSV for configuration

## How to Run
1. Clone the repository
2. Install dependencies using pip install -r requirements.txt
3. Run the application using: streamlit run app.py
4. Upload a resume to get insights

## Note: This repo does not contain dataset and code files to access them follow the link below
👉 https://drive.google.com/drive/folders/1m-esVg19P9i9Ya4QSHuflhkfVWUMUMcm?usp=sharing

## Output Features
Top 3 matched roles with similarity, coverage, and missing skills.
Strategic report including analysis, weak areas, improvements, roadmap, and readiness score.

## Business Impact
Useful for resume screening, career guidance, EdTech platforms, and HR analytics.
Improves job matching and provides personalized career recommendations.

## Output Images

<img width="1883" height="829" alt="image" src="https://github.com/user-attachments/assets/e94bcb36-5a32-4843-bb41-4a7ed7f549cb" />

<img width="1909" height="842" alt="image" src="https://github.com/user-attachments/assets/50d6c434-4b79-414e-9505-b2753d3f16d1" />

<img width="1846" height="549" alt="image" src="https://github.com/user-attachments/assets/b68043ff-243b-433e-9975-01ea64e5e59f" />

<img width="1795" height="571" alt="image" src="https://github.com/user-attachments/assets/85917362-62b7-4320-a004-37021154e2dd" />

## Future Improvements

* Live job API integration
* ATS scoring system
•	Multilingual support

