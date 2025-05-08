# 🩺 Breast Cancer Prediction Model

A machine learning web application that predicts whether a tumor is **benign** or **malignant** based on diagnostic features. This hybrid project combines the power of **Flask**, **Streamlit**, and **HTML/CSS** for interactive and educational use.

## 📌 Features

- 🧠 Trained ML model using **Breast Cancer Wisconsin (Diagnostic) Dataset**
- 🧪 Dual interface:
  - **Streamlit** for rapid experimentation and user interaction
  - **Flask** + **HTML/CSS** for structured web interface
- 🎨 Clean UI with real-time predictions
- 🔍 Emphasis on early detection

## 📽️ Demo

![Demo Screenshot](![Screenshot 2025-05-08 194354](https://github.com/user-attachments/assets/9f0e7dd7-9667-465e-a25b-0372f251060b)
)

## 🚀 Live Preview

[Click here to try the app](https://your-deployed-app-link.com)

## 🛠️ Tech Stack

- Python 🐍
- Streamlit ⚡
- Flask 🌶️
- Scikit-learn 📚
- Pandas & NumPy 📈
- HTML/CSS & Bootstrap 🎨

## 📂 Project Structure

```
breast-cancer-prediction/
│
├── static/                  # CSS and images
├── templates/               # Flask HTML templates
├── model/                   # Trained ML model (Pickle file)
├── app.py                   # Flask application
├── streamlit_app.py         # Streamlit application
├── requirements.txt         # Dependencies
└── README.md                # This file
```

## 📈 How It Works

1. Users input diagnostic values.
2. Data is preprocessed and passed into a trained ML model.
3. The model predicts and returns either "Benign" or "Malignant".
4. UI displays result through Flask/HTML or Streamlit dashboard.

## 🧪 Dataset

Using the [Breast Cancer Wisconsin (Diagnostic) dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html) from `sklearn.datasets`.

## 🧰 Installation & Usage

```bash
# Clone the repo
git clone https://github.com/yourusername/breast-cancer-prediction.git
cd breast-cancer-prediction

# Install dependencies
pip install -r requirements.txt

# Run Flask app
python app.py

# OR run Streamlit app
streamlit run streamlit_app.py
```

## 📸 Screenshots

| Input Page (Flask) | Streamlit App |
|--------------------|----------------|
| ![](![Screenshot 2025-05-08 193705](https://github.com/user-attachments/assets/3149aac5-6ddf-4bcd-933a-43b33b5238cf)) | ![](![Screenshot 2025-05-08 194848](https://github.com/user-attachments/assets/9228cd52-444e-40ef-a5ec-759c641cf448)
) |

## 🤝 Contributing

Contributions and suggestions are welcome! Open issues or PRs freely.

## 🧑‍💻 Author

- **Kashish Rana** – [GitHub](https://github.com/bytequeen02)

---

> “Combining AI with simplicity to support early detection of breast cancer.”
