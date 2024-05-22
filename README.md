# Document Analyzer using Google Gemma and Groq 

This RAG application allows you upload any pdf file and the Gemma LLM would analyse the pdf, act as you personal assistant to answer various
questions with regard to the pdf.

## DEMO

https://github.com/saketh1999/gemma_pfd_rag/assets/48793201/373f0384-6d87-46e5-aeba-aa4462d668c9


## More About Gemma
Gemma is a family of lightweight, open models built from the research and technology that Google used to create the Gemini models.
Learn more on [Gemma](https://ai.google.dev/gemma).

## What is Groq?
Groq is on a mission to set the standard for GenAI inference speed, helping real-time AI applications come to life today.
Learn about Groq and checkout what LPU's are in Groq [Here](https://wow.groq.com/why-groq/).

## RAG : Retrieval-Augmented Generation
It's a technique used to improve the accuracy and reliability of large language models (LLMs).

### How it works : 
1. Normally, LLMs are trained on massive amounts of data, and they use that data to respond to your questions and requests. However, this data might not always be up-to-date or accurate.

2. RAG addresses this by incorporating an information retrieval component. This component searches external sources, like a trusted knowledge base, to find relevant information for your specific query.

3. Once the information is retrieved, it's fed to the LLM along with your original question. With this extra context, the LLM can generate a more informative and accurate response.

#### RAG essentially enhances LLMs in two key ways:

Accuracy: By grounding the LLM in real-world facts, RAG helps to ensure that the information it generates is truthful and reliable.

Transparency: RAG can sometimes reveal the sources of the information used by the LLM, which increases transparency and allows you to verify the information yourself.

## Technologies

1. Streamlit
2. Gemma
3. LangChain
4. GroqAPI   

## Requirements

1. Follow the instructions on Google AI Studio [setup page](https://makersuite.google.com/app/apikey) to obtain an API key.
2. Follow the instruction on [Groq developer studio](https://console.groq.com/playground) to obatin your Groq API key.
3. Add your API Key in this format in the .env file .

```txt
GOOGLE_API_KEY="<insert you key here>"
GROQ_API_KEY = "<insert you key here>"
```
