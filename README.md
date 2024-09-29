# Business Card Scanner
A simple web application built using Streamlit and Pytesseract to extract text from business card images.

## Features

- Upload a business card image (jpg, jpeg, png)
- Extract text from the image using Optical Character Recognition (OCR)
- Display extracted text, including company name, ID, and other relevant information

## Requirements
- Python 3.x
- Streamlit
- Pytesseract
- Tesseract-OCR
- Ngrok (for tunneling)

## Installation
Clone the repository: 

 
 
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/business-card-scanner.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Install Tesseract-OCR:
    ```bash
    sudo apt-get install tesseract-ocr (on Linux)
    ```
4. Set up Ngrok:
    ```
    ngrok authtoken 'Your Auth Key'
    ```
5. Run the Streamlit application:
    ```bash
    streamlit run _Project_5_Business_Card_Scanner.ipynb
    ```
## Usage
- **Run the application:** streamlit run Business_Card_Scanner.py
- Upload a business card image
- View extracted text
## Note
- This application is built using **Colab** and may require modifications to run on other environments.
- **Ngrok** is used for tunneling and may require a paid plan for heavy usage.

## DESCRIPTION

Business Card Scanner is a simple web application that uses Optical Character Recognition (OCR) to extract text from business card images. The application is built using Streamlit and Pytesseract, and can be easily deployed using Ngrok.

The application allows users to upload a business card image, which is then processed using OCR to extract relevant text, including company name, ID, and other information. The extracted text is then displayed on the screen.

This application is a proof-of-concept and may require further development to improve accuracy and functionality. However, it demonstrates the potential of using OCR to automate data extraction from business cards.

## CONTRIBUTING
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.
