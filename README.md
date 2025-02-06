Firecrawl Streamlit App

Overview

This Streamlit application enables users to extract structured data from any website using Firecrawl's API. Users can provide a website URL, define an optional schema, and receive extracted data in a structured format. The extracted data is displayed in an interactive chat-based interface.

Features

Website Data Extraction: Convert any website into structured API data.

Schema Builder: Define custom field names and types for extracted data.

Interactive Chat: Ask questions about the extracted website data.

Real-Time Streaming: Typing effect for responses.

Session Management: Caching and session state handling.

Installation

Prerequisites

Python 3.8+

pip package manager

Steps

Clone the repository:

git clone <repo-url>
cd <repo-directory>

Install dependencies:

pip install -r requirements.txt

Set up environment variables:

Create a .env file in the root directory.

Add your Firecrawl API key:

FIRECRAWL_API_KEY=your_api_key_here

Run the Streamlit app:

streamlit run app.py

Usage

Enter a Website URL: Provide the URL of the website you want to extract data from.

Define Schema (Optional): Specify field names and data types for extracted content.

Chat with the Extracted Data: Ask questions and receive structured responses.

View Extracted Data: Data is presented in a markdown table format.

Technologies Used

Streamlit: For UI and interactive components

Firecrawl API: For website data extraction

Pandas: For data transformation

Pydantic: For schema validation

dotenv: For environment variable management

Known Issues & Limitations

Currently supports a maximum of 5 schema fields.

Requires a valid Firecrawl API key.

Performance depends on Firecrawl API response time.

Contribution

Feel free to submit pull requests or raise issues
