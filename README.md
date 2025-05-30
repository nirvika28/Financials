Financial Chatbot
A simple, rule-based Python chatbot that answers key financial questions about Microsoft, Tesla, and Apple using company data from 2021–2023.

Features
Answers three predefined financial queries for MSFT, TSLA, and AAPL

Reads data from an Excel file

Simple, easy-to-understand code

Getting Started
Prerequisites
Python 3.x

pandas

openpyxl

Installation
Clone this repository:

bash
git clone https://github.com/yourusername/financial-chatbot.git
cd financial-chatbot
Install dependencies:

bash
pip install pandas openpyxl
Ensure Financials_2021-2023.xlsx is in the project directory.

Usage
Run the script or open the Jupyter notebook.

Enter one of the supported queries:

What is the total revenue?

How has net income changed over the last year?

What is the profit margin?

The chatbot will respond with the relevant information for each company.

Example
text
> What is the total revenue?
MSFT total revenue (2023): $211.9B
TSLA total revenue (2023): $96.77B
AAPL total revenue (2023): $383.29B
Limitations
Only supports the three predefined queries above.

Only covers MSFT, TSLA, and AAPL for 2021–2023.

Does not use natural language processing or advanced AI.

License
For educational use only.
