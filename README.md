# KAPT - Knowledge Assessment and Plagiarism Tool

KAPT is an innovative web-based application designed to enhance the educational experience through a comprehensive plagiarism checker and automated question generation system. This tool helps maintain academic integrity by effectively detecting plagiarized content and allows educators to generate engaging multiple-choice questions (MCQs) based on provided text.

## Features

### Plagiarism Checker
- Detects plagiarism in both uploaded files and entered text.
- Compares student submissions against local documents and web content.
- Provides a detailed plagiarism report with similarity percentages for easier assessment.

### Q&A Generator
- Generates multiple-choice questions (MCQs) from entered text or uploaded documents.
- Summarizes the input text to create relevant questions.
- Offers options for multiple answer choices to enhance learning.

## Technologies Used
- **Frontend**: Streamlit, ReactJS, JavaScript, CSS, HTML
- **Backend**: Python, NLTK, TF-IDF Vectorizer, cosine similarity
- **Libraries**:
  - `requests` for web scraping
  - `BeautifulSoup` for parsing HTML
  - `scikit-learn` for calculating text similarity
  - `transformers` for summarization
  - `docx2txt` for handling DOCX files

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/KAPT.git
   cd KAPT
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage

- **Plagiarism Checker**: Select a method to input text (upload a file, or enter text directly). The tool will compare the content against both local submissions and online sources.
  
- **Q&A Generator**: Upload a text file or enter text directly to generate multiple-choice questions based on the content.

## Contributing

Contributions are welcome! If you would like to improve the project, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Special thanks to the contributors of libraries and frameworks that made this project possible.

For any questions or feedback, feel free to reach out. Happy coding!

---

Feel free to customize the text as needed, especially the repository URL, installation instructions, and anything specific to your project!