# House-Price_Prediction

# 🏡 Boston Housing Price Prediction

This is a machine learning web application built using **Flask** that predicts housing prices in Boston based on user inputs. It’s trained on the classic Boston Housing dataset and provides predictions via a simple, elegant web form.

![0d3d-34-138-188-151 ngrok-free app_predict](https://github.com/user-attachments/assets/de73ccbc-242d-4752-a4f6-3ae8dee9453d)

---

## 🚀 Features

- Predict house prices using 13 input features
- Clean HTML/CSS frontend with animated prediction results
- Runs interactively in **Google Colab** with **Ngrok**
- Model built using `scikit-learn` and deployed via Flask

---

## 🧠 Model Details

- Trained using a regression algorithm (e.g., Linear Regression or similar)
- Saved as a `.pkl` file using Python’s `pickle` module
- Input features include:
  - CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT

---

## 🗂️ Project Structure

├── house_price_prediction.pkl # Trained model ├── index1.html # HTML form ├── templates/ │ └── index1.html # Moved here automatically by the app ├── app.py # Flask application └── README.md # You’re reading this :)


---

## 💻 How to Run Locally (or in Colab)

### 🔸 In Google Colab

1. Upload the following files:
   - `app.py`
   - `house_price_prediction.pkl`
   - `index1.html`
2. Install dependencies:
   ```bash
   !pip install flask pyngrok
3. Set your Ngrok authtoken:
   from pyngrok import conf
conf.get_default().auth_token = "YOUR_NGROK_TOKEN"

4. Run the app:
  !python app.py

5. ✅ A public link (like https://xxxxxx.ngrok.io) will appear. Click it to use the app!

