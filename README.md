# Intellihire-NLP-Resume Screener
A robust Final Year Project implementing an AI-powered interactive chatbot and web application for automated resume screening, contextual matching against job descriptions (JD), and personalized candidate feedback using Natural Language Processing (NLP).
IntelliHire: An AI-Powered Resume Analysis and Contextual Feedback System
The IntelliHire project aims to revolutionize the initial stage of the Human Resources (HR) recruitment process by replacing manual, time-consuming resume screening with an efficient, intelligent, and unbiased automated system. This system will be deployed as a web-based interactive Chatbot and Analysis Console.
Core Problem Addressed
Current screening methods are often slow, prone to human fatigue, and rely heavily on keyword-based filtering, leading to high-potential candidates being overlooked and significant delays in the hiring cycle.
Solution and Key Modules
This system, built primarily with Python and Natural Language Processing (NLP), performs a seamless three-step analysis:
  Automated Resume Parsing: The system extracts structured data (skills, experience, education, contact info) from unstructured files (PDF, DOCX) using powerful NLP parsing techniques.
  Contextual Suitability Scoring: A Machine Learning (ML) model or advanced similarity metrics (e.g., Cosine Similarity) compares the extracted candidate profile against a specific Job Description (JD) and generates a numerical suitability score.
  Generative AI Feedback Loop (Innovation): This is the project's unique feature. The system provides candidates with detailed, constructive feedback and suggestions on how to improve their resumes for better alignment with the JD, moving beyond simple acceptance or rejection.
Technology Stack
| Backend & Core Logic | Python (Flask/Django) | Managing application routes, API endpoints, and business logic. |
| NLP & ML | SpaCy, NLTK, Scikit-learn | Text processing, entity recognition, and implementing the matching algorithm. |
| Data Storage | PostgreSQL / MongoDB | Storing job descriptions, candidate data, and historical screening results. |
| Frontend | HTML, CSS, JavaScript | Building the user interface, recruiter dashboard, and the interactive chatbot window. |
Expected Outcome
The final prototype will deliver a robust, functional tool that demonstrates proficiency in Web Application Development, Database Management, and advanced AI/NLP concepts, proving significant value by enhancing recruitment efficiency and candidate experience.
