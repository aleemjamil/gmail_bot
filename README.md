# Email-Based Chatbot using OpenAI

This project creates a chatbot that interacts via email, powered by OpenAI's GPT-3.5 model. The chatbot can receive queries via email, process them using OpenAI's model, and respond appropriately. Additionally, it can send responses back to the user via email.

### Video Demo

![](./RecordedVideo__4_.webm)


# Problem Statement:

Inefficient communication methods hinder seamless interaction between users and automated systems. Traditional email lacks interactivity and responsiveness expected in modern conversational systems. Our project addresses this gap by developing an Email-Based Chatbot powered by OpenAI's GPT-3.5 model, aiming to enhance communication efficiency and user experience by enabling natural language conversations via email.


# Installation

### Usage
- Set up your email credentials
- OpenAI API key in the main.py file.
- Customize the answer() and openai_res() functions in main.py according to your specific use case.
### Run the script:
- Install Requirements
- Run **python main.py**

The script will start monitoring your email inbox for incoming messages. It will process each message using the OpenAI model and send the response back to the sender.

## Requirements
- Python 3.x
- openai
- imaplib
- email
- time
- smtplib
- from Python Standard Library openai library for interacting with OpenAI's GPT-3.5 model

# Get Strated

## Configuration
- Update OPENAI_API_KEY, email_, and password variables in main.py with your OpenAI API key and email credentials.
- Modify the answer() and openai_res() functions as needed to tailor the bot's responses to your specific requirements.

## Run

To run this project, you need to have Python installed on your system. Additionally, install the required dependencies by running:
```
pip install -r requirements.txt
```
```
python app.py
```

# Conclusion
In summary, this project introduces an Email-Based Chatbot powered by OpenAI's GPT-3.5 model. It improves communication efficiency by enabling natural language conversations via email. The chatbot receives queries, processes them using the OpenAI model, and responds accordingly. Key features include seamless integration with email systems, customizable responses, and easy setup. The project's team, led by Asma Shoukat, developed the solution to demonstrate the capabilities of GPT-3.5 in email-based interactions.


## License
This project is licensed under the ML1
