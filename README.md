🌍 Travel Eazy – AI-Powered Travel Recommendation System

Travel Eazy is a smart travel planning platform built with Python, Flask, and Machine Learning.
It delivers personalized, health-aware, and preference-based recommendations for destinations, activities, and cuisines across India — helping users plan trips effortlessly.

Recruiters: This project demonstrates full-stack development, ML integration, database management, and UI design skills.

✨ Key Highlights

✅ ML-powered personalized travel recommendations
✅ Health-aware suggestions (mobility, allergies, dietary needs)
✅ Admin dashboard to manage destinations, cuisines & activities
✅ User-friendly interface with cart & booking system
✅ Built with Python, Flask, MySQL, Scikit-learn, TensorFlow, Keras
✅ Tested with Unit, Integration, Regression & Usability testing

🚀 Tech Stack

Frontend: HTML5, CSS3, Bootstrap, JavaScript

Backend: Python (Flask Framework)

Database: MySQL

Machine Learning: Scikit-learn, TensorFlow, Keras (Cosine Similarity, Random Forest, Gradient Boosting, KNN)

Tools & Libraries: Pandas, NumPy, Matplotlib, Seaborn, Joblib

⚙️ Setup & Installation

Clone the Repository

git clone https://github.com/your-username/travel-eazy.git
cd travel-eazy


Create Virtual Environment & Install Dependencies

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
pip install -r requirements.txt


Setup Database

Import travel_eazy.sql into MySQL

Update credentials in config.py

Run Application

python app.py


Access in Browser

http://127.0.0.1:5000/

📸 Screenshots
<img width="1856" height="669" alt="filtering" src="https://github.com/user-attachments/assets/ac09f5ba-033d-46c2-bbfb-603b1a09a82b" />

<img width="1873" height="644" alt="booking (2)" src="https://github.com/user-attachments/assets/d12aabed-ad9a-4728-a82c-482a37d608d4" />

	<img width="1907" height="97<img width="1873" height="978" alt="recomendation" src="https://github.com/user-attachments/assets/9d37323d-8104-4ae4-9a79-d2989ad6f5e9" />
7" alt="login" src="https://github.com/user-attachments/assets/53c3a84a-fba4-4a3a-a513-c6b19665a5dc" />

	Project Structure
 travel-eazy/
│
├── app.py                  # Main Flask application entry point
├── config.py               # Database configurations (MySQL credentials)
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation (this file)
│
├── static/                 # Static files (CSS, JS, Images)
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
│       └── logo.png
│
├── templates/              # HTML templates (Jinja2)
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── destination.html
│   ├── booking.html
│   ├── recommendations.html
│   └── admin_dashboard.html
│
├── ml_models/              # Machine Learning models & training scripts
│   ├── train_model.py
│   ├── recommender.pkl     # Saved trained ML model
│   └── preprocessing.py
│
├── database/               # Database-related files
│   └── travel_eazy.sql     # SQL dump for creating MySQL schema & tables
│
├── docs/                   # Documentation & project reports
│   ├── screenshots/        # Screenshots for README
│   │   ├── login.png
│   │   ├── destination.png
│   │   ├── booking.png
│   │   └── recommendations.png
│   └── system_flow.png     # Architecture/System flow diagram
│
└── tests/                  # Test cases
    ├── test_app.py
    ├── test_models.py
    └── test_routes.py

	
💡 Project Impact

🌍 Tourism Industry – Helps travelers find unique, safe, and health-friendly destinations.
🧑‍🤝‍🧑 Inclusivity – Supports senior citizens, families with kids, and people with medical conditions.
📈 Local Economy – Promotes lesser-known destinations, boosting local businesses.
♻️ Sustainability – Encourages responsible tourism by spreading visitor flow beyond overcrowded spots.
🎯 Recruiter Value – Demonstrates real-world problem-solving, AI integration, teamwork, and end-to-end deployment skills.

🧪 Testing

✔️ Unit Testing – Core modules validation
✔️ Integration Testing – User/Admin data flow
✔️ Regression Testing – No breakage after updates
✔️ Usability Testing – Smooth user experience

📌 Future Enhancements

🌐 Real-time data integration (weather, transport, events)

🏨 Hotel booking & itinerary planning

📱 Mobile app (Android & iOS)

🌎 International destinations expansion

🔒 Advanced security & privacy compliance

👨‍💻 Project Team

G Uma Mahesh – Database

C Mukunda – ML Model

J Narendra – UI/UX & Testing

M Madhu Harsha – Backend & API Integration

A Mokesh Reddy – Frontend & Deployment

Guide: Mrs. N. Nalini – Assistant Professor, Dept. of CSE, Mohan Babu University

📜 License

This project is developed as part of the Bachelor of Computer Applications (BCA) program at Mohan Babu University (2025).
Usage is intended for academic and demonstration purposes only.
