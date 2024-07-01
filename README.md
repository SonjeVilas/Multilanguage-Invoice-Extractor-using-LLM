# Multilanguage Invoice Extractor using LLM

This project is a Streamlit application that extracts and understands invoice details from uploaded images using the Gemini Pro Vision model from Google's generative AI. The application can handle invoices in multiple languages and provides responses based on the content of the invoice.


## Features

**Multi-language support :** The application can process invoices in various languages.

**Image upload :** Users can upload invoice images in JPG, JPEG, or PNG formats.

**Generative AI integration :** Utilizes the Gemini Pro Vision model for content generation and understanding.

**User-friendly interface :** Built with Streamlit, providing a simple and interactive user interface.


## Technologies Used

- Streamlit for building the web application.
- Google Generative AI API for image processing and LLM integration.
- Python 3.x as the programming language.
- PIL (Python Imaging Library) for image handling.

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/invoice-extractor.git
cd invoice-extractor
```

Create a virtual environment and activate it:

```bash
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

 1.Run the Streamlit application:

```bash
  streamlit run app.py
```

2.Open your web browser and go to http://localhost:8501 to access the application.

3.Upload an invoice image: Click on "Choose an image of the invoice..." and select your image file.

4.Input a prompt: Provide a prompt for the model to understand what details to extract from the invoice.

5.Submit: Click on the "Tell me about the invoice" button to get the response from the model.





## Set up Environment Variables

Create a .env file in the root directory of your project and add your Google API key:

`GOOGLE_API_KEY=your_google_api_key`



## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).


## Acknowledgements

 - [Streamlit](https://streamlit.io/)
 - [Google Generative AI]()
