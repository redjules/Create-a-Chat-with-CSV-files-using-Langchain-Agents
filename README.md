# Create-a-Chat-with-CSV-files-using-Langchain-Agents


This is a Python application that enables you to load a CSV file and ask questions about its contents using natural language. The application leverages Language Models (LLMs) to generate responses based on the CSV data. The LLM will only provide answers related to the information present in the CSV.

## How it works

The application reads the CSV file and processes the data. It utilizes OpenAI LLMs alongside with Langchain Agents in order to answer your questions. The CSV agent then uses tools to find solutions to your questions and generates an appropriate response with the help of a LLM.

The application employs Streamlit to create the graphical user interface (GUI) and utilizes Langchain to interact with the LLM.

## Installation

To install the repository, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies by running the following command:

   ```
   pip install -r requirements.txt
   ```

3. Additionally, you need to obtain an OpenAI API key and add it to the `.env` file.

## Usage

To use the application, execute the `main.py` file using the Streamlit CLI. Make sure you have Streamlit installed before running the application. Run the following command in your terminal:

```
streamlit run main.py
```

## Results

<img width="560" alt="Screenshot 2024-03-09 at 08 05 58" src="https://github.com/redjules/Create-a-Chat-with-CSV-files-using-Langchain-Agents/assets/106017493/3483580d-c2cb-443d-bbca-55d5404d35d4">

In the Terminal we see the train of actions of the AgentExecutor:

<img width="462" alt="Screenshot 2024-03-09 at 08 05 20" src="https://github.com/redjules/Create-a-Chat-with-CSV-files-using-Langchain-Agents/assets/106017493/295eadff-1706-474b-b794-e14cca31bc37">
