<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,100:1E3A8A&height=220&section=header&text=Jake%20Thomas%20Mathew&fontSize=42&fontColor=FFFFFF&animation=fadeIn&fontAlignY=35&desc=Full-Stack%20%7C%20AI%2FML%20Engineer&descAlignY=55&descSize=18" width="100%"/>

<a href="https://github.com/jake-thomas1">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=0EA5E9&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=Building+Pramana+%E2%80%94+an+explainable+multimodal+RAG+engine;Finalist+%40+Canara+Bank+HackAIthon+2026;CSE+Undergrad+%40+NIT+Surat" alt="Typing SVG" />
</a>

<br/>

[![Email](https://img.shields.io/badge/Email-mathewjake733%40gmail.com-1E3A8A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mathewjake733@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-jake--thomas1-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jake-thomas1)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Add%20your%20link-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Portfolio](https://img.shields.io/badge/Portfolio-Add%20your%20link-0EA5E9?style=for-the-badge&logo=vercel&logoColor=white)](#)

![Profile Views](https://komarev.com/ghpvc/?username=jake-thomas1&style=for-the-badge&color=1E3A8A&label=PROFILE+VIEWS)

</div>

---

### 👋 About Me

I'm a Computer Science undergraduate at **Sardar Vallabhbhai National Institute of Technology (NIT Surat)**, building production-grade, AI-integrated full-stack systems — from explainable document-intelligence engines to on-premises fraud-detection platforms for banking. I care about shipping software that is **secure, scalable, and genuinely intelligent**, not just AI-flavored.

- 🌟 Building **[Pramana](https://github.com/jake-thomas1/Pramana-Latest)** — my flagship project: an explainable, hallucination-aware multimodal RAG engine for high-stakes document QA, shipped as an MCP server
- 🎯 Also engineered **TerraShield** — an AI-driven property loan fraud detection platform for the **Canara Bank HackAIthon**, running fully on-prem with zero cloud data exposure
- 🧠 Deep interest in applied LLMs, retrieval-augmented generation, document forensics, and secure system design
- 🌱 Currently sharpening skills in **agentic protocols (MCP)**, **hybrid retrieval systems**, and **containerized ML deployment**

---

### 🏆 Recognitions & Achievements

<div align="center">

| Recognition | Program / Event | Project |
|:---:|:---|:---:|
| 🥈 **Finalist** | Canara Bank HackAIthon | TerraShield |
| 🥈 **Finalist** | Google Winter of Code | Rabuste |
| 🥈 **Finalist** | WebWonders Web Development Competition | Crossfit |
| 🥈 **Finalist** | Nexus Web Development Competition | Crossfit |
| 🥇 **School Topper — Computer Science** | Class 12, CBSE Board (97%) | — |
| 🎤 **Invited Speaker** | ACM "Hour of AI" Program | AI Fundamentals Session |
| ✅ **Selected — Internal Round** | Smart India Hackathon (SIH) | — |

</div>

## 🤝 Leadership & Campus Involvement

- 🎪 **Organizer, Mindbend 2026 (NIT Surat)** — Contributed to the planning and execution of one of Gujarat's largest techno-managerial festivals, coordinating event operations and logistics.
- 🚀 **Organizer, E-Cell Startup Event** — Coordinated teams, scheduling, and event execution for entrepreneurship-focused initiatives.
- 💻 **Executive Member, ACM Student Chapter (SVNIT)** — Contribute to technical events, coding initiatives, and student engagement activities.
- 🏛️ **Departmental Cell Representative, NEXUS (CSE)** — Represent the Computer Science department in organizing technical events, workshops, and student-driven initiatives.
- 🏅 **Member, Sports Council** — Assisted in organizing and managing inter-college sports tournaments and campus sporting events.

---

### 🌟 Main Project

<table>
<tr>
<td width="100%" valign="top">

**🔎 Pramana** — Explainable Multimodal RAG for High-Stakes Document Intelligence

A hallucination-aware RAG chatbot built for documents where being *wrong* isn't an option — board reports, financial decks, and visually dense PDFs where the answer might be buried in a chart, table, or flowchart instead of plain text.

- Built a **3-step verification pipeline with RAPTOR indexing** so answers are checked before they're trusted, not just generated
- Engineered a **multimodal ingestion pipeline** — native text extraction, **Mistral OCR** for tables and layout-heavy pages, and **Gemini / NVIDIA Phi-4 vision-language models** for chart, diagram, and flowchart understanding
- Combined **BM25, keyword search, and dense FAISS retrieval** fused with Reciprocal Rank Fusion, on top of **NVIDIA nv-embed-v1** embeddings
- Added **CRAG (Corrective RAG) relevance grading** before generation, plus a final page-image VLM fallback so nothing gets missed
- Every answer ships with **inline, page-and-chunk-level citations** (e.g. `[p3:c12]`) tracing straight back to the source
- Shipped the whole system as an **MCP (Model Context Protocol) server via FastMCP** — deployed and callable by any MCP-compatible AI host
- **Fully containerized** with a multi-stage Docker build and Compose orchestration for reproducible, one-command deployment

`Python` `FastAPI` `Next.js` `Google Gemini` `NVIDIA` `Mistral AI` `FAISS` `RAPTOR` `MCP` `Docker`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jake-thomas1/Pramana-Latest)
[![Live MCP Server](https://img.shields.io/badge/Live_MCP_Server-0EA5E9?style=for-the-badge&logo=lightning&logoColor=white)](https://pramana.fastmcp.app/mcp)

</td>
</tr>
</table>

---

### 📦 Other Projects

<table>
<tr>
<td width="50%" valign="top">

**🏦 TerraShield**
*AI Property Loan Fraud Intelligence Platform*
**Canara Bank HackAIthon Finalist**

An on-premises fraud-detection engine that flags forged property and loan documents in real time — built for a banking environment where data never leaves the building.

- Orchestrated a fully local AI pipeline using **Qwen2.5 via Ollama** for document reasoning, with zero external API calls
- Built forensic detection using **OpenCV Error Level Analysis (ELA)** and **Tesseract OCR** to catch tampered documents
- Extracted structured entities from unstructured loan paperwork with **spaCy NER**
- Integrated **CERSAI** connectors for registry cross-verification
- Designed the system end-to-end for **zero-cloud data exposure**, a hard requirement in banking compliance

`Next.js` `FastAPI` `Qwen2.5` `Ollama` `OpenCV` `Tesseract OCR` `spaCy`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jake-thomas1)

</td>
<td width="50%" valign="top">

**☕ Rabuste**
*Full-Stack Coffee Commerce Platform*
**Google Winter of Code Finalist**

A full-stack lifestyle platform connecting customers, artists, and admins around a single coffee marketplace.

- Engineered an **AI Barista** using the Google Gemini API to generate personalized coffee recommendations
- Built real-time order notifications with **Socket.io**
- Shipped an **Art & Coffee marketplace** for curated artist submissions and purchases
- Delivered a complete MERN-stack product with secure authentication end-to-end

`React` `Node.js` `MongoDB` `Gemini AI` `Socket.io`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jake-thomas1)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🏋️ Crossfit**
*Sports Hub & E-commerce Platform*
**WebWonders & Nexus Finalist**

A role-based platform serving fans and clubs, combining community features with a full e-commerce checkout pipeline.

- Implemented secure, role-based access with **JWT authentication**
- Built a complete e-commerce flow with cart and atomic checkout operations
- Integrated the **Razorpay** payment gateway with server-side verification
- Optimized the backend on **MongoDB indexing**, cutting load time to under **800ms**

`Node.js` `Express.js` `MongoDB` `Razorpay API`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jake-thomas1)

</td>
<td width="50%" valign="top">

**🎓 ProtoVolt**
*Virtual Classroom & Circuit Simulation Platform*

A virtual classroom built for teachers and students, combining assignment management with an interactive circuit simulator.

- Developed role-based authentication tailored to teacher and student workflows
- Designed circuit simulation modules following **OOP principles**
- Built an end-to-end assignment management system

`MongoDB` `Express.js` `React.js` `Node.js`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jake-thomas1)

</td>
</tr>
</table>

> 💡 The four repos above still link to placeholders — swap in their actual GitHub URLs.

---

### 🛠️ Tech Stack

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Shadcn UI](https://img.shields.io/badge/Shadcn_UI-000000?style=for-the-badge&logo=shadcnui&logoColor=white)

**Backend & Databases**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**AI / ML**

![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Mistral AI](https://img.shields.io/badge/Mistral_AI-FA520F?style=for-the-badge&logoColor=white)
![Qwen2.5](https://img.shields.io/badge/Qwen2.5-FF6A00?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white)
![Tesseract OCR](https://img.shields.io/badge/Tesseract_OCR-4B4B4B?style=for-the-badge&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-3B5998?style=for-the-badge&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-0EA5E9?style=for-the-badge&logoColor=white)

**Infra & Deployment**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Hub](https://img.shields.io/badge/Docker_Hub-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-0C2451?style=for-the-badge&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)

---

### 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=jake-thomas1&show_icons=true&count_private=true&hide_border=true&bg_color=FFFFFF&title_color=1E3A8A&text_color=334155&icon_color=0EA5E9&border_color=E2E8F0" width="48%"/>
<img src="https://github-readme-streak-stats.demolab.com?user=jake-thomas1&hide_border=true&background=FFFFFF&stroke=E2E8F0&ring=0EA5E9&fire=1E3A8A&currStreakLabel=1E3A8A&sideLabels=334155&currStreakNum=1E3A8A&sideNums=334155&dates=94A3B8" width="48%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jake-thomas1&layout=compact&hide_border=true&bg_color=FFFFFF&title_color=1E3A8A&text_color=334155&border_color=E2E8F0" width="48%"/>
<img src="https://github-profile-trophy.vercel.app/?username=jake-thomas1&theme=flat&no-frame=true&row=2&column=4&margin-w=8&margin-h=8" width="48%"/>

</div>

---

<div align="center">

### 📫 Let's Connect

Open to internships, hackathon teams, and collaborative builds in AI/ML and full-stack engineering.

[![Email](https://img.shields.io/badge/Email_Me-1E3A8A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mathewjake733@gmail.com)
[![GitHub](https://img.shields.io/badge/Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jake-thomas1)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E3A8A,100:0F172A&height=120&section=footer" width="100%"/>

</div>
