# Review Sentiment Analyzer Project 🧠

## About This Project

An interactive web application that performs sentiment analysis on bulk reviews uploaded via Excel files.

---

## Features

This project provides several useful capabilities:

* **Bulk Processing:** Upload an `.xlsx` file and analyze hundreds of reviews at once.
* **AI Model:** Uses the DistilBERT transformer model for high-accuracy sentiment classification *(Positive/Negative)*.
* **Data Visualization:** Automatically generates a pie chart to show the percentage of positive vs. negative feedback.
* **Interactive Table:** Displays the original reviews alongside their predicted sentiment labels.

---

## Tech Stack

This project is built using the following tools:

* **Transformers (Hugging Face):** To run the DistilBERT sentiment model
* **Gradio:** To create the web interface
* **Pandas:** For Excel data manipulation
* **Matplotlib:** For generating the sentiment pie chart

---
## Result:
<img width="1878" height="893" alt="image" src="https://github.com/user-attachments/assets/56012bd0-ffc5-4865-8e59-dd6b5392d20c" />

## How to Use

### Requirements

To run this notebook on your own machine, you will need Python installed along with the libraries listed in the `requirements.txt` file.

You can install them quickly using pip:

```bash
pip install -r requirements.txt
```

---

### Steps to Run

1. **Run the App:** Execute the script.
2. **Upload:** Provide an Excel file that has a column named `"Reviews"`.
3. **Result:** View the processed data table and the visual sentiment chart.

---

