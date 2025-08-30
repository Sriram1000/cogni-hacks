# Cogni-Hacks 2025
# LifeLens
Prompt: Create novel applications that make human-computer interaction more natural, accessible, and impactful

# 🌟 LifeLens – AI Future Planner for Students & Youth
# 🧩 The Problem

Students have dreams (college, career, lifestyle), but they can’t visualize how their current habits/choices map to those futures.

Guidance counselors are overworked, and tools like Naviance or Khan are too generic.

Teens want something more interactive and inspiring, not just static charts.

# 💡 The Solution

LifeLens is an AI-powered future simulator that creates a “day-in-the-life” story of your future self (5, 10, or 20 years from now) — based on your classes, interests, habits, and goals.

Simulation: “If you keep up your tennis + CS club, here’s what Future You might look like in college.”

Visualization: Diary entries, schedules, even AI-generated images of your future environment.

Actionable steps: Concrete course, extracurricular, or habit suggestions now.

It’s part coach, part mirror, part imagination machine.

# 🎭 Core Features

Future Diary Generator

User fills a short form: current grade, interests, subjects they like, career ideas, hobbies, habits (e.g., “procrastinates a lot” 😅).

AI generates a vivid day in the life narrative:
“You wake up in your dorm at Stanford. You’re double majoring in CS + Philosophy. You spend the afternoon coding a startup prototype, but tennis practice helps you destress…”

Future Slider (5y / 10y / 20y)

Slider UI to shift perspective → near-term (college), mid-term (career entry), far-term (adult lifestyle).

Each view has a diary + key stats (job, salary estimate, city, habits).

Pathway Map

Alongside the diary, a roadmap shows:

- 📚 Courses to take

- 🎓 Possible majors

- 💼 Career pathways

- 🌍 Skills & habits needed

AI links each suggestion to why it matters for their goal.

Alternate Futures (Forks)

Try different goals:
“What if I went pre-med instead of business?”
“What if I took a gap year?”

AI generates “alternate timelines” to compare.

Visuals & Moodboards (Stretch Feature)

AI generates images of your “future setting”: college campus, workplace, city vibe.

Adds emotional connection and demo appeal.

# 🏗️ Technical Architecture

Frontend: React/Next.js (web) or Expo/React Native (mobile).

Backend: FastAPI/Node.js with OpenAI API.

# Data Layer:

Embedding DB (Pinecone/Qdrant/pgvector) with career data, college majors, salary ranges, etc.

Prompt templates that pull from these to ground predictions.

# AI Integration:

GPT for narrative generation (“future diary,” roadmap text).

Retrieval-Augmented Generation (RAG) for real-world career/major info.

Optional: Stable Diffusion/DALL·E for future images.


