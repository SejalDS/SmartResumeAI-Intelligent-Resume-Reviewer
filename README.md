# SmartResumeAI: Intelligent Resume Reviewer using LLMs and Azure

## 📌 Project Overview

**SmartResumeAI** is an AI-powered resume analyzer that helps job seekers understand how well their resumes align with specific job descriptions. By leveraging advanced **Large Language Models (LLMs)**, **embeddings**, and **cosine similarity**, the system provides **personalized recommendations**, highlights **missing skills**, and improves resume formatting to increase the chances of landing interviews.

---

## 🎯 Project Goals

- Assess resume-job description similarity using semantic understanding
- Identify skill and formatting gaps in resumes
- Provide actionable improvement suggestions using GPT-4
- Enable users to upload resumes/JDs and receive insights in real time
- Deploy the system on **Azure** for accessibility and scalability

---

## 🧰 Tech Stack

- **Language**: Python 3.10  
- **Libraries**: Langchain, OpenAI, Streamlit, PyTesseract  
- **LLM Model**: OpenAI GPT-4, `text-embedding-3-large`  
- **Cloud Platform**: Microsoft Azure (App Services, Blob Storage)  
- **Interface**: Streamlit Web Application  

---

## 🚀 Features

- ✅ Resume and JD text parsing from PDFs or images
- ✅ Semantic embeddings via OpenAI
- ✅ Cosine similarity for scoring
- ✅ AI-based suggestions using GPT-4
- ✅ User-friendly Streamlit app with visual feedback
- ✅ Deployable on Azure App Services
- ✅ Feedback loop for model improvement

---

## 🧪 How It Works

1. **Upload** a resume and job description (PDF/Image).
2. **Parse** text using OCR or PDF readers.
3. **Embed** the texts using OpenAI's embedding models.
4. **Score** similarity using cosine similarity.
5. **Analyze Gaps** in skills, roles, keywords, and formatting.
6. **Get Suggestions** powered by GPT-4.
7. **Interact** via a Streamlit UI deployed on Azure.

---

## ✅ Prerequisites

- Python knowledge
- Familiarity with LLMs, embeddings, cosine similarity
- Azure and OpenAI API accounts

