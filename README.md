# 📚💬 Chat with Multiple PDFs Gemini

Chat with Multiple PDFs Gemini is a Streamlit application that enables users to interactively ask questions related to the content of multiple uploaded PDF files. The application harnesses the power of Google Gemini Pro AI for both document similarity search and generating detailed responses to user queries.

## ✨ Features

- **PDF Upload**: Users can upload multiple PDF files containing textual information.
- **Question Answering**: Users can ask questions related to the content of the PDF files.
- **Gemini Pro AI Integration**: The application utilizes Google Gemini Pro AI for document similarity search and generating detailed responses.
- **Efficient Document Processing**: The PDFs are processed to create a Faiss index for efficient document retrieval based on user queries.

## 🚀 Getting Started

To run the Chat with Multiple PDFs Gemini locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Set up your Google API key and other environment variables as specified in the `.env` file.
4. Ensure that you have the necessary PDF files to upload.
5. Run the Streamlit app by executing `streamlit run app.py` in your terminal.

## 💡 Usage

1. Upload your PDF files using the file uploader.
2. Enter your question in the text input field.
3. Click on the "Submit & Process" button.
4. View the generated response from the Gemini Pro AI based on the content of the PDF files.

## 🛠️ Technologies Used

- **Streamlit**: For building the interactive web application.
- **Google Gemini Pro AI**: For document similarity search and question answering.
- **PyPDF2**: For extracting text from PDF files.
- **FAISS**: For efficient similarity search and vector storage.

## 🙏 Acknowledgements

Special thanks to Google Generative AI for providing access to the Gemini Pro AI.
