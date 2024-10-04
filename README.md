# PdfQuery
LangChain is a framework that allows developers to create agents capable of reasoning about issues and breaking them down into smaller sub-tasks. 
By building intermediary stages and chaining complex commands together, you can add context and memory to completions using LangChain.

The first step in PDFQuery is to download and import the models. 
Later we can load any pdf using PyMuPDFLoader() function. 
On loading the pdf, the text in it is split into smaller chucks making it easier for the machine to comprehend.
Next, we use Hugging Face Transformers for the language model and Sentence Transformers to generate embeddings for your text chunks. 
Then, we create a RetrievalQA chain to query the documents. RetrievalQA chain combines retrieval with the LLM to provide answers to your questions.

![image](https://github.com/user-attachments/assets/a0313cee-e4c4-49f6-b8e3-879295cde33e)
