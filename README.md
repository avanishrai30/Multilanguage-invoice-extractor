# Multi-Language Invoice Extractor

The Multi-Language Invoice Extractor is a sophisticated tool designed to streamline the process of extracting information from invoices in various languages. Leveraging the power of AI and the Gemini API, this tool offers unparalleled accuracy and efficiency in processing invoice data.

## Key Features

- **Multi-Language Support:** The extractor is capable of handling invoices in multiple languages, making it versatile and adaptable to diverse business needs.
- **Image Recognition:** Powered by Google GenerativeAI, the tool uses advanced image recognition algorithms to accurately extract data from invoice images.
- **Streamlit Interface:** The user-friendly Streamlit interface provides a seamless user experience, allowing users to easily upload and process invoices.

## Technologies Used

- **Streamlit:** A Python library used for creating web applications with simple and intuitive interfaces.
- **Google GenerativeAI:** A cutting-edge AI technology used for image recognition and processing.
- **Python-dotenv:** A Python library used for managing environment variables in development.
- **PyPDF2:** A Python library for reading PDF files.
- **Pdf2image:** A Python library for converting PDF files to images.
- **Faiss-cpu:** A library for efficient similarity search and clustering of dense vectors.
- **Langchain:** A library for language detection and translation.
- **Langchain_google_genai:** A model for language detection and translation using Google GenerativeAI.

## Installation

To use the Multi-Language Invoice Extractor, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/MultiLanguageInvoiceExtractor.git
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up environment variables:**
   - Create a `.env` file.
   - Add your Google API key: `GOOGLE_API_KEY=your_api_key_here`

## Usage

1. **Run the Streamlit app:**
   ```bash
   streamlit run app.py
   ```
2. **Upload an image of an invoice** to extract information.

## Contributors

- [avanishrai](https://github.com/avanishrai30)

## Interface
![Screenshot (11)](https://github.com/avanishrai30/Multilanguage-invoice-extractor/assets/82101000/fe33b501-f9df-4ccd-8169-d03df796b597)

## Response
![Screenshot (10)](https://github.com/avanishrai30/Multilanguage-invoice-extractor/assets/82101000/13543a5a-04c9-4d99-8dd8-d7bfd15e96ed)
