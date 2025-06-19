# 🩺 Health Track

A modern, easy-to-use Streamlit web app for **personal health monitoring** and **doctor-patient consultation**.  
Track your daily health, get AI-powered advice, and connect seamlessly with healthcare professionals!

---

## 🚀 Features

- **Patient Registration**: Easy sign-up with personal health details.
- **Doctor Registration**: Specialized onboarding for doctors.
- **Secure Login**: Role-based access (Patient/Doctor).
- **Personalized Dashboard**:
  - **BMI Calculation** & health status.
  - **Daily Target Recommendations** for steps, water, and sleep.
  - **Interactive Data Entry** for tracking health trends.
  - **Visual Trend Charts** (Steps, Water, Sleep).
- **AI Consultation Advice**:  
  Get tailored health advice based on your data and medical conditions.
- **Consultation Requests**:  
  Patients can request consultations, doctors can review and respond.
- **Prescription Management**:  
  Doctors can add notes/prescriptions, saved securely for each patient.

---

## 🖼️ Screenshots

| Patient Dashboard | Doctor Dashboard |
|-------------------|-----------------|
| ![Patient Dashboard](assets/patient_dashboard.png) | ![Doctor Dashboard](assets/doctor_dashboard.png) |

---

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/hardik0501/Project-code.git
   cd Project-code
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

   > **Dependencies include:**  
   > - `streamlit`  
   > - `pandas`  
   > - `matplotlib`

3. **Run the app**
   ```bash
   streamlit run health_track.py
   ```

---

## ✨ Usage

- **Patient:**  
  Register as a patient, log in, track your daily health data, and request consultations.
- **Doctor:**  
  Register as a doctor, log in, view patient requests, and provide AI-powered advice and prescriptions.

---

## 💡 How it Works

1. **Registration:**  
   Patients and doctors register with their details.
2. **Login:**  
   Secure login system with role detection.
3. **Patient Dashboard:**  
   - Input daily health data.
   - Visualize trends.
   - Request consultations.
4. **Doctor Dashboard:**  
   - View patient requests and data.
   - Get AI-generated advice.
   - Submit prescriptions and notes.

---

## 📁 Data Storage

- User data: `users.csv`
- Consultation requests: `consult_requests.json`
- Prescriptions: `/prescriptions/`
- Completed consultations: `completed_consultations.csv`

---

## 🤖 AI Advice

- Tailored for conditions like **diabetes**, **hypertension**, **asthma**.
- Personalized targets based on BMI.
- Recommendations for diet, exercise, and healthy habits.

---

## 💬 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.

---

## 📄 License

This project is open-source, licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Built with ❤️ using [Streamlit](https://streamlit.io/).
