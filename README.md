🤖 AI Resume Builder with ATS Scoring (Java)

📌 Description

This project is an AI-assisted Resume Builder developed using Java that automates the process of creating professional resumes.

The system collects user details through a command-line interface, enhances the experience section using AI assistance, and generates a structured Resume.docx file. Additionally, it includes an ATS (Applicant Tracking System) scoring feature to evaluate the resume quality.

🚀 Features

* Collects user details (name, email, education, skills, experience)
* AI-assisted enhancement of experience section
* Generates professional Resume.docx automatically
* ATS scoring system for resume evaluation
* Structured resume formatting using Java

🧠 How It Works

1. User enters details via command line
2. System guides user to enhance experience using AI
3. Enhanced text is added back into the program
4. Resume object stores all data (OOP concept)
5. Apache POI generates a formatted Resume.docx
6. ATS system evaluates resume score

🛠️ Technologies Used

* Java
* Object-Oriented Programming (OOP)
* Apache POI (for DOCX generation)
* Command Line Interface
* AI Tool (for content enhancement)

▶️ How to Run

1. Compile all files:
   javac src/*.java

2. Run the program:
   java src.ResumeInput

📂 Project Structure

src/
├── ResumeInput.java        # User input handling
├── Resume.java             # Data model
├── ResumeDocGenerator.java # DOCX generation
├── ATS.java                # ATS scoring logic



⚠️ Note

This project requires Apache POI library for document generation.

## 🔮 Future Improvements

* Add GUI (Java Swing / JavaFX)
* Direct AI API integration (no manual copy-paste)
* Multiple resume templates
* PDF export option

