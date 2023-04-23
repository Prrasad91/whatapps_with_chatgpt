# whatapps_with_chatgpt


PostgreSQL installed on your machine.
A Twilio account set up. If you don't have one, you can create a free account here.
An OpenAI API key to access ChatGPT.
A smartphone with WhatsApp installed to test your AI chatbot.
A basic understanding of FastAPI, a modern, fast (high-performance), web framework for building APIs with Python 3.6+.
A basic understanding of what an ORM is. If you are not familiar with ORM, we recommend you to read this wiki page to get an idea of what it is and how it works.


Requirements.txt file
    fastapi: A package for FastAPI, a modern web framework for building APIs with Python 3.7+ based on standard Python type hints. It's designed to be easy to use, fast, and to provide automatic validation of request and response data.
    uvicorn: A package for Uvicorn, a fast ASGI server implementation, using the websockets library for long-polling connections, and based on uvloop and httptools.
    
    twilio: A Python helper library for Twilio, a cloud communications platform that allows software developers to programmatically make and receive phone calls, send and receive text messages, and perform other communication functions using its web service APIs.
    
    openai: A Python client for OpenAI, a research company that focuses on developing and advancing artificial intelligence in a way that is safe and beneficial for humanity. OpenAI offers various AI models, including the GPT 3.5 turbo model, which is used in this tutorial to power the chatbot.
    python-decouple: A library for separating the settings of your Python application from the source code. It allows you to store your settings in an environment file, instead of hardcoding them into your code.
    
    sqlalchemy: A package for SQLAlchemy, a Python SQL toolkit and Object-Relational Mapping (ORM) library. It provides a set of high-level APIs for connecting to relational databases, executing SQL queries, and mapping database tables to Python classes.
    
    psycopg2-binary: A Python package that provides a PostgreSQL database adapter for the Python programming language.
    
    python-multipart: A library that allows you to parse multipart form data in Python, which is commonly used to handle form submissions that contain files such as images or videos. In the case of this tutorial, it will be used to handle form data from the user's input through the WhatsApp chatbot.
    
    pyngrok: A Python wrapper for ngrok, a tool that allows you to expose a web server running on your local machine to the internet. You'll use it to test your Twilio webhook while you send WhatsApp messages.
    
    
