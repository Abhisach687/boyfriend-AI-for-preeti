1. Create a .env file in the root directory and put

```
   GOOGLE_API_KEY= "get API key from google AI studio"
   groq_api_key= "get api key from Groq website"
```

2. Create a folder named "user_data" and put pdfs with your personal information inside it.

3. Create environment using

```
   python -m venv env
   env\Scripts\activate
```

4. install requirements using

```
pip install -r requirements.txt
```

5. Finally run the app using

```
streamlit run app.py

```
