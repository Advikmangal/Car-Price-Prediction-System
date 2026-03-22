#  Car Price Prediction System

A machine learning web application that predicts the selling price of a car based on user inputs such as company, model, year, fuel type, and kilometers driven.

🔗 **Live Demo:** https://car-price-prediction-system-7vdv.onrender.com/

---

## 📌 Features

* 🔍 Predict car prices in real-time
* 📊 Machine Learning model using Scikit-learn
* 🌐 Flask-based backend API
* ⚡ Fast and interactive frontend using HTML, CSS, JavaScript
* 🔗 Deployed on Render

---

## 🛠️ Tech Stack

### 👨‍💻 Backend

* Python
* Flask
* Flask-CORS
* Scikit-learn

### 🎨 Frontend

* HTML
* CSS (Bootstrap)
* JavaScript (Fetch API)

### ☁️ Deployment

* Render

---

## ⚙️ How It Works

1. User enters car details:

   * Company
   * Model
   * Year
   * Fuel Type
   * Kilometers Driven

2. Data is sent to Flask backend via API

3. Backend processes input and feeds it to the trained ML model

4. Model predicts the price

5. Result is displayed instantly on the UI

---

## 📂 Project Structure

```
Car-Price-Prediction/
│
├── app.py
├── LinearRegressionModel.pkl
├── Cleaned Car.csv
│
├── templates/
│   └── index.html
│
├── static/
│   └── css/
│       └── style.css
│
├── requirements.txt
└── Procfile
```

---

## 🚀 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Car-Price-Prediction.git
cd Car-Price-Prediction
```

### 2. Create virtual environment

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the app

```bash
python app.py
```

Open in browser:

```
http://127.0.0.1:5000
```

---

## 📈 Future Improvements

* 📊 Add model performance metrics (R² score, accuracy)
* 📉 Show price range instead of single value
* 🎨 Improve UI with modern design
* ⚛️ Convert frontend to React

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Advik Mangal**

* GitHub: https://github.com/Advikmangal
* LinkedIn: https://www.linkedin.com/in/advik-mangal-7b9752321/

---

⭐ If you like this project, consider giving it a star!
