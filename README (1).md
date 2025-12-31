
# 🧩 Multi-Agent LinkedIn Post Refiner (CrewAI)

This project is a **multi-agent AI system built with CrewAI**.  
It takes a **messy, long text** (for example, a rough LinkedIn draft) and turns it into a **short, eye-catching, specific post**.

## 🧠 What this system does
- Input: messy text written by the user
- Output: a short, eye-catching, specific post (3–6 lines, human tone, with emojis)

## 🧑‍🤝‍🧑 Agents
1. Content Extractor
2. Hook & Structure Designer
3. Post Writer & Polisher
4. Supervisor (coordinates & finalizes)

## 🧬 Tasks
- Each specialist agent has one task
- All specialists depend on Task 1 (Content Extractor)
- Supervisor checks and returns final post

## ⚙️ Tech
- Built using CrewAI
- Text-in / Text-out only
- Sequential workflow

## 🧪 Run
Call the function:
improve_messy_post("your messy text here")
