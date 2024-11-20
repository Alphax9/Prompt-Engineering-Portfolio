# Prompt-Engineering-Portfolio
# Prompt Engineering Portfolio  

Welcome to my Prompt Engineering Portfolio! This repository showcases my expertise in crafting effective prompts for various natural language processing (NLP) tasks using large language models like OpenAI's GPT.  

## 🧑‍💻 About Me  
I am Alphaxard Kibagendi, a skilled prompt engineer with a background in Healthcare although my propmts are general. I specialize in creating optimized prompts for applications such as text generation, data extraction, chatbot development, and more. My goal is to bridge the gap between user intent and AI performance through precise prompt design.  
import openai  

# Define your OpenAI API key  
openai.api_key = "your-api-key"  

# Prompt definition  
prompt = """Craft a campaign slogan for a candidate running for president of the Pharmaceutical Society of Kenya (PSK) focusing on education, policy advocacy, innovation, and collaboration."""  

# Generate output  
response = openai.Completion.create(  
    engine="text-davinci-003",  
    prompt=prompt,  
    max_tokens=50  
)  

# Print generated slogans  
print("Generated Slogan:", response.choices[0].text.strip())  
