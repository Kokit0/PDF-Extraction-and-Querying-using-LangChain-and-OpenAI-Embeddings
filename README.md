# PDF-Extraction-and-Querying-using-LangChain-and-OpenAI-Embeddings
PDF Text Extraction and Querying using LangChain and OpenAI Embeddings.

Hey there. Kokke here 👋

## Introduction

Welcome to our GenAI project, where we're about to dive headfirst into the riveting world of PDF querying, all thanks to Langchain (yeah, I know, "PDFs" and "exciting" don't usually go hand in hand, but let's make it sound cool). But what's Langchain, you ask? Well, consider it your digital detective, your trusty sidekick, ready to help you navigate the labyrinth of PDF documents.

Langchain, a Large Language Model (LLM), is your unwavering companion on this adventure. It's equipped with the extraordinary power to extract keywords, phrases, and sentences from PDFs, all at the snap of your fingers (well, a few lines of code, to be precise). In essence, it transforms these seemingly impenetrable PDFs into a goldmine of insights.

Now, let's delve into "The Idea" behind this project, where we'll explore how this digital buddy, fueled by Langchain, simplifies your life. No more manual PDF sifting; we're here to harness the magic of technology to extract, process, and analyze text data, turning it into a formidable tool for research and data analysis. So, without further ado, let's embark on this PDF querying escapade, where Langchain is your guiding star in the world of digital documents. 🕵️‍♂️📄💼

---

## The Idea

***The idea behind this tool is to simplify the process of querying information within PDF documents. It leverages Langchain, a powerful language model, to extract keywords, phrases, and sentences from PDFs, making it an efficient digital assistant for tasks like research and data analysis. It eliminates the need for manual data extraction and transforms seemingly complex PDFs into valuable sources of insights, offering a versatile solution for working with text-based PDFs.***

## Technologies Used

Okay, let's get a bit technical first (just a smidge). We'll be harnessing the following tech wizardry:

- **Langchain**: Our trusty language model for making sense of PDFs. Langchain is a large language model (LLM) designed to comprehend and work with text-based PDFs, making it our digital detective in the PDF world.
- **OpenAI Embeddings**: The magic behind understanding text data. OpenAI Embeddings provides essential tools to convert text into numerical representations, helping us process and analyze the content.
- **PyPDF2**: The tool that helps us read the secrets hidden in PDFs. PyPDF2 is a Python library that allows us to extract text from PDF documents, turning those digital pages into readable text.
- **FAISS (Facebook AI Similarity Search)**: Our digital magnifying glass for hunting down similar text. FAISS is a library for efficient similarity searching and clustering of data, which is crucial for finding related text content.
- **Tiktoken**: It's like the clicker you use to count sheep, but for tokens. Tiktoken is a handy library for counting the number of tokens in a text string. It's our token-counter extraordinaire, helping us keep track of the language model's workload.

These technologies are the gears in our PDF-reading machine, working together to make our PDF querying adventure possible. we wil use Jupyter notebook or Colab to take our investigation ahead and make it work and later, maybe you can drop it into production for a more robust end-to-end Project or for a consistant personal assistant for your day to day work.

# Get it running on your VSCode (or any other IDE you like)
## Prerequisites

Before you begin, ensure that you have the following prerequisites installed on your system:

- [Python](https://www.python.org/) (recommended version: tokenizer is only available for 3.9+)
- [VSCode](https://code.visualstudio.com/)

## Getting Started

1. **Clone the Repository:**

   Open your terminal and run the following command to clone this repository to your local machine:

   ```shell
   git clone https://github.com/Kokit0/PDF-Extraction-and-Querying-using-LangChain-and-OpenAI-Embeddings.git
   ```

2. **Navigate to the Project Directory:**

   Change your current directory to the project folder:

   ```shell
   cd PDF-Extraction-and-Querying-using-LangChain-and-OpenAI-Embeddings
   ```

3. **Create a Virtual Environment:**

   It's a good practice to work within a virtual environment to manage this project dependencies. Create a virtual environment using `venv`:

   ```shell
   python -m venv venv
   ```

4. **Activate the Virtual Environment:**

   On macOS or Linux:

   ```shell
   source venv/bin/activate
   ```

   On Windows:

   ```shell
   .\venv\Scripts\activate
   ```

   You should now see the virtual environment name in your terminal prompt.

5. **Install Dependencies:**

   Use `pip` to install the project dependencies:

   ```shell
   pip install -r requirements.txt
   ```

6. (Optional preference) Installation and Setup for the OpenAI API key:
   
   - This step is not mandatory for running the notebook per se. To obtain an OpenAI API key, follow these instructions:
     - Sign up for an OpenAI API key at [OpenAI](https://platform.openai.com/signup).
     - Once you have an API key, got to the notebook and replace `YOUR_API_KEY_HERE` with your actual OpenAI API key. Look for the "" and simply insert.


6.a. (Optional) If you want to use OpenAI's tokenizer (available for Python 3.9+) and instead decide to not run the requirements.txt, install Tiktoken directly with bash:
   ```bash
   pip install tiktoken
   ```

7. **Open the Project in VSCode:**

   Launch VSCode and open the project folder by selecting "File" > "Open Folder" and choosing the project directory.

8. **Start Coding:**

   You're now all set to work on the project in VSCode. Open the Python files, modify the code, and run the notebooks as needed.

-------
## Feedback and Contributions

Just read the LICENCE but as a TL;DR: If you encounter issues, have suggestions, or want to contribute to this project, please open an issue or a pull request. Feel free to add your name in the contribution list if you add something cool.
Your feedback and contributions are highly appreciated!

Happy coding, nerdos! 🚀
