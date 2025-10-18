## Fundamental Prompting Techniques 

This guide explains the **six fundamental prompting techniques** used in AI and Large Language Models (LLMs).  
Each technique helps shape how the AI understands instructions, maintains context, and generates accurate and meaningful responses.

---

## 🔹 1. Zero-Shot Prompting

**Definition:**  
Zero-shot prompting means giving the AI a **task or question without providing any example**.  
The model relies solely on its pre-trained knowledge to generate a response.

**Example:**  
```
“Write a short poem about friendship.”
(No examples or prior context are given — the AI figures it out by itself.)
```

---

## 🔹 2. One-Shot Prompting

One-shot prompting means giving the AI one example of what you expect before asking it to perform the same task.
This helps the AI understand the format, tone, or structure of your desired output.

**Example:**
```
Q: What is the capital of France?
A: Paris

Now, Q: What is the capital of Italy?”
→ The AI will answer: “Rome.”
```

---

## 🔹 3. Few-Shot Prompting

Few-shot prompting means giving the AI a few examples (2–5 or more) to teach it a pattern or style before asking for a new result.
This technique improves accuracy because the model understands the context and pattern better.

**Example:**
```
“Q: Dog → Animal
Q: Rose → Flower
Q: Car → ?”
→ The AI learns the pattern and answers: “Vehicle.”
```

---

## 🔹4. System Prompting

System prompting involves setting rules or boundaries that define how the AI should behave throughout the conversation.
It tells the model its purpose, style, or personality before it starts responding.

**Example:**
```
“You are a polite and professional assistant who answers questions clearly and concisely.”

This system prompt makes the AI follow that tone in all responses.
```

---

## 🔹5. Role Prompting

Role prompting means assigning a specific role or identity to the AI to guide its responses.
It helps the AI adopt the tone, knowledge, and thinking style of that role.

**Example:**
```
“Act as a Python teacher and explain loops to a beginner.”

→ The AI replies like a teacher would, using simple language and examples.
```

---

## 🔹6. Contextual Prompting

Contextual prompting involves providing background information, data, or previous conversation details so the AI can give more accurate and relevant answers.
It helps the AI understand the situation or topic before generating a response.

**Example:**
```
“Based on the previous report showing a 20% drop in sales, write an email suggesting improvement strategies.”

→ The AI uses that context (20% drop) to create a meaningful response.
```

---

## What Are the Benefits of Using Prompting Techniques?

- Get **clearer, more accurate results**.  
- Improve **creativity and problem-solving**.  
- Reduce **hallucinations** (incorrect facts).  
- Save **time and effort** through structured queries.  
- Make the AI **adapt to tone, audience, and purpose**.
- Boost productivity in **education, writing, and coding.**

---

# Medium Blogs Links : 

1. 🧩 [Fundamental Prompting Techniques & The Art of Prompt Engineering](https://medium.com/@anumriz2017/fundamental-prompting-techniques-the-art-of-prompt-engineering-4c48af0aebe4)  
