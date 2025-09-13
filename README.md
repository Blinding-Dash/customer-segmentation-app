# AI-Powered Customer Segmentation App

This app performs customer segmentation using **K-Means clustering** and generates marketing personas using **Google Gemini AI**.  
It supports **demographic, behavioral, and psychographic features**.

---

## 🚀 Features
- Upload your own customer dataset (CSV)
- Automatic clustering with K-Means
- Behavioral (RFM) and Psychographic segmentation
- Interactive 2D & 3D plots
- AI-generated personas for each cluster
- Help & Glossary section for non-technical users

---

## 📦 Installation (Local)
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/customer-segmentation-app.git
   cd customer-segmentation-app
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   streamlit run app2.py
   ```

---

## ☁️ Deployment (Streamlit Cloud)
1. Push this repo to GitHub.
2. Go to [Streamlit Community Cloud](https://share.streamlit.io/).
3. Log in → **New App** → Select your repo → Set main file to `app2.py`.
4. Add your **Gemini API key** in Streamlit Secrets:
   ```
   GOOGLE_API_KEY = "your_api_key_here"
   ```
5. Deploy 🎉 and share your link.

---

## 📊 Example Dataset
An example dataset (`sample_data.csv`) with 200 customers is included for demo purposes.

---

## 📖 Glossary
- **Segmentation** → Dividing customers into groups with similar traits.
- **RFM Analysis** → Recency, Frequency, Monetary segmentation.
- **K-Means Clustering** → Algorithm to form customer clusters.
- **Persona** → Fictional profile representing a customer group.
