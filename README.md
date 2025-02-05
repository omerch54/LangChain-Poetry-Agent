# **LangChain Poetry Agent**  

## **Project Overview**  
This project implements a **LangChain-based AI agent** that generates a poem using the **10 most frequently occurring words** from a given document set. The agent interacts with multiple tools to extract keywords, compute word frequencies, and generate poetry using OpenAI’s **GPT-4o-mini** (or similar) model.  

By leveraging **LangChain’s agent-executor**, the system autonomously determines how to perform the task without predefined steps, making it a powerful example of **AI-driven decision-making** in natural language processing.  

---

## **Scope**  
- **Document Processing**: Extract and analyze text data from files.  
- **Keyword Extraction**: Identify the most significant words in the document.  
- **Frequency Computation**: Count occurrences and determine the top 10 keywords.  
- **Poetry Generation**: Use an LLM to generate a poem based on the extracted words.  
- **LangChain Integration**: Use **agent-executor** to structure the workflow dynamically.  

---

## **Value and Motivation**  
The project highlights the power of **LLMs and autonomous AI agents** in creative content generation. The motivation behind this project includes:  
- **Exploring multi-tool LangChain agents** for advanced AI workflows.  
- **Combining NLP techniques** (keyword extraction, frequency analysis) with **AI-generated poetry**.  
- **Encouraging agent-based autonomy** where AI figures out the execution flow rather than following a strict step-by-step procedure.  
- **Practical LangChain exposure** through real-world application.  

---

## **Technologies Used**  
- **Python**: Core programming language.  
- **LangChain**: Framework for creating AI-driven applications.  
- **OpenAI GPT-4o-mini**: LLM used for generating poetry.  
- **NLTK**: Used for text processing and keyword extraction.  

---

## **Installation and Setup**  
### **1. Install Dependencies**  
Run the following commands in a Jupyter Notebook cell:  
```python
!pip install -qU langchain-openai
!pip install nltk
```
  
### **2. Set Up OpenAI API Key**  
Ensure you have a valid OpenAI API key and configure it in your environment:  
```python
import os
os.environ["OPENAI_API_KEY"] = "your_openai_api_key"
```  

---

## **Usage**  
1. **Run the Notebook**: Execute the cells to initialize the agent and tools.  
2. **Document Analysis**: The system will read the document, extract keywords, and compute word frequencies.  
3. **Poem Generation**: The AI will compose a poem using the most frequent words.  
4. **Final Output**: The notebook will display the generated poem.  

---

## **Expected Output**  
- **Extracted Keywords**: The top 10 most frequently occurring words from the document.  
- **Generated Poem**: A creative AI-generated poem using those keywords.  
- **Verbose Execution**: Steps will be logged in verbose mode for clarity.  

---

## **Future Enhancements**  
- **Allow multiple document processing** for better keyword selection.  
- **Enhance keyword selection** by considering synonyms and stemming techniques.  
- **Introduce multiple poetry styles** based on user input.  
- **Implement user feedback loop** for improving poem quality.  
