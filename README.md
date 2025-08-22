# Edu-Recommendation

A machine learning–powered web application that recommends suitable educational and career paths for students based on their performance data and attributes.  
The system is built with **Flask** and uses a trained scikit-learn model for real-time predictions.

---

## 🚀 Features
- Interactive web interface to collect student details (scores, study hours, activities, etc.)
- Pre-trained ML model (`model.pkl`) to generate recommendations
- Scaler and Label Encoder for consistent input preprocessing
- Dynamic results page displaying personalized recommendations
- Lightweight backend with Flask and Jinja2 templates

---

## 🏗️ Project Structure
edu-recommendation/
│── app.py # Flask application entry point
│── model.pkl # Trained ML model
│── scaler.pkl # Feature scaler
│── label_encoder.pkl # Label encoder for outputs
│── requirements.txt # Python dependencies
│── Procfile # Deployment configuration (Heroku)
│── templates/ # HTML templates for UI
│── static/ # (optional) CSS/JS files
│── student-scores.csv # Sample dataset
│── Studies Recommendations.ipynb # Model training notebook


---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/edu-recommendation.git
cd edu-recommendation

2. Create Virtual Environment & Install Dependencies
python -m venv venv
source venv/bin/activate    # On macOS/Linux
venv\Scripts\activate       # On Windows

pip install -r requirements.txt

3. Run the Application
python app.py


The app will be available at http://127.0.0.1:5000/

📊 How It Works

User fills in details on the web form.

Flask backend processes inputs and applies scaling/encoding.

The ML model (model.pkl) predicts the most suitable path.

Result is displayed back on the results page.

🛠️ Tech Stack

Backend: Python, Flask

ML: scikit-learn, Pandas, NumPy

Frontend: HTML, CSS, Jinja2

Deployment: Procfile (Heroku/Gunicorn)

Version Control: Git, GitHub

📌 Future Improvements

Add user authentication for saving results

Support more datasets and recommendation categories

Build API endpoints for external integration

Deploy with Docker/Kubernetes for scalability

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to improve.

📄 License

This project is licensed under the MIT License.


---

Do you want me to also **add screenshots/demo GIF placeholders** in this README (like showing the form page and the results page), so it looks more polished on GitHub?
