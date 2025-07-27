# ATS Resume Ranker

Automatically rank candidate resumes against a job description using semantic similarity. This tool helps recruiters quickly surface the best matches by comparing embeddings of resume text and the job posting.

## 🚀 Features

- **Flexible embedding backends**:  
  - **OpenAI embeddings** (`text-embedding-ada-002`)  
  - **Universal Sentence Encoder** (TensorFlow Hub)  
- **Supports PDF & TXT resumes**  
- Caches embeddings locally for faster re-runs  
- Ranks and scores resumes by cosine similarity  
- Outputs human-readable percentage scores  

## ⚙️ Installation

1. **Clone this repository**  
   ```bash
   git clone https://github.com/yourusername/ats-resume-ranker.git
   cd ats-resume-ranker
