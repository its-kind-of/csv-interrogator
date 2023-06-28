# CSV Agent
This is a Python script that utilizes the langchain package to create a CSV agent. The CSV agent is capable of answering questions about a CSV file using the OpenAI API. This script provides a simple user interface built with Streamlit to upload a CSV file and ask questions about its content.

## Prerequisites
Before running the code, make sure you have the following:

* Python 3.x installed
* The necessary Python packages installed. You can install them by running the following command:
```pip install langchain streamlit python-dotenv```
* An OpenAI API key. You can obtain one from the OpenAI website.

# Getting Started
1. Clone the repository or download the code.
2. Open a terminal and navigate to the directory where the code is located.
3. Create a file named .env in the same directory and add the following line, replacing YOUR_API_KEY with your OpenAI API key:
makefile
```OPENAI_API_KEY=YOUR_API_KEY```
4. Save the .env file.
5. Run the following command to start the application:
```python filename.py```
Replace filename.py with the name of the Python file containing the code.
# Usage
1. After running the code, a web page will open in your default browser.
2. The page displays a header "Ask your CSV" and a file uploader.
3. Click on the "Upload a CSV file" button to select a CSV file from your local machine.
4. Once the file is uploaded, the agent will be created using the OpenAI API and the uploaded CSV file.
5. Enter your question about the CSV file in the text input field labeled "Ask a question about your CSV".
6. Click on the "Enter" button or press "Enter" to submit the question.
7. The answer to your question will be displayed on the page.

## Important Note
Make sure you have set the OPENAI_API_KEY environment variable correctly. If it is not set or is empty, the code will exit with an error message.

Feel free to explore the code and modify it according to your requirements. Enjoy asking questions about your CSV files!