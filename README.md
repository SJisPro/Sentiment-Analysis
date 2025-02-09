# **IMDB Review Sentiment Analysis**  

A web application that predicts the sentiment (positive or negative) of IMDB movie reviews. The project leverages **scikit-learn** and **Keras Sequential API** to build a deep learning model and uses **Streamlit** for an interactive web-based user interface.

---

## **Table of Contents**  
1. [About the Project](#about-the-project)  
2. [Features](#features)  
3. [Tech Stack](#tech-stack)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Screenshots](#screenshots)  
7. [Contributing](#contributing)  
8. [License](#license)  
9. [Contact](#contact)  

---

## **About the Project**  
This project uses a **Deep Learning model** to classify IMDB movie reviews as **positive** or **negative**. The model is trained using **Keras Sequential API** and **scikit-learn** for preprocessing.  

The trained model is deployed using **Streamlit**, which provides a simple UI for users to enter a movie review and get an instant sentiment prediction.

---

## **Features**  
✔ Sentiment analysis of IMDB reviews (Positive/Negative).  
✔ Preprocessing of text data using **Tokenization**, **Padding**, and **TF-IDF**.  
✔ Deep Learning model built with **Keras Sequential API**.  
✔ Web interface using **Streamlit**.  
✔ Real-time sentiment prediction.  

---

## **Tech Stack**  
### **Machine Learning & Deep Learning:**  
- **scikit-learn** for preprocessing (TF-IDF, tokenization).  
- **Keras Sequential API** with TensorFlow backend for building and training the deep learning model.  

### **Web Application:**  
- **Streamlit** for building and deploying the web-based UI.  

### **Other Dependencies:**  
- **NumPy**, **Pandas**, **Matplotlib**, **Seaborn** for data handling and visualization.  

---

## **Installation**  

Follow these steps to set up and run the project:

### **Prerequisites**  
Ensure you have **Python 3.8+** installed on your system.  

### **Steps**  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/username/IMDB-Sentiment-Analysis.git
   cd IMDB-Sentiment-Analysis
   ```

2. **Create and activate a virtual environment** (recommended)  
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/Mac
   venv\Scripts\activate     # For Windows
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app**  
   ```bash
   streamlit run app.py
   ```

5. Open your browser and go to `http://localhost:8501/` to use the app.  

---

## **Usage**  

1. **Enter a movie review** in the provided text box.  
2. Click on **Analyze Sentiment**.  
3. The model will process the review and display the sentiment as **Positive** or **Negative**.  

---

## **Screenshots**  
![Screenshot 2025-02-09 220747](https://github.com/user-attachments/assets/5eb42a67-6237-4acc-aa72-4e8fdbdc7f19)


---

## **License**  
This project is licensed under the **MIT License**. See `LICENSE` for details.

---

## **Contact**  
**Your Name**  
- Email: jainsamyakdelhi@gmail.com  
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/samyak-jain-0807ab249)  
- GitHub: [Your GitHub Profile](https://github.com/SJisPro)  
