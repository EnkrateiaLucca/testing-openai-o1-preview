# Testing OpenAI O1-preview. 

Code for the Youtube video: 

This project implements some simple testing of the new [o1-preview model from the OpenAI API](https://openai.com/index/introducing-openai-o1-preview/) including summarization, question answering, and structured output generation.

## Table of Contents

- [Testing OpenAI O1-preview.](#testing-openai-o1-preview)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Features](#features)
  - [Dependencies](#dependencies)
  - [Configuration](#configuration)
  - [Examples](#examples)
    - [Text Summarization](#text-summarization)
    - [Question Answering](#question-answering)
    - [Structured Output Generation](#structured-output-generation)
  - [License](#license)

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/EnkrateiaLucca/o1-preview-test.git
   cd o1-preview-test
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:
   ```
   export OPENAI_API_KEY='your-api-key-here'
   ```

## Usage

The main functionality is implemented in a Jupyter notebook. To use the agent:

1. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```

2. Open the `o1-preview-tests.ipynb` notebook.

3. Run the cells in order to interact with the Data Science LLM Agent.

## Features

1. **PDF Text Extraction**: Extract text from PDF files for analysis.
2. **Text Summarization**: Generate concise summaries of large text documents.
3. **Question Answering**: Generate questions and answers based on the input text.
4. **Structured Output Generation**: Convert unstructured QA data into structured format.

## Dependencies

- OpenAI API
- Jupyter Notebook
- PyPDF2
- Pydantic

For a complete list of dependencies, refer to the `requirements.txt` file.

## Configuration

The project uses the OpenAI API. Make sure to set your API key as an environment variable:


```1:11:o1-preview-tests.ipynb
in[0]: import os

os.environ['OPENAI_API_KEY'] = 'your api key'

in[1]: # QuickStart with the OpenAI API

in[2]: from openai import OpenAI

client = OpenAI()

in[3]: prompt = "Tell me what is the most complex and interesting problem that you know."
```


## Examples

### Text Summarization


```203:217:o1-preview-tests.ipynb
    print("***********")
```


### Question Answering


```623:627:o1-preview-tests.ipynb
    print("***********")
```


### Structured Output Generation


```636:662:o1-preview-tests.ipynb
    print("***********")
```


For more detailed examples and usage, refer to the `o1-preview-tests.ipynb` notebook in the repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.