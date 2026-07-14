# Ecom-reviews-mail-generation
Ecom Mail generation on Reviews of customers using GenAI 
# Customer Reviews Analysis & AI-Powered Customer Response

## 📌 Project Summary

This project analyzes an e-commerce customer reviews dataset to identify common customer complaints, classify reviews based on ratings, visualize complaint trends, and automatically generate personalized customer support emails using Google's Gemini AI through LangChain.

The notebook demonstrates a complete workflow from data preprocessing to AI-powered response generation.

---

## 📂 Project Features

- Import and clean customer review data
- Rename and standardize dataset columns
- Analyze customer ratings
- Categorize reviews into:
  - Critical (Ratings 1–2)
  - Average or Good (Ratings 3–5)
- Extract critical reviews
- Identify the most common complaint keywords
- Visualize complaint frequency using Plotly
- Find Top-K complaint categories
- Retrieve customer reviews using Customer ID
- Generate personalized apology emails using Gemini AI and LangChain

---

## 📊 Workflow

1. Load customer review dataset
2. Clean and rename columns
3. Analyze rating distribution
4. Classify reviews
5. Filter critical reviews
6. Count complaint keywords
7. Visualize complaint statistics
8. Retrieve customer-specific reviews
9. Generate AI-based customer support emails

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- LangChain
- Google Gemini API
- Jupyter Notebook

---

## 📁 Dataset

Expected dataset:

`customer_reviews_dataset_45.csv`

The dataset includes customer information, ratings, and review titles used for complaint analysis.

Example columns:

- Cust_Id
- Product
- Rating
- Review
- Full Review

---

## 📈 Analysis Performed

### Rating Analysis
- Counts ratings across all customers.
- Separates critical customers from satisfied customers.

### Complaint Analysis
Finds the most common complaint categories such as:
- Cheap Quality
- Poor Battery
- Wrong Item

### Visualization
Creates an interactive Plotly bar chart showing complaint frequencies.

### Top Complaints
Displays the Top-K most frequent customer complaints.

---

## 🤖 AI Customer Support

Using LangChain and Google's Gemini model, the notebook generates personalized apology emails based on each customer's complaint.

Example use case:

Input:
- Customer ID
- Review

Output:
- Professional customer support email
- Personalized apology
- Resolution message

---

## 📦 Required Libraries

Install dependencies before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn plotly
pip install langchain langchain-core langchain-community
pip install langchain-google-genai
```

---

## ▶️ How to Run

1. Clone the repository.
2. Install all dependencies.
3. Place the dataset (`customer_reviews_dataset_45.csv`) in the project folder.
4. Add your Google Gemini API key.
5. Run the notebook from top to bottom.

---

## 📌 Results

The notebook successfully:

- Performs customer review analysis
- Detects the most common complaints
- Visualizes complaint statistics
- Generates AI-powered personalized customer support emails
- Demonstrates how LLMs can automate customer service workflows

---

## ⚠️ Security Note

The notebook currently contains a hard-coded Gemini API key. **Do not commit API keys to public repositories.** Instead, store them securely using environment variables or a `.env` file.

---

## 🚀 Future Improvements

- Perform sentiment analysis on review text
- Build an interactive dashboard using Streamlit
- Support multiple LLM providers
- Export AI-generated emails to CSV or PDF
- Automate email delivery
- Add complaint trend analysis over time

---

## 👨‍💻 Author

Developed as a customer review analytics and AI-powered customer support automation project using Python, data analysis libraries, LangChain, and Google Gemini.
