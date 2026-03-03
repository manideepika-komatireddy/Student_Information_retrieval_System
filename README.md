🤖 Student_Information_retrieval_System

📌 Project Overview
Student information retrieval System [AI-Powered] is a Python-based desktop application that integrates:
•	Data management using Excel
•	Graphical User Interface (GUI) with Tkinter
•	Data analysis using Pandas
•	AI-based question answering using Ollama (LLaMA 3)
The system not only manages student records but also enables intelligent natural language queries over structured academic data.
This project demonstrates the integration of traditional data systems with modern AI technologies.

🎯 Project Objectives
•	To design a student data management system
•	To perform attendance and academic performance analysis
•	To identify at-risk students using predefined thresholds
•	To integrate Large Language Models (LLMs) for intelligent querying
•	To demonstrate applied AI in structured datasets

🏗️ System Architecture
The system consists of three major layers:
1️⃣ Data Layer
•	Excel file (excel-data.xlsx)
•	Sheets:
o	Student_Info
o	Attendance
o	Academic_Marks
2️⃣ Application Layer
•	Python
•	Pandas for data processing
•	Tkinter for GUI
•	OpenPyXL for Excel writing
3️⃣ AI Layer
•	Ollama integration
•	LLaMA3 model
•	Prompt engineering for structured data interpretation

📂 Project Structure
AI_Student_Management_System/
│
├── main.py
├── excel-data.xlsx
├── Final_Student_Report.xlsx
├── At_Risk_Students.xlsx
└── README.md

⚙️ Core Features
1️⃣ Attendance Management
•	Record attendance (Present/Absent)
•	Store attendance date
•	Update Excel dynamically
•	Maintain structured student records

2️⃣ Emergency Contact Retrieval
•	Fetch father’s phone number using Roll Number
•	Quick access for emergency situations

3️⃣ Academic Marks Viewer
•	View subject-wise marks:
o	Maths
o	Physics
o	Chemistry
o	Computer Science
•	Display overall percentage

4️⃣ At-Risk Student Detection
The system identifies students at risk based on:
Condition	Threshold
Attendance	< 75%
Percentage	< 60%
Students meeting both conditions are classified as At Risk.
Generated files:
•	Final_Student_Report.xlsx
•	At_Risk_Students.xlsx

5️⃣ 🤖 AI-Powered Query System
The system integrates Ollama (LLaMA3) to enable natural language interaction.
Users can ask questions like:
•	"Which students have low attendance?"
•	"Who scored below 60%?"
•	"List at-risk students."
•	"Show academic performance summary."
The AI reads structured Excel data, converts it into text context, and generates intelligent responses in simple English.

🧠 AI Integration Logic
1.	Load Excel sheets using Pandas
2.	Convert structured data into text format
3.	Inject data into a structured prompt
4.	Send prompt to Ollama LLaMA3 model
5.	Display generated response in GUI
This demonstrates practical LLM + structured data integration.
________________________________________
💻 Technologies Used
•	Python
•	Pandas
•	Tkinter
•	OpenPyXL
•	Ollama
•	LLaMA 3
•	Excel

▶️ How to Run the Project
Step 1: Install Required Libraries
pip install pandas openpyxl ollama

Step 2: Install Ollama
Download from:
https://ollama.com
Pull LLaMA 3 model:
ollama pull llama3

Step 3: Run the Application
python main.py

📊 Learning Outcomes
This project helped in understanding:
•	Data preprocessing and cleaning
•	GUI application development
•	Excel-based data management
•	Risk analysis logic implementation
•	Prompt engineering
•	Integration of Large Language Models
•	AI-enhanced decision support systems

🚀 Future Enhancements
•	Convert desktop app to Flask web application
•	Replace rule-based risk detection with Machine Learning
•	Deploy as cloud-based student analytics system
•	Add authentication system
•	Add real-time dashboard visualization

🎓 Academic Relevance
This project demonstrates:
•	Applied Artificial Intelligence
•	Educational data analytics
•	System design principles
•	Human-computer interaction
•	Integration of AI with traditional databases
Suitable for:
•	Mini Project
•	Internship Evaluation
•	Academic Demonstration
•	AI-based System Prototype

📄 License
Developed for academic and learning purposes only.



