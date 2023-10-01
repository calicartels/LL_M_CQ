# LLM MCQs Generator with Davenchi 3

This is a tool for generating multiple-choice questions (MCQs) through the power of LLM's. It leverages the power of Davenchi-003, a state-of-the-art language model developed by OpenAI, to extract relevant descriptions from PDF documents and automatically generate MCQs based on the extracted content.

## Features

- **PDF Text Extraction**: The tool utilizes Davenchi 3 to extract text descriptions from PDF files. This enables automatic processing of legal documents, saving time and effort.
- **MCQ Generation**: Using the extracted text, the tool generates multiple-choice questions related to the LLM field. This helps in creating practice tests, assessments, or study materials.
- **Customization Options**: The tool provides various options for customizing the generated MCQs. You can specify the number of questions, difficulty level, topic focus, and other parameters to suit your requirements.
- **Efficient and Time-Saving**: With the ability to process PDFs and generate MCQs automatically, this tool streamlines the content creation process, allowing you to focus on other important tasks.

## Installation

To use this tool, follow the steps below:

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/calicartels/LL_M_CQ.git
   ```

2. Install the required dependencies using pip:

   ```
   pip install openai
   pip install PyPDF2
   ```

3. Download and install Davenchi-003 from the OpenAI website. Please refer to the OpenAI documentation for installation instructions.

4. Place your PDF files in the designated directory.

## Usage

To generate MCQs with this tool, follow the steps below:

1. Run the main script:

   ```
   script.py
   ```

2. Follow the on-screen prompts to select the PDF file(s), customize the MCQ generation options, and specify the output format.

3. Once the MCQ generation process is complete, the tool will provide you with the generated questions in the specified format (e.g., text file, CSV, etc.).

4. You can now use the generated MCQs for your intended purpose, such as studying, creating practice tests, or integrating them into an educational platform.

## Contributing

Contributions to this project are welcome! If you encounter any issues, have suggestions for improvements, or would like to add new features, please open an issue on the GitHub repository or submit a pull request.

## Disclaimer

Please note that this tool is provided for educational and informational purposes only. The generated MCQs should be reviewed and verified by subject matter experts for accuracy and relevance before use in any formal assessments or evaluations. The creators of this tool cannot be held responsible for any inaccuracies or misuse of the generated content.

## Note

This code demonstrates how to use the OpenAI API with the GPT-3 language model, specifically the Davinci-003 engine, to generate multiple-choice questions.
It takes a paragraph as input, reduces its length if necessary, and generates the specified number of multiple-choice questions based on the paragraph. The questions and answers are then printed.

Make sure to replace 'YOUR_API_KEY' with your actual OpenAI API key.

Remember to have the openai Python package installed (pip install openai) and a valid OpenAI API key to run this code successfully.


