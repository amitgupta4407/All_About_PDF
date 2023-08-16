# AllAboutPDF 📄

AllAboutPDF is a web-based application for working with PDF files. With this app, you can perform a variety of PDF-related tasks, such as finding out mata data, extract image, extract text, extract annotation and more. 🔨
One of the unique features that sets AllAboutPDF apart from other online PDF apps is our ChatPDF feature. This feature allows users to interact with their PDF files using OpenAI and LangChain's natural language processing technology, enabling users to quickly find the information they need and complete tasks more efficiently.


## Live Project Link 🚀

The live version of the app is hosted on Streamlit Sharing and can be accessed at the following URL:

- Main application:  https://amitgupta4407-all-about-pdf-app-dmn92l.streamlit.app/
- Test feature: https://allaboutpdf-multiple-filequery-feature.streamlit.app/
## Features 🎉

- Extract text from a PDF file 💬
- Extract images from a PDF file 🖼️
- Extract metadata from a PDF file 📝
- Encrypt a PDF file with a password 🔒
- _**Chat with a PDF file using OpenAI and Langchain**_ 🤖
- _**Chat with multiple textual file(pdf, txt, doc, excel, csv, sql)**_  (https://allaboutpdf-multiple-filequery-feature.streamlit.app/)

## Overview 📋

AllAboutPDF is built using the Python programming language 🐍 and the Streamlit framework. The app uses the PyPDF2 library to perform various PDF-related tasks, such as parsing and extracting relavent information from PDFs. The app also uses OpenAI and Langchain APIs to enable the "ChatPDF" feature.

When a user uploads a PDF file to the app, the app performs the requested task (e.g. merging PDFs), and then generates a new PDF file that the user can download.

## Installation ⚙️

To install the repository, please clone this repository and install the requirements:

```
pip install -r requirements.txt
```

## Usage 🏃

- To use the main application, run the `main.py` file with the streamlit CLI (after having installed streamlit): 

```
streamlit run app.py
```
- To use the test feature application, run the `FileQueryHub.py` file with the streamlit CLI (after having installed streamlit): 

```
streamlit run FileQueryHub.py
```

## Motivation 💡

The motivation behind AllAboutPDF was to create a simple, user-friendly tool for working with PDF files. While there are many PDF-related tools available online, many of them are complex and difficult to use. AllAboutPDF aims to provide an easy-to-use alternative that can be used by anyone, regardless of technical expertise and make process of data extraction a cake work.

## Problem Solved ✅

PDF files are a ubiquitous file format used for sharing documents across platforms and devices. However, working with PDF files can often be a tedious and time-consuming process. AllAboutPDF aims to solve this problem by providing a simple, user-friendly tool for working with PDF files.

## Tech Stack 🛠️

AllAboutPDF is built using the following technologies:

- Python 🐍
- Streamlit 🌟
- PyPDF2 📑
- OpenAI 🤖
- Langchain 🔗

## Challenges Faced 🤔

📚 Selecting the most suitable libraries for the project, which we accomplished by choosing Python, Streamlit, PyPDF2, and LangChain.
🌟 Developing a unique feature that distinguishes AllAboutPDF from other online PDF apps. Our ChatPDF feature allows users to interact with their PDF files using OpenAI and LangChain's natural language processing technology.
💰 Optimizing the cost of preparing the knowledge base for ChatPDF by selecting the correct size and ratio of the chunk size and overlap size.

## Future Plans 🔮

We have several future plans for AllAboutPDF, including:
- Merge multiple PDF files into a single file 📂
- Split a PDF file into multiple files 📄
- Compress a PDF file to reduce its size 📉
- Convert a PDF file to a different file format (e.g. JPEG, PNG, DOCX) 🔄
- Adding more PDF-related features, such as OCR (Optical Character Recognition) and watermarking
- Adding support for more file formats (e.g. Word documents, Excel spreadsheets)


>If you have any feedback or suggestions for how we can improve AllAboutPDF, please don't hesitate to get in touch!


## Some Screen shot for [ https://s3.amazonaws.com/static.nomic.ai/gpt4all/2023_GPT4All_Technical_Report.pdf ]
-------------
![image](https://github.com/amitgupta4407/All_About_PDF/assets/73437027/07299ade-fc6c-4987-936c-42d81f2efcad)
-------------
![image](https://github.com/amitgupta4407/All_About_PDF/assets/73437027/4e432feb-590a-44b0-af04-18b331153995)
-------------
![image](https://github.com/amitgupta4407/All_About_PDF/assets/73437027/3701e779-839b-415d-9e82-707153274f91)
-------------
![image](https://github.com/amitgupta4407/All_About_PDF/assets/73437027/e77d9fc6-30c6-4bf3-bff2-67990d69f68d)
-------------
![image](https://github.com/amitgupta4407/All_About_PDF/assets/73437027/17dbbf53-e621-41ae-85d0-47a329d79aa1)
-------------
![image](https://github.com/amitgupta4407/All_About_PDF/assets/73437027/3e04c342-9fad-412c-9e98-f0dab8d69c2f)
-------------


## Links
- 👉 Streamlit: https://streamlit.io/
- 👉 Langchain docs: https://python.langchain.com/en/latest/index.html
- 👉 How🤔 ChatPDF works: https://bennycheung.github.io/ask-a-book-questions-with-langchain-openai

![ Ask_Book_Questions_Workflow_Ext](https://github.com/amitgupta4407/All_About_PDF/assets/73437027/6e670334-d929-42be-8681-2ce803cf8b1a)
