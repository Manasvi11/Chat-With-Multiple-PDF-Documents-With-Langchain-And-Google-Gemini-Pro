# Chat-With-Multiple-PDF-Documents-With-Langchain-And-Google-Gemini-Pro

### 1. Create an Virtual Environment (VS Code)
   
   Run the below Commands
```
conda create -p venv python==3.10
```
``` 
conda activate venv/
 ```
 ### 2 . Create an environment variable and paste Google_API_Key 

 

### 3 . Libraries used are

google-generativeai                         - For Gemini-pro

langchain                                          - To read Pdf

langchain_google_genai- with help of langchain you can access the API's of google genAI

faiss-cpu            - (Facebook AI Similarity Search) quickly search for embeddings. You can also use GPU if you have more files / Parallel Processing 

PyPDF2              - To read Pdf

python-dotenv       - To load all environment variables

streamlit           - framework to build and share ML and data science web apps

```
pip install -r requirements.txt
```
 
### 4. Run Code
```
streamlit run pdfapp.py
```

![image](https://github.com/Manasvi11/Chat-With-Multiple-PDF-Documents-With-Langchain-And-Google-Gemini-Pro/assets/71812747/9ffed0c2-3b7e-4e4b-82af-3e74ed86fab5)
