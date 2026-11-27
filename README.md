<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Sarthak Jain: Software Engineer at Myra AI, building GenAI products that hold up in production. 2+ years in industry, 10 open-source AI projects, 500+ users on auth flows built, 300+ LeetCode problems solved." src="assets/banner-light.svg" width="100%">
</picture>

<p>
  <a href="https://www.linkedin.com/in/sarthakjain29/"><img src="https://img.shields.io/badge/LinkedIn-sarthakjain29-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:sarthakjain3241@gmail.com"><img src="https://img.shields.io/badge/Email-say%20hi-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://leetcode.com/u/sarthak_2907/"><img src="https://img.shields.io/badge/LeetCode-300%2B%20solved-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode"></a>
  <a href="https://github.com/SarthakJain29/portfolio_v2"><img src="https://img.shields.io/badge/Portfolio-source-24292f?style=flat-square&logo=github&logoColor=white" alt="Portfolio"></a>
</p>

Full-stack engineer (TypeScript · MERN) who spends most days on the unglamorous half of GenAI: **what happens when the model is slow, rate-limited, down, or just wrong.** Every project here has a fallback chain, runs with zero API keys, and ships with tests.

**Right now at Myra AI** I'm building MCP OAuth integrations, MFA and session revocation for 500+ users, LLM model fallbacks, and an eval tool that replays conversations to see how persistent LLM memory drifts over time.

---

### 🔭 Featured work

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/SarthakJain29/MF-x-ray"><img src="assets/mf-xray.webp" alt="MF X-ray dashboard"></a>
<h4><a href="https://github.com/SarthakJain29/MF-x-ray">MF X-ray</a></h4>
See inside your mutual funds, privately. Drop in a CAMS/KFintech statement and get true XIRR, hidden fees and fund overlap. The PDF is decrypted and parsed <b>on your device</b>: no upload, no account.<br><br>
<code>Next.js</code> <code>pdf.js</code> <code>Web Workers</code> <code>PWA</code> <code>39 tests</code>
</td>
<td width="50%" valign="top">
<a href="https://github.com/SarthakJain29/News-shorts"><img src="assets/news-shorts.webp" alt="News Shorts feed"></a>
<h4><a href="https://github.com/SarthakJain29/News-shorts">News Shorts</a></h4>
The news in 60-second swipes. A pipeline clusters 30+ feeds into stories, an LLM writes an original script (an originality guard rejects copied phrasing), and the browser renders narrated, karaoke-captioned explainers.<br><br>
<code>Next.js</code> <code>Gemini TTS</code> <code>d3-geo</code> <code>GitHub Actions</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/SarthakJain29/AI-code-review-bot"><img src="assets/diffwise.webp" alt="Diffwise concept frame"></a>
<h4><a href="https://github.com/SarthakJain29/AI-code-review-bot">Diffwise Evals</a> <sub>🚧 in progress</sub></h4>
A scoreboard for AI pull-request reviewers, built <i>before</i> the bot. It mines 110 real bug-introducing PRs from Vue, Svelte, zod, axios and others (SZZ-style), then checks if a reviewer catches what maintainers later fixed.<br><br>
<code>TypeScript</code> <code>git blame / SZZ</code> <code>LLM-as-judge</code> <code>Wilson CIs</code>
</td>
<td width="50%" valign="top">
<a href="https://github.com/SarthakJain29/PDF_Chatbot"><img src="assets/folio.webp" alt="Folio PDF viewer with highlighted citation"></a>
<h4><a href="https://github.com/SarthakJain29/PDF_Chatbot">Folio</a></h4>
Chat with your PDFs and see the proof. Every claim cites the exact page, and clicking it highlights the passage. Parsing, chunking and BM25 retrieval all run in the browser.<br><br>
<code>RAG</code> <code>BM25</code> <code>IndexedDB</code> <code>Next.js</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/SarthakJain29/Similar-song-AI"><img src="assets/similar-song-ai.webp" alt="Similar Song AI results"></a>
<h4><a href="https://github.com/SarthakJain29/Similar-song-AI">Similar Song AI</a></h4>
Type a song you love and get what to play next, with <i>why</i>. Explanations are grounded in Last.fm data and validated, and anything unverifiable falls back to a deterministic sentence. Journey mode drifts from song A to B.<br><br>
<code>Last.fm</code> <code>Grounded LLM</code> <code>NDJSON streaming</code>
</td>
<td width="50%" valign="top">
<a href="https://github.com/SarthakJain29/Notes-Inbox-app"><img src="assets/notes-inbox.webp" alt="Notes Inbox Telegram bot"></a>
<h4><a href="https://github.com/SarthakJain29/Notes-Inbox-app">Notes Inbox</a></h4>
Dump anything into Telegram, and AI files it: classifies, titles, tags, dates and reminds. It also searches by meaning. If the model is down, an offline classifier saves the note so nothing is ever lost.<br><br>
<code>grammY</code> <code>SQLite</code> <code>Embeddings</code> <code>~170 tests</code>
</td>
</tr>
</table>

<details>
<summary><b>More things I've built →</b></summary>
<br>

| | Project | What it does |
|---|---|---|
| <img src="assets/scribeai.webp" width="160"> | [**ScribeAI**](https://github.com/SarthakJain29/AI-Blog-Generator) | Topic → SEO-aware blog post, streamed token by token, with live SEO and readability scoring. |
| <img src="assets/meetnote.webp" width="160"> | [**MeetNote**](https://github.com/SarthakJain29/MeetNote) | Meeting transcript → summary, decisions and an owner-assigned task board. Schema-validated output. |
| <img src="assets/quickchat.webp" width="160"> | [**QuickChat**](https://github.com/SarthakJain29/Quick-Chat) | Real-time Socket.IO chat with AI smart replies, summaries and tone rewrite. Runs with zero accounts. |
| <img src="assets/dragshift.webp" width="160"> | [**DragShift**](https://github.com/SarthakJain29/DragShift) | Drag a file, pick a slice: a radial menu that converts, compresses and merges files entirely in-browser. |
| 🎬 | [**Demo-Videos**](https://github.com/SarthakJain29/Demo-Videos) | Narrated product videos for MF X-ray and Diffwise, made in code with Remotion. |

</details>

---

### 🧭 Path so far

- **Myra AI**, Software Engineer · *Jan 2026 – now*: MCP OAuth, MFA, Atlas Search infra, LLM fallbacks and evals
- **Protiviti**, Technology Consultant · *Jun 2024 – Dec 2025*: built a role-management tool with 45% faster data retrieval and REST APIs with 30% better performance (intern → full-time)
- **Bennett University**, B.Tech CSE · *2021 – 2025*: 9.07 CGPA, Smart India Hackathon 2023 finalist

### 🛠️ Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,python,cpp,nodejs,express,react,nextjs,tailwind,mongodb,postgres,docker,aws,git&perline=14" alt="TypeScript, JavaScript, Python, C++, Node.js, Express, React, Next.js, Tailwind, MongoDB, PostgreSQL, Docker, AWS, Git">
</p>

**GenAI:** Gemini · Groq · OpenAI · Vercel AI SDK · MCP · RAG · embeddings · evals / LLM-as-judge

---

<p align="center">
  <sub>Building something with LLMs that has to work in production? <a href="mailto:sarthakjain3241@gmail.com">Let's talk.</a></sub>
</p>
