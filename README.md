# 📧 Cold Mail Generator
A cold email generator for service companies built with Groq, LangChain, and Streamlit. This tool enables users to input a company's careers page URL, extract job listings, and craft personalized cold emails. The emails are tailored to specific job descriptions and include relevant portfolio links retrieved from a vector database.

**Imagine a scenario:**

-Industry giants like Microsoft, Google, Amazon, and Tesla are investing significant time and resources into hiring, onboarding, and training Principal Software Engineers or AI Engineers.
- ValueCoders, a trusted provider of dedicated software development engineers, collaborates with leading companies like Microsoft, Google, Amazon, and Tesla.
- Now, Parvesh Aggarwal, a Business Development Executive at ValueCoders, plans to connect with Google, Amazon, and Tesla through a well-crafted cold email.
 
# DEMO
  Uploading cold-email-generator-Demo By AshwinDumane.mp4…
  
  ![Screenshot 2024-12-04 000200](https://github.com/user-attachments/assets/58ab7dd8-ffba-496c-8300-42b0ea112080)
  ![Screenshot 2024-12-04 000200](https://github.com/user-attachments/assets/26361d3b-5040-4534-bd3d-aae53c7101c4)
  ![Screenshot 2024-12-04 000200](https://github.com/user-attachments/assets/dbbd8a87-8a26-427c-805b-37254608fa15)

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

