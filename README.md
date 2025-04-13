# 🏡 **House Price Predictor** - Flask Web Application

> A simple **Flask** web application that predicts house prices using a **Linear Regression** model based on features like area, number of bedrooms, bathrooms, parking, and more.

---

## 📸 **Preview**


---

## 🧑‍💻 **Tech Stack**

- **Backend**: Python 3, Flask
- **Machine Learning**: Scikit-Learn (Linear Regression Model)
- **Data Manipulation**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn (Optional for data insights)
- **Frontend**: HTML, CSS (Responsive templates)

---

## 📝 **Features**

- Predict house prices based on user input features like area, number of bedrooms, etc.
- **Interactive Flask Web Interface**: Easy-to-use UI for users to input data and get predictions.
- **Linear Regression Model**: Built using Scikit-Learn to predict prices.
- **Visualization**: Graphical representations of trends (optional).

---

## 💡 **Sample Input and Output**

### **Sample Input:**

| **Feature**  | **Value** |
|--------------|-----------|
| Area         | 3000 sq.ft |
| Bedrooms     | 3         |
| Bathrooms    | 2         |
| Stories      | 2         |
| Parking      | 1         |

### **Sample Output:**

**Predicted House Price**: ₹5,131,666.58

---

## 🔥 **Project Structure**

house-price-predictor/ ├── app.py # Main Flask application file ├── model.pkl # Trained Linear Regression Model ├── templates/ │ └── index.html # Frontend HTML template ├── static/ # (Optional) CSS/JS files for the frontend ├── requirements.txt # Python dependencies ├── README.md # Project documentation └── .gitignore # Git ignore file

yaml
Copy
Edit

---

## 🚀 **Setup Instructions**

### 1. Clone the repository

```bash
git clone https://github.com/aniljangld7/house-price-predictor.git
cd house-price-predictor
2. Set up a virtual environment (recommended)
For Linux/Mac:

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate
For Windows:

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate
3. Install the required dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Run the Flask Application
bash
Copy
Edit
python app.py
Once the app is running, open a browser and visit:
http://127.0.0.1:5000/

