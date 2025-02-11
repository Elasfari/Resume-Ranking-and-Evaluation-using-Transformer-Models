# Resume Ranking and Evaluation using Transformer Models

This project automates the process of ranking and evaluating resumes by leveraging state-of-the-art transformer models (BERT, RoBERTa, and ALBERT) to compute semantic similarities between resumes and job descriptions. The system provides recruiters with an efficient and accurate tool for candidate evaluation, including AI-generated insights and recommendations.

## Features
- **Resume Preprocessing:** Extracts key sections (e.g., skills, work experience, education) from resumes.
- **Transformer Models:** Utilizes BERT, RoBERTa, and ALBERT to generate embeddings and compute semantic similarities.
- **Weighted Similarity Score:** Combines similarity scores from multiple models for robust ranking.
- **LLM Refinement:** Uses a Large Language Model (LLM) to refine rankings and provide detailed evaluations.
- **Interactive GUI:** Built with Gradio for easy resume upload, similarity scoring, and evaluation.

## How It Works
1. **Resume Preprocessing:** Resumes are segmented into key sections (e.g., skills, experience) and cleaned for analysis.
2. **Embedding Generation:** Transformer models generate embeddings for both resumes and job descriptions.
3. **Similarity Computation:** Cosine similarity is calculated between embeddings, and a weighted score is used to rank resumes.
4. **LLM Refinement:** Top-ranked resumes are evaluated by an LLM, which provides detailed feedback and hiring recommendations.
5. **GUI Integration:** Recruiters can upload resumes, view similarity scores, and access AI-generated insights via an interactive interface.

## Usage
- Upload resumes (PDF, DOC, DOCX, or TXT) and provide a job description.
- View similarity scores for each transformer model and the combined weighted score.
- Access AI-generated evaluations, including strengths, weaknesses, and hiring recommendations.

## Dependencies
- Python 3.x
- Transformers library (Hugging Face)
- Gradio
- PyPDF2
- Pandas
- NumPy
- Together AI API (for LLM integration)

## Future Work
- Support for multilingual resumes.
- Fine-tuning transformer models for specific industries.
- Enhanced LLM capabilities for domain-specific analyses.
