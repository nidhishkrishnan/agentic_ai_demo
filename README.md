# CrewAI Classroom Demo 🤖📚

Welcome to the **CrewAI Classroom Demo**! This project is designed to show you how multiple AI "agents" can work together to solve a problem, just like a team of students in a classroom.

## 🌟 What is this?

Imagine you have a group project to write a short paragraph about **Photosynthesis**. Instead of doing it all yourself, you have a team:

1.  **The Researcher** 🕵️‍♂️: Looks up facts.
2.  **The Writer** ✍️: Takes those facts and writes a story.
3.  **The Editor** 📝: Checks the story to make sure it's perfect.

This program creates these three "AI Agents" on your computer and makes them talk to each other to finish this task automatically!

## 🧠 How it Works (The Flow)

1.  **Start**: The "Manager" (Crew) gives the topic "Photosynthesis" to the team.
2.  **Step 1 (Research)**: The **Researcher** agent wakes up. It uses its AI brain (Ollama) to find 3 simple facts about photosynthesis. It passes these facts to the next person.
3.  **Step 2 (Write)**: The **Writer** agent takes the list of facts. It writes a fun, easy-to-read paragraph using them. It passes this draft to the next person.
4.  **Step 3 (Edit)**: The **Editor** agent reads the draft. It fixes any hard words or grammar mistakes to make it perfect for students.
5.  **Finish**: The final paragraph is printed on your screen!

## 🛠️ Setup Instructions

### 1. Install Ollama (The AI Brain)
This project runs **locally** on your computer using Ollama. This means it's free and private!

1.  Download and install Ollama from [ollama.com](https://ollama.com).
2.  Open your terminal (Command Prompt or Terminal).
3.  Download the "brain" (model) we will use by typing:
    ```bash
    ollama pull llama3.2:1b
    ```
    *(Note: This is a small, fast model. You can also use `llama3` for smarter results)*.

### 2. Install Python Requirements
Make sure you have Python installed. Then, install the necessary tools:

```bash
pip install -r requirements.txt
```

## 🚀 How to Run

1.  Open your terminal in this folder.
2.  Run the script:
    ```bash
    python main.py
    ```
3.  Watch the console! You will see the agents "thinking" and talking to each other.

## 🧪 Experiment!

Want to change the topic? Open `main.py` and change line 57:

```python
topic = "The Solar System"
```

Run it again and see what the agents create!
