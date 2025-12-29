AI-Powered PPTX Presentation Generator

Groq + SerpAPI + Unsplash + python-pptx + Tkinter

This project automatically generates complete, professional PowerPoint presentations using:

Groq LLM for content

SerpAPI + Unsplash for images

python-pptx for slide rendering

Tkinter for a simple desktop UI

A beginner-friendly interface that lets anyone create PPTs in seconds — perfect for students, teachers, startups, and demos.

✨ Features
1️⃣ AI-Generated Slide Content

Uses Groq LLM (Llama-3.3-70B Versatile)

Produces expert-style bullet points

No childish language

Structured, formal, business-ready content

2️⃣ Automatic Image Insertion

Fetches images via SerpAPI (Google Images)

Falls back to Unsplash when needed

Automatically scales images

Always places image on the right side

Prevents overlap with text

3️⃣ Clean Slide Design

Uses theme0.pptx as base template

Correct title slide layout

Auto-adds final “Thank You” slide

Avoids duplicate titles

Adjusted text widths for readability

4️⃣ Simple Tkinter GUI

Enter topic, number of slides, and API key

Click Generate

PPT is created automatically and saved

No manual editing required.

 
 ############################## PROJECT STRUCTURE ######################################


PPTX-Generator-Groq/
│
│── apis/
│   │── __init__.py
│   │── base_generation.py
│   │── groq_api.py
│
│── crawlers/
│   │── __init__.py
│   │── icrawlercrawler.py
│   │── serpapi_image.py
│
│── generated_ppt/
│
│── static_site/
│   │── assets/
│   │── favicon.ico
│   │── index.html
│   │── placeholder.svg
│   │── robots.txt
│
│── node_modules/        # (for static site preview / UI)
│── flask/               # deployment-related
│
│── config.json
│── generate_ppt.py
│── server.py
│── ui.py
│── utils.py
│── theme0.pptx
│
│── requirements.txt
│── Procfile
│── package.json
│── package-lock.json
│── LICENSE
│── README.md
│── .gitignore
