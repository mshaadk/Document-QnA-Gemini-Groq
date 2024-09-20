# Document Q&A using Gemini and Groq

This application leverages advanced AI techniques to allow users to ask questions about documents and receive accurate answers based on the content.

## Features

- **Document Upload:** Load documents from a specified directory.
- **Vector Embeddings:** Create embeddings for document chunks using Google Generative AI.
- **Question Answering:** Ask questions related to the loaded documents and get context-based answers.
- **Document Similarity Search:** Explore similar document chunks related to the queried question.

## Getting Started

### Prerequisites

1. Python 3.7 or higher
2. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```
   
3. Set up your environment variables:

Create a `.env` file in the root directory and add your API keys:

   ```plaintext
   GROQ_API_KEY=your_groq_api_key
   GOOGLE_API_KEY=your_google_api_key
   ```

## Running the Application
1. Clone the repository:

   ```bash
   git clone https://github.com/mshaadk/Document-QnA-Gemini-Groq.git
   cd Document-QnA-Gemini-Groq
   ```
2. Run the Streamlit app:
   
   ```bash
   streamlit run app.py
   ```

3. Open your browser and navigate to `http://localhost:8501` to access the application.

## Usage
1. Upload your PDF documents into the us_census directory.
2. Click the "Documents Embedding" button to create a vector store from the uploaded documents.
3. Enter your question in the text input field and click Submit.
4. View the answer along with related document chunks in the expander section.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.
