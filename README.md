<!-- ------------- BEGIN README ------------- -->

<!-- ------------- CSS for animations, hover-spin & floating cards ------------- -->
<style>
/* Spin badges on hover */
a[href*="shields.io"] img {
  transition: transform .4s;
}
a[href*="shields.io"]:hover img {
  transform: rotate(360deg);
}

/* Gradient animated header text */
@keyframes gradientText {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
h1 {
  background: linear-gradient(270deg, #ff7f50, #00ffff, #ff69b4, #7fff00);
  background-size: 800% 800%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: gradientText 8s ease infinite;
}

/* Floating animation for project cards */
.project-card {
  transition: transform 0.3s, box-shadow 0.3s;
  border-radius: 12px;
  padding: 1.2rem;
  margin: 1rem 0;
  background: #0b111f;
  color: #fff;
  box-shadow: 0px 4px 15px rgba(0,0,0,0.3);
}
.project-card:hover {
  transform: translateY(-10px);
  box-shadow: 0px 8px 30px rgba(0,0,0,0.6);
}

/* Typing effect for summary and projects */
.typing {
  border-right: .1em solid #fff;
  white-space: nowrap;
  overflow: hidden;
  display: inline-block;
  animation: typing 3s steps(80, end), blink-caret .75s step-end infinite;
}
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}
@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: #fff; }
}
</style>

<h1 align="center">🌟 Shivam Bahuguna – Data Scientist & AI MLOps Engineer</h1>

<p align="center"><em class="typing">Turning data into a moving story – one line of code at a time.</em></p>

---

### 📫 Contact
- 📧 Email: shivambahuguna88@gmail.com  
- ✈️ Singapore: +65 87101444  
- 🇮🇳 India: +91‑9719508006  
- 💼 LinkedIn: [linkedin.com/in/shivambahuguna88/](https://www.linkedin.com/in/shivambahuguna88/)  
- 🎨 Portfolio: [shivam26102022.github.io](https://shivam26102022.github.io/Shivam-Portfolio/index.html)  
- 🐙 GitHub: [Shivam26102022](https://github.com/Shivam26102022)

---

## 🎯 Quick Stats

<p align="center">
<a href="#"><img src="https://img.shields.io/badge/Python-3.9%2C3.10-blue?style=for-the-badge&logo=python&logoColor=white"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure%20%26%20AWS-Cloud-2ea44f?style=for-the-badge&logo=azure&logoColor=white"></a>
<a href="#"><img src="https://img.shields.io/badge/Generative%20AI-🤖%20LLaMa%20%26%20GPT-ff7f00?style=for-the-badge"></a>
<a href="#"><img src="https://img.shields.io/badge/LangChain-🧠%20RAG-ff9800?style=for-the-badge"></a>
<a href="#"><img src="https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-7057ff?style=for-the-badge"></a>
</p>

---

## 🛠️ Tech Stack

```bash
# Languages
Python 3.9/3.10 • SQL • Bash

# Frameworks & Libraries
FastAPI • React • Plotly Dash • LangChain • Azure OpenAI

# Cloud & MLOps
Azure • AWS • GCP (certified) • Azure ML Pipelines • GitHub Actions • Docker • Terraform

# Data Engineering
Snowflake • Snowpark • Pandas‑AI • Pandas • ETL • Mallion
