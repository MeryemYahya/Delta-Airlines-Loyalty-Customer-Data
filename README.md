# 🎯 Delta Airlines Loyalty Customer Data | Understanding What Customers Want  


## 🧠 What’s This All About?

This project is like being a detective 🕵️‍♀️ looking through customer data to understand what people do, what they want, and how we can predict their next move.

Imagine you're running a service where customers can book flights, add snacks, ask questions, or choose extra services. You have loads of data... but what is it really telling you?

This notebook walks through the full journey — from cleaning and exploring the data, to building smart tools that **help make decisions**.

---

## 📚 What's in the Notebook?

Here’s the journey we take inside the notebook:

### 1. 📦 Importing Libraries
We start by bringing in the tools we’ll need — Python libraries like `pandas`, `seaborn`, and `scikit-learn`.

---

### 2. 🧹 Cleaning the Data  
Real-world data is messy. We:
- Remove duplicates
- Fix strange formatting (e.g., weird yes/no columns)
- Handle missing values
- Standardize text so it’s easy to work with

Think of it like tidying a messy room before starting a project!

---

### 3. 📊 Exploring the Data (EDA)  
We ask questions like:
- What kinds of inquiries are customers making?
- Do people who book flights also order snacks?
- How common is lounge access or added baggage?
- Who comes from email vs. phone vs. web?

And we use colorful charts and graphs to bring the answers to life.

---

### 4. 📈 Visualizations for Insight  
We visualize key parts of the data:
- Bar charts for choices (like “Planned Snack?” or “Used Lounge?”)
- Trends in behaviors
- Customer breakdowns by source, interaction, and features

This helps us **spot trends and patterns** at a glance.

---

### 5. 🧪 Preparing the Data for Machine Learning  
Before making predictions, we:
- Convert text and categories into numbers (using encoders)
- Scale numerical values so they're ready for models
- Split the data into training and testing sets

This step is like prepping ingredients before cooking a dish.

---

### 6. 🤖 Building Predictive Models  
We train **three types of models** to make predictions:

#### ✅ Logistic Regression  
Great for answering "Yes or No" questions like:
> Will this customer do [X]?

#### 📍 K-Nearest Neighbors (KNN)  
Looks at what similar customers did.

#### 🌲 Random Forest  
Uses many decision trees to vote on the best prediction — like a committee!

---

### 7. 🧠 Making Predictions & Understanding Them
After training our models, we:
- See how well they perform
- Compare accuracy scores
- Interpret the results and what they mean for the business

---

## 📌 Project Highlights

✅ Clean, readable Python code  
✅ Real-world customer data  
✅ Easy-to-understand visual storytelling  
✅ Beginner-friendly explanations of technical steps  
✅ Built-in insights for marketing and product teams



## ⚙️ How to Run
### 💻 Setup
Make sure you have Python installed and run:

```bash
pip install pandas seaborn matplotlib scikit-learn
```

Then open the notebook:

```bash
jupyter notebook "NoteBook.ipynb"
```
