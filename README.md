# OrbisAI-Adaptive-Knowledge-Discovery-with-Generative-AI

OrbisAI: Adaptive Knowledge Discovery with Generative AI
***Project Overview***
Welcome to OrbisAI! This project is all about taking huge piles of unorganized text – like company documents or research papers – and turning them into a smart, connected network of information called a Knowledge Graph. Imagine asking a question about a company's projects, and instead of just searching for keywords, the system understands the relationships between projects, teams, and bugs to give you a precise answer.

OrbisAI uses powerful Deep Learning for the first pass of understanding text, and then smart Generative AI (like ChatGPT) to dig deeper, find hidden connections, and even let you ask questions in plain English. It's built to help businesses quickly find answers and make better decisions from their own data.

Why OrbisAI? (Motivation & What You'll Learn)
Building OrbisAI is a fantastic way to show off skills that top companies are desperate for. Here's why this project is a big deal:

Solving a Real-World Problem: Almost every company struggles with managing tons of text data. ***This project directly addresses that by showing how to automatically organize information and find answers, making you valuable.***
Learning Top Technologies: You'll work with Knowledge Graphs (a cutting-edge way to organize data), Deep Learning (for understanding language), and Generative AI (LLMs) (the hottest topic in AI right now). You'll also use Docker for easy setup, showing you can build modern, well-structured systems.
The "Curious Problem": Finding Hidden Links
The main challenge OrbisAI tackles is how to automatically find hidden connections within mountains of text. It's like having millions of LEGO bricks (facts) and wanting to automatically build a specific, complex structure (the answer to a question) by understanding how the bricks fit together. For example: "Which team is working on 'Project Phoenix' and is impacted by 'Bug 456'?" OrbisAI builds the connections so it can answer those tricky questions.

How OrbisAI Works (Key Features)
Here’s a simple breakdown of what OrbisAI does:

Makes Fake Data: A Python script creates realistic company documents for testing, including specific names and project details.
Smartly Reads Text:
First, it uses Deep Learning to quickly find basic "things" (like people's names or project codes).
Then, it uses Generative AI (LLMs) to read even smarter, finding more complex connections and making sure names are matched correctly (e.g., "J. Doe" and "John Doe" are the same person).
Builds a "Smart Web": All the found "things" and "connections" are put into a special database called Neo4j (a Graph Database), which is perfect for showing relationships.
Answers Questions in English:
You ask a question in plain English (e.g., "Who manages Project Titan?").
Generative AI translates your English question into a database query.
The system finds the answer in Neo4j and uses Generative AI again to give you a clear, easy-to-understand response in English.
Easy to Set Up: Everything runs easily using Docker, so you can get it working quickly on any computer.
