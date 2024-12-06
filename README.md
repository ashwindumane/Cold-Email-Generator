# 📧 Cold Mail Generator
A cold email generator for service companies built with Groq, LangChain, and Streamlit. This tool enables users to input a company's careers page URL, extract job listings, and craft personalized cold emails. The emails are tailored to specific job descriptions and include relevant portfolio links retrieved from a vector database.

**Imagine a scenario:**

-Industry giants like Microsoft, Google, Amazon, and Tesla are investing significant time and resources into hiring, onboarding, and training Principal Software Engineers or AI Engineers.
- ValueCoders, a trusted provider of dedicated software development engineers, collaborates with leading companies like Microsoft, Google, Amazon, and Tesla.
- Now, Parvesh Aggarwal, a Business Development Executive at ValueCoders, plans to connect with Google, Amazon, and Tesla through a well-crafted cold email.
 
# DEMO

https://github.com/user-attachments/assets/d7992f86-b8da-482c-82c9-7650650e50f2

  ![Screenshot 2024-12-04 000200](https://github.com/user-attachments/assets/095d48a6-96f1-40be-9642-697fb6c91eb1)
  ![Screenshot 2024-12-04 000357](https://github.com/user-attachments/assets/d126dba5-089a-4e8a-96a8-6944acbc223a)
  ![Screenshot 2024-12-04 000459](https://github.com/user-attachments/assets/0484b08c-625a-4ec7-ae8d-d92b065961f2)
 
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

