# 🎓 AI Internship Selection Predictor using Find-S Algorithm

An interactive machine learning project that predicts internship eligibility using the **Find-S Concept Learning Algorithm**.

This system learns patterns from historical placement datasets and generates a hypothesis representing the ideal candidate profile for internship selection.

The project demonstrates how classical AI concept-learning algorithms can be applied to real-world student placement prediction scenarios.

---

# 🚀 Project Highlights

✔ Upload placement dataset (CSV supported)
✔ Automatic hypothesis generation
✔ Step-by-step Find-S learning process
✔ Internship eligibility prediction system
✔ Interactive web interface using Streamlit
✔ Beginner-friendly machine learning implementation
✔ Runs locally in browser

---

# 🧠 Algorithm Used

This project implements the **Find-S Algorithm**, a supervised learning technique used to determine the most specific hypothesis consistent with positive training examples.

Working principle:

1. Initialize most specific hypothesis
2. Select only positive training examples
3. Compare attribute values
4. Generalize mismatched attributes using '?'
5. Generate final hypothesis
6. Use hypothesis for prediction

---

# 📊 Example Hypothesis Output

Example generated hypothesis:

< High, ?, 2, Good, ? >

Meaning:

Students with high CGPA, at least 2 projects, and good communication skills are likely eligible for internship selection.

---

# 📂 Project Structure

FindS_Internship_Predictor/

dataset/

placement_data.csv

find_s.py

predictor.py

app.py

requirements.txt

README.md

---

# ⚙️ Technologies Used

Python

Pandas

Streamlit

Machine Learning Concept Learning Algorithm (Find-S)

---

# 📁 Dataset Format Required

CSV file must contain:

cgpa

projects_count

internships_count

coding_skill_score

communication_skill_score

placement_status

Target column:

placement_status

Allowed values:

Placed

Not Placed

---

# ▶️ How to Run the Project Locally

Step 1

Clone repository

git clone https://github.com/your-username/finds-internship-predictor-ai.git

Step 2

Open project folder

cd finds-internship-predictor-ai

Step 3

Install dependencies

pip install -r requirements.txt

Step 4

Run application

streamlit run app.py

Step 5

Open browser

http://localhost:8501

Upload dataset and start prediction.

---

# 🧪 Example Workflow

Upload dataset

Generate hypothesis

Enter new student details

Predict internship eligibility

---

# 📈 Applications

Student internship prediction

Placement eligibility screening

Concept learning demonstration

Educational AI projects

Machine learning beginner projects

---

# ⚠️ Limitations

Uses only positive training examples

Sensitive to noisy datasets

Works best with structured categorical data

---

# 🔮 Future Improvements

Add accuracy evaluation module

Compare with Candidate-Elimination Algorithm

Add visualization dashboard

Deploy online using Streamlit Cloud

Export hypothesis report as PDF

---

Developed as an academic AI mini-project demonstrating concept learning using Find-S Algorithm.
