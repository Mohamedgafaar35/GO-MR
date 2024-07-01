
import google.generativeai as genai
import os

genai.configure(api_key=os.environ['API_KEY'])

model = genai.GenerativeModel(name='gemini-1.5-flash')
response = model.generate_content('Teach me about how an LLM works')

print(response.text)
