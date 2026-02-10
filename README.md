# BFHL API

**Author:** Vanshika Jindal  
**Email:** vanshika0913.be23@chitkara.edu.i.n 

This project implements two REST APIs using Node.js:  

1. `POST /bfhl` – Performs Fibonacci, Prime, LCM, HCF calculations or answers AI questions.  
2. `GET /health` – Checks API health.  

The project includes **AI integration** using OpenAI / Google Gemini / Anthropic (replace API key in `.env`). 

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/07Vanshikajindal/bfhl-api.git
cd bfhl-api
npm install
AI_API_KEY=YOUR_API_KEY_HERE
npm start
Performs one of the following based on the request key:

Key	Input Type	Output Type
fibonacci	Integer	Fibonacci series array
prime	Integer array	Prime numbers array
lcm	Integer array	Single LCM value
hcf	Integer array	Single HCF value
AI	String	Single-word AI response
