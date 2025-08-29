<div align="center">
  <br />
  <h1>AI Article Summarizer</h1>
  <p>Simplify your reading by summarizing articles with OpenAI GPT-4.</p>
  <br />
</div>

---

## 📋 Table of Contents

1. [Introduction](#introduction)  
2. [Tech Stack](#tech-stack)  
3. [Features](#features)  
4. [Quick Start](#quick-start)  
5. [Environment Variables](#environment-variables)  
6. [License](#license)  

---

## 🤖 Introduction

AI Article Summarizer is a web application that uses OpenAI's GPT-4 model to transform long articles into clear and concise summaries with a single click.

It’s perfect for anyone who wants to save time by quickly understanding the key points of any article.

---

## ⚙️ Tech Stack

- React.js  
- JavaScript  
- Tailwind CSS  
- Vite (build tool)  
- OpenAI GPT-4 API  

---

## 🔋 Features

- Clean and modern responsive UI built with Tailwind CSS  
- Summarize articles by entering their URLs  
- Save summary history locally for easy access later  
- Copy summaries to clipboard with one click  
- Built with reusable React components for maintainability  

---

## 🤸 Quick Start

### Prerequisites

- Git  
- Node.js & npm  

### Setup Steps

```bash
# Clone the repository
git clone https://github.com/Adnan-Talha/AI-Article-Summarizer.git
cd AI-Article-Summarizer

# Install dependencies
npm install

# Create a .env file
VITE_OPENAI_API_KEY=your_openai_api_key_here

//Replace your_openai_api_key_here with your OpenAI API key

# Start development server
npm run dev
