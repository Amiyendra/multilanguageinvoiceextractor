# Multilanguage Invoice Extractor

This project is a Streamlit-based web application that extracts information from invoices in various languages using Google's Generative AI (`gemini-1.5-flash`). It allows users to upload an image of an invoice, input a question or prompt, and receive AI-generated insights about the invoice.

---

## Features
- **Image Upload**: Upload invoice images in `JPG`, `JPEG`, or `PNG` formats.
- **Generative AI Integration**: Uses Google's Generative AI model `gemini-1.5-flash` to analyze invoices and respond to queries.
- **Multilingual Support**: Extract and understand invoice details in multiple languages.
- **Simple User Interface**: Built with Streamlit for an easy-to-use interface.

---

## Requirements
### Python Libraries
- `dotenv`: To load environment variables.
- `streamlit`: For building the web interface.
- `Pillow (PIL)`: To handle image uploads and processing.
- `google.generativeai`: To use the `gemini-1.5-flash` model.

### API Key
This project requires a **Google Generative AI API Key**. Ensure the key is stored securely in a `.env` file under the variable name `GOOGLE_API_KEY`.

---

## Setup and Installation
1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
