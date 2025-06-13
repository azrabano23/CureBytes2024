# 🧬 CureBytes – AI-Powered Feedback Tool for Medical Education  
**Group 2 – Rutgers Health Hack Fall 2024**  
🏆 *4th Place Winner – $1000 Prize*

---

## 👥 Team Members
- Abhinav Ramidi  
- Beomseok Park  
- Shariar Uddin  
- Preet Patel  
- Nikhil Shukla  
- Azra Bano  
- Wanzhao Yang  
- Naveen Gedupoori  
- Manav Vohra  
- Rishabh Dhingra  
- Sumedh Sinha  

---

## 💡 Overview

**CureBytes** is a cloud-based AI platform designed to support **medical schools and instructors** by providing instant, structured feedback on student-written clinical notes during **OSCEs (Objective Structured Clinical Examinations)**. The tool drastically reduces grading time, helping educators focus more on teaching and less on repetitive administrative tasks.

> 🔍 *OSCEs are crucial evaluations in medical training — but providing thorough feedback on student notes is time-consuming and inconsistent across institutions. CureBytes changes that.*

---

## ❗ Problem Statement

Medical educators face growing class sizes and increasing administrative burdens. OSCEs, though essential, require detailed feedback that often takes hours to generate manually.

> ⏳ *According to a 2023 AAMC report, faculty spend an average of 5–10 hours per week on assessment feedback.*  
>  
> 🧠 *AI-based automation could reduce this burden by over 60%, freeing educators to focus on clinical mentorship and curriculum development.*

---

## ✅ Key Features

- **LLM-Generated Feedback**  
  → Automatically evaluates and generates feedback on OSCE notes using 2 fine-tuned **Google Gemini AI** models.

- **Context Preservation via LinkedList Segmentation**  
  → Overcame token limit issues by implementing a **LinkedList-based breakdown** of long notes, preserving context across segmented inputs.

- **Teacher Interface**  
  → Clean web-based dashboard to upload notes and receive AI-driven evaluations in real time.

- **Student Experience**  
  → Enables medical students to receive consistent, constructive feedback they can actually learn from.

- **Cloud-Based Deployment**  
  → Fully hosted via **AWS Amplify** for accessibility, scalability, and real-time access.

---

## 🌐 Live Deployment

> **[Try CureBytes (Live Until Oct 27, 2024)](https://newr.dv3r7ksuvk0b0.amplifyapp.com/)**

---

## 🎥 Resources

- ▶️ **[Frontend Walkthrough](#)** *(YouTube)*  
- 🧠 **[Backend Walkthrough](#)** *(YouTube)*  
- 💻 **[GitHub Repository](https://github.com/sumedhsinha/health-hack-2024Oct)** *(Original Repo)*

---

## 🛠️ Tech Stack

| Component       | Tools Used                              |
|----------------|-------------------------------------------|
| Frontend        | HTML/CSS, JavaScript, React              |
| Backend         | Node.js                                  |
| AI Models       | Google Gemini AI (2 fine-tuned LLMs)     |
| NLP Solution    | LinkedList-based context management      |
| Deployment      | AWS Amplify                              |
| Routing         | React Router DOM                         |

### 📦 Installation Guide

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/curebytes.git
   cd curebytes
   ```

2. **Install dependencies**  
   ```bash
   npm install
   npm install @google/generative-ai
   npm install react-router-dom
   ```

3. **Run the app**  
   ```bash
   npm start
   ```

---

## 🧠 My Contributions *(Azra Bano)*

- **Full-Stack Development**: Worked across frontend and backend to implement GeminiAI API calls and UI features.  
- **Medical Research Integration**: Aligned AI outputs with real OSCE grading rubrics.  
- **Technical Innovation**: Helped design the LinkedList-based memory mechanism to handle large note sets across token boundaries.  
- **Demo & Presentation**: Participated in live judging session and walkthrough of CureBytes.

---

## 🚀 Impact & Next Steps

CureBytes is designed to be **adaptable for other health education use cases**, including:
- Radiology Report Analysis  
- Patient Interview Feedback  
- Real-Time SOAP Note Evaluation  

---

## 📄 License

This project was developed at Rutgers Health Hack 2024 and is open-source for educational purposes.

---

## 🙌 Acknowledgments

Thanks to:
- **Rutgers Health Hackathon Organizers**  
- **Google Cloud & Gemini AI** for LLM support  
- **AWS Amplify** for enabling live cloud deployment  
