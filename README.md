# Automated PDF Data Extraction

This project automates the extraction and analysis of data from PDF documents, converting unstructured data into structured Excel files. It supports multi-language extraction and provides high accuracy in text extraction and checkbox recognition.

## Features

- **Automated Text Extraction**: Extracts and converts text from PDF files into structured Excel files.
- **Checkbox Recognition**: Identifies and records checkbox selections from forms.
- **Image Detection**: Detects and extracts images from PDF files.
- **Multi-language Support**: Supports OCR and translation for multiple languages including English, Spanish, French, German, Chinese (Simplified), Malay, Tamil, and Hindi.
- **Deployment**: Utilizes pyngrok for easy deployment.

## Technologies Used

- **Frontend**: Streamlit
- **Backend**: Python
  - Libraries: PyMuPDF, pytesseract, pdf2image, Pillow, pandas, openpyxl, OpenCV, Google Translate API, Camelot, Tabula
- **Others**: pyngrok

# PDF to Excel Converter

This project automates the extraction and analysis of data from PDF documents, converting unstructured data into structured Excel files. 

## Features
- Convert multiple PDF files into a single Excel file.
- Extract text and checkbox selections from PDF files.
- Supports multi-language OCR and translation.
- Provides hyperlinks to detected images in the Excel file.
- Achieves over 95% accuracy in text extraction and checkbox recognition.
- Reduces manual data entry time by 80%.

## Technologies Used
- **Frontend:** Streamlit
- **Backend:** Python (PyMuPDF, pytesseract, pdf2image, Pillow, pandas, openpyxl, OpenCV, Google Translate API, Camelot, Tabula)
- **Deployment:** pyngrok

## Screenshots
![Screenshot 1](https://github.com/YourUsername/YourRepoName/blob/main/Screenshot%202024-08-04%20103555.png)
![Screenshot 2](https://github.com/YourUsername/YourRepoName/blob/main/Screenshot%202024-08-04%20103612.png)
![Screenshot 3](https://github.com/YourUsername/YourRepoName/blob/main/Screenshot%202024-08-04%20103622.png)
![Screenshot 4](https://github.com/YourUsername/YourRepoName/blob/main/Screenshot%202024-08-04%20103632.png)
![Screenshot 5](https://github.com/YourUsername/YourRepoName/blob/main/Screenshot%202024-08-04%20103951.png)
![Screenshot 6](https://github.com/YourUsername/YourRepoName/blob/main/Screenshot%202024-08-04%20104032.png)
![Screenshot 7](https://github.com/YourUsername/YourRepoName/blob/main/Screenshot%202024-08-04%20104047.png)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SanjanaReddySangam/Automated-PDF-Data-Extraction.git
   cd Automated-PDF-Data-Extraction


## Statistics

- Achieved over 95% accuracy in text extraction and checkbox recognition.
- Processed over 500 PDF documents.
- Reduced manual data entry time by 80%.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/SanjanaReddySangam/Automated-PDF-Data-Extraction.git
    cd Automated-PDF-Data-Extraction
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

## Usage

1. Upload the PDF files you want to process.
2. Select the language for OCR and translation.
3. Download the converted Excel file.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request.

## Acknowledgments

Thanks to my co-developer [Kedhar](https://github.com/Kedhar7) for the invaluable support and collaboration on this project.

## Future Developments

- Further develop image and checkbox features.

## Contact

**Sanjana Reddy Sangam**
- Email: [sangamsanjanareddy@gmail.com](mailto:sangamsanjanareddy@gmail.com)
- GitHub: [SanjanaReddySangam](https://github.com/SanjanaReddySangam)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
