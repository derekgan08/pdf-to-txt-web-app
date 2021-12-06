# CAT201 Assignment 1: Web App - Convert PDF to TXT

## Problem Statements
In the real world, many users receive documents in PDF format, but sometimes need to extract the content for further processing, editing, or analysis. A web-based solution can make this conversion accessible from anywhere, without needing additional software. This project leverages Docker for portability and scalability, providing a lightweight and efficient conversion service. With this tool, users can easily upload PDFs and receive text files in return, all through a simple web interface. This web app is fully Dockerized, ensuring scalability and ease of deployment.

## Project Overview
This project is a web-based PDF to TXT conversion tool, designed to run inside a Docker container. The application allows users to upload PDF files through a simple HTML interface, which are then processed on the server using the Apache PDFBox library. The server extracts text from the PDF file and converts it into a plain text (.txt) file, which users can then download. The goal of this project is to provide a simple and portable solution for converting PDF documents into editable text, with the entire system contained within a Docker environment for ease of deployment and scalability.

The system provides the following features:

- Dockerized Environment: The Apache web server and application run inside a Docker container, ensuring consistent and portable execution across different environments.
- File Upload Interface: Users can upload PDF files through an intuitive HTML form.
- PDF to TXT Conversion: The server processes the uploaded PDF files using Apache PDFBox and converts them to plain text format.
- File Retrieval: Once the conversion is complete, users can download the resulting text file through a direct download link.

## Key Features
- **Dockerized Deployment:** The entire web application is packaged in a Docker container for easy setup and portability.
- **Web Interface:** Simple HTML and CSS interface for users to upload PDF files and receive text files in return.
- **PDF to TXT Conversion:** Uses Apache PDFBox to extract text from PDF files and convert them into plain text.
- **Secure File Handling:** Uploaded PDF files are processed on the server and deleted after conversion.
- **Easy Retrieval:** Once conversion is completed, the system provides a link for users to download the resulting text file.

## Technologies Used
- **Backend:** Java with Apache PDFBox
- **Web Server:** Apache HTTP Server running inside a Docker container
- **Frontend:** HTML, CSS (for the web form and basic styling)
- **Docker:** For containerizing the web server and the application
- **Maven:** To manage Java dependencies and build the application

## Installation
This project is not open for public cloning or redistribution without prior written permission from the author as stated in ![LICENSE.md](LICENSE.md). If you would like to access this project, please reach out to the repository owner to request permission.

Once written permission is granted, you will receive detailed instructions on how to install and run the system, including all necessary steps and dependencies.

## Usage
Similar to the installation process, usage instructions will be provided only after written permission is granted to access this repository. Upon receiving access, you will be provided with step-by-step instructions on how to use this system/application, including on how to run the program, interact with it and exploring all the key features stated.

## Screenshots
<p align="center">
<img src="readme-assets/01 Upload PDF File.png" alt="upload pdf file screen"/>
<br/>
<i>Figure 1: Upload PDF File Screen</i>
</p>

<p align="center">
<img src="readme-assets/02 Download Generated Text File.png" alt="download generated text file screen"/>
<br/>
<i>Figure 2: Download Generated Text File</i>
</p>

<p align="center">
<img src="readme-assets/03 Generated Text File.png" alt="generated text file screen"/>
<br/>
<i>Figure 3: Generated Text File</i>
</p>

<p align="center">
<img src="readme-assets/04 Generated Text File (Maximised Window).png" alt="generated text file screen"/>
<br/>
<i>Figure 4: Generated Text File (Maximised Window)</i>
</p>

<p align="center">
<img src="readme-assets/05 Validation - No File Chosen.png" alt="no file is chosen screen"/>
<br/>
<i>Figure 5: Validation when no file is chosen</i>
</p>

<p align="center">
<img src="readme-assets/06 Validation - Invalid File Type.png" alt="invalid file is chosen screen"/>
<br/>
<i>Figure 6: Validation when file is invalid</i>
</p>