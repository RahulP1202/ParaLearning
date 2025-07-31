# PARA – The Supreme Evolution App

**PARA** is a holistic transformation platform designed to help individuals grow physically, mentally, emotionally, and spiritually. It provides structured challenges, intelligent AI coaching, and community features to guide users through their personal evolution journey.

## Features

- **41-Day Challenge:**  
  Users embark on a 41-day journey, choosing personal goals such as improving mental clarity, building discipline, or increasing physical fitness. Each day presents a unique routine, and users can track their progress visually with a calendar view.

- **Health Tracking & AI Insights:**  
  Users input physical and mental health data, which is analyzed by an integrated Med-BERT AI model. The app provides a health score, condition assessment, and personalized challenge recommendations.

- **Motivational & Gamified Experience:**  
  - Daily motivational quotes and tips.
  - Streak-based badges (Bronze, Silver, Gold) for consistent progress.
  - Progress analytics and visual feedback.
  - Accountability partnerships with friends.

- **User Management:**  
  - Registration and login with local storage.
  - User profile management (age, gender, profession, marital status).
  - Secure session handling.

- **Health Comparison:**  
  At the end of the challenge, users can compare their initial and final health data, receiving feedback and encouragement based on their improvement.

- **Modern UI:**  
  - Responsive design with engaging animations.
  - Clean, accessible interface for all user types.

## Technology Stack

- **Frontend:**  
  - HTML, CSS, JavaScript  
  - Responsive and animated UI  
  - Local storage for user data and progress

- **Backend:**  
  - Python Flask API (`app.py`)
  - AI/ML integration with Med-BERT (`medbert_model.py`)

- **AI/ML:**  
  - Med-BERT model for health data analysis and personalized recommendations

## File Structure

- `app.py` – Flask backend serving AI predictions.
- `medbert_model.py` – Loads and runs the Med-BERT model for health analysis.
- `index.html` – Landing page.
- `login.html`, `register.html`, `login.js`, `register.js` – User authentication and onboarding.
- `user-details.html` – User profile management.
- `para_web_page.html` – Main challenge dashboard with calendar, routines, badges, and progress bar.
- `health.html`, `physical-health.html`, `mental-health.html` – Health data entry and tracking.
- `health-summary-comapre.html.html` – Health progress comparison and feedback.
- `style.css`, `auth-style.css` – Main and authentication-related styles.
- `script.js` – Navigation logic.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- PyTorch
- Transformers (HuggingFace)
- A pre-trained Med-BERT model file at `model_files/medbert_model.pt`

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/PARA-The-Supreme-Evalution-App.git
   cd PARA-The-Supreme-Evalution-App
   ```

2. **Install Python dependencies:**
   ```bash
   pip install flask torch transformers
   ```

3. **Download or place the Med-BERT model:**
   - Place the model file at `model_files/medbert_model.pt`.

4. **Run the backend:**
   ```bash
   python app.py
   ```

5. **Open `index.html` in your browser to start using the app.**

## Usage

- Register a new account or log in.
- Complete your user profile.
- Start the 41-Day Challenge and track your daily routines.
- Enter your health data and receive AI-powered insights.
- Compare your progress at the end of the challenge.

## Screenshots

*(Add screenshots of the landing page, challenge dashboard, health entry, and progress comparison here.)*

## Contributing

Contributions are welcome! Please open issues or submit pull requests for new features, bug fixes, or improvements.

## License

This project is licensed under the MIT License.


