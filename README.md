Resume Parser using Python, spaCy & PDFMiner
Description

This project is a Resume Parser that extracts useful information from PDF resumes using Natural Language Processing (NLP) techniques. It combines PDFMiner for text extraction, spaCy for named entity recognition, and regex-based rules for structured data extraction. The output is returned in a structured format (dictionary / DataFrame), making it easy to use for HR analytics, recruitment automation, or resume screening.

🚀 Features

Extract Text from PDF

Uses PDFMiner to extract raw text from resumes.

Text Cleaning

Removes unnecessary whitespace and special characters for better accuracy.

Personal Information Extraction

Name: Extracted using spaCy’s Named Entity Recognition (NER).

Email: Extracted with regex patterns.

Phone Number: Identifies different phone number formats.

Skills Extraction

Matches a predefined list of skills (Python, Machine Learning, SQL, TensorFlow, etc.).

Can be extended to support custom skill lists.

Work Experience Extraction

Uses regex to find job roles like Engineer, Developer, Manager, Intern along with companies.

Final Output

Returns a dictionary with Personal Info, Skills, and Experience.

Can easily be converted to CSV or Excel using Pandas for further analysis.
