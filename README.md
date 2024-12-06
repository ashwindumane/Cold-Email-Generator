# 📧 Cold Mail Generator
A cold email generator for service companies built with Groq, LangChain, and Streamlit. This tool enables users to input a company's careers page URL, extract job listings, and craft personalized cold emails. The emails are tailored to specific job descriptions and include relevant portfolio links retrieved from a vector database.

**Imagine a scenario:**

-Industry giants like Microsoft, Google, Amazon, and Tesla are investing significant time and resources into hiring, onboarding, and training Principal Software Engineers or AI Engineers.
- ValueCoders, a trusted provider of dedicated software development engineers, collaborates with leading companies like Microsoft, Google, Amazon, and Tesla.
- Now, Parvesh Aggarwal, a Business Development Executive at ValueCoders, plans to connect with Google, Amazon, and Tesla through a well-crafted cold email.
 
# DEMO

https://github.com/user-attachments/assets/d7992f86-b8da-482c-82c9-7650650e50f2

# Tech Architecture
![image](https://github.com/user-attachments/assets/6f4cab76-562f-4ef2-9a53-1d8962c1b5b1)

### Tools and Technologies:

1. **Llama 3.1**: Open-source LLM for fast response and generative AI tasks.
2. **ChromaDB**: Vector store for creating, manipulating, and retrieving collections using Python.
3. **LangChain**: Framework for prompt engineering and seamless integration of LLMs.
4. **Streamlit**: For quick UI prototyping of the generator.
5. **Web B Loader**: For web scraping and extracting relevant data.
6. **Prompt Engineering**: Crafting templates and data extraction for email generation.
7. **Secure Practices**: Storing API keys securely and separately from the codebase.  

### Functionality Highlights:
- Automated generation of cold emails based on job posts or skill requirements.
- End-to-end automation of the job application process using Gen AI.

## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 

2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ``` 
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```

