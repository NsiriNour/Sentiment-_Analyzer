###Sentiment Analyzer
An interactive web application that performs sentiment analysis on bulk reviews uploaded via Excel files.
Features:
Bulk Processing: Upload an .xlsx file and analyze hundreds of reviews at once.
AI Model: Uses the DistilBERT transformer model for high-accuracy sentiment classification (Positive/Negative).
Data Visualization: Automatically generates a pie chart to show the percentage of positive vs. negative feedback.
Interactive Table: Displays the original reviews alongside their predicted sentiment labels.
##Tech Stack:
Transformers (Hugging Face): To run the DistilBERT sentiment model.
Gradio: To create the web interface.
Pandas: For Excel data manipulation.
Matplotlib: For generating the sentiment pie chart.
How to Use
## Requirements
To run this notebook on your own machine, you will need Python installed along with the libraries listed in the `requirements.txt` file.
Run the App: Execute the script.
Upload: Provide an Excel file that has a column named "Reviews".
Result: View the processed data table and the visual sentiment chart.
You can install them quickly using pip:
```bash
pip install -r requirements.txt ```
