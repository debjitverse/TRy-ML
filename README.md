
# 🏡 House Price Prediction Web App

A machine learning-powered web application that predicts house prices based on key features like quality, living area, garage capacity, and basement size. This project integrates **Python**, **Flask**, **HTML/CSS**, and **scikit-learn**, making it a perfect blend of **data science** and **web development**.

![Screenshot](./Screenshot%202025-04-06%20142723.png)

---

## 📌 Project Highlights

- 💡 **Trained ML Model**: Predicts house prices using a `RandomForestRegressor`.
- 🌐 **Frontend**: Responsive and modern UI built with **HTML5** and **CSS3**.
- ⚙️ **Backend**: Flask-based server processes input and displays predictions.
- 🧠 **Features Used**:
  - `OverallQual`: Overall material and finish quality
  - `GrLivArea`: Above-ground living area (sqft)
  - `GarageCars`: Number of cars that can fit in the garage
  - `TotalBsmtSF`: Total basement area (sqft)

---

## 📂 File Structure

```
.
├── app.py                  # Flask backend application
├── train_model.py          # Script to train and save the ML model
├── house_price_model.pkl   # Trained model saved using joblib
├── train.csv               # Dataset used for training
├── templates/
│   └── index.html          # UI template for the web interface
├── static/
│   └── 3DHome.png          # Icon/image used in the UI
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation (this file)
```

---

## 🚀 How to Run Locally

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/house-price-predictor.git
   cd house-price-predictor
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Train the model (Optional)**
   If you want to retrain the model:
   ```bash
   python train_model.py
   ```

5. **Run the Flask app**
   ```bash
   python app.py
   ```

6. **Open in browser**
   Visit `http://127.0.0.1:5000` in your web browser.

---

## 📊 Example Input

| Feature              | Value      |
|----------------------|------------|
| Overall Quality      | 7          |
| Living Area (sqft)   | 1800       |
| Garage Capacity      | 2          |
| Basement Area (sqft) | 900        |

---

## 🎓 What I Learned

- Building and training a machine learning regression model
- Preprocessing real-world datasets with missing values
- Saving/loading ML models with `joblib`
- Designing a clean and responsive frontend with HTML & CSS
- Integrating ML predictions into a web interface using Flask

---

## 📚 Tech Stack

| Category     | Technology          |
|--------------|---------------------|
| Language     | Python 3            |
| ML Framework | scikit-learn        |
| Web Framework | Flask              |
| Frontend     | HTML5, CSS3         |
| Deployment   | (Optional: Heroku, Render, etc.) |

---

## 📸 UI Preview

> Lightweight, gradient-themed UI with a clean layout and smooth user interaction.

![UI Screenshot](./Screenshot%202025-04-06%20142723.png)

---

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).
