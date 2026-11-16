# Stefan Menne – Softwareentwickler & KI-Engineer (GenAI / LLMs)

Diplom-Informatiker (Universität Bonn) mit über 24 Jahren Erfahrung in der Automotive-Softwareentwicklung bei Continental / AUMOVIO.
Meine Stationen: Grafik- und Kartensoftware, Bootloader-Entwicklung in C, dann zehn Jahre Integrationstest und CI/CD für Embedded-Plattformen.
Seit 2025 arbeite ich mit **generativer KI und LLMs**: als NVIDIA Certified Professional, mit eigener KI-Hardware (NVIDIA GB10 Grace Blackwell) und mit **Claude Code** als täglichem Entwicklungswerkzeug.

**Ich suche eine Stelle als KI-Entwickler, Softwareentwickler oder Testingenieur.**

---

## 🔧 Schwerpunkte

- **Agentic Coding mit Claude Code:** seit März 2026 täglich im Einsatz. Ich schreibe eigene Skills, MCP-Server und Claude-Code-Plugins und steuere darüber auch meine lokalen KI-Modelle.
- **Generative KI / LLMs:** selbst gehostete Modelle für Bild, Video, Sprache und 3D auf NVIDIA GB10, dazu vLLM, Ollama, llama.cpp und Docker
- **Softwareentwicklung:** C# / .NET, Python, C/C++, JavaScript, Desktop-Anwendungen (WinForms, Avalonia)
- **Test & CI/CD:** automatisierte Tests (pytest, Playwright), Jenkins, GitHub Actions, Docker, Git, Requirements-Tracing (DOORS, Jira), Automotive SPICE
- **Embedded:** Embedded Linux, Green Hills INTEGRITY, Android, Bare Metal, Bootloader / Flash-Update

## 🚀 Projekte

| Projekt | Beschreibung | Technik |
|---|---|---|
| [**gb10-assets**](https://github.com/StefanMenne/gb10-assets) | Selbst gehosteter Server, der einen NVIDIA-GB10-Rechner (DGX Spark, ASUS Ascent GX10) im Netzwerk als Generator für Bilder, Videos, Sprache und 3D-Modelle bereitstellt. Er nimmt Jobs in eine Warteschlange auf und hält immer nur ein Modell im Speicher. Ansprechbar per REST-API, MCP-Server oder als Claude-Code-Plugin, dessen Skills z. B. aus einer Beschreibung eine animierte Spielfigur erzeugen. Ein Web-Dashboard zeigt GPU, Speicher und Jobs. | Python, FastAPI, Docker, CUDA, MCP, FLUX.2, Qwen3-TTS, LTX-2.5, Blender |
| [**smChess3d**](https://github.com/StefanMenne/smChess3d) | 3D-Schach im Browser. Die zwölf animierten Figuren habe ich komplett lokal mit generativer KI erzeugt (FLUX.2 → TRELLIS.2 → Blender) und die Pipeline über Claude Code gesteuert. | JavaScript, Three.js, Playwright |
| [**smTablebases**](https://github.com/StefanMenne/smTablebases) | Generator für Schach-Endspieldatenbanken mit Multithreading und eigener LZMA-basierter Kompression. 2026 auf .NET 10 portiert, die Oberfläche läuft jetzt mit Avalonia auf mehreren Plattformen. | C#, .NET 10, Avalonia |
| [**kyphi**](https://github.com/StefanMenne/kyphi) | 2D-Point-and-Click-Adventure (in Entwicklung) | Godot, GDScript |

### Weitere Projekte (nicht öffentlich)

- **smTrace:** Terminal- und Trace-Tool für serielle Schnittstellen, das große Datenmengen verarbeitet. Ich habe es 20 Jahre lang allein entwickelt und gepflegt. Es läuft weltweit an mehreren Continental-Standorten im Produktivbetrieb.
- **stChess:** Turnierverwaltung für Schachvereine. 1999 in C++ entstanden, 2004 nach C# portiert, mehrere Jahre kommerziell verkauft und heute Freeware.
- **CI/CD-Toolchain für Embedded-Bootloader-Tests:** durchgängige Pipeline mit Docker, Python, Jenkins, Git, Jira und IBM DOORS.

## 🎓 Zertifikate

**Zertifizierungen**

- NVIDIA Certified Professional – Generative AI and LLMs (NCP-GENL, 2026)
- NVIDIA Certified Associate – Generative AI and LLMs (NCA-GENL, 2026)
- ISTQB Certified Tester Foundation Level (2026)
- SAFe for Teams (5.1) – Scaled Agile

**Coursera** – 4 Abschlüsse mit 32 Kursen (06/2025 – 03/2026)

| Abschluss | Anbieter | Umfang | Datum |
|---|---|---|---|
| [Generative AI Engineering – Professional Certificate](https://www.coursera.org/account/accomplishments/professional-cert/MW5U892WIZ29) | IBM | 16 Kurse | 11/2025 |
| [AI Agent Developer – Specialization](https://www.coursera.org/account/accomplishments/specialization/E4NXBWHUBM60) | Vanderbilt University | 6 Kurse | 01/2026 |
| [Exam Prep NCA-GENL – Specialization](https://www.coursera.org/account/accomplishments/specialization/ON3AP2TNBOLC) (Vorbereitungskurs) | Whizlabs | 6 Kurse | 03/2026 |
| [Introduction to Generative AI Learning Path – Specialization](https://www.coursera.org/account/accomplishments/specialization/IPE77KKADWKZ) | Google Cloud | 4 Kurse | 06/2025 |

Schwerpunkte: LLM Fine-Tuning, RAG / LangChain, Agentic AI, Transformer, GenAI-Anwendungen in Python, Deployment, Responsible AI

<details>
<summary>Alle Einzelkurse anzeigen</summary>

**IBM Generative AI Engineering** (06/2025 – 11/2025)
AI Foundations · Generative AI Essentials · Prompt Engineering for Generative AI · Python for Data Science & AI · Build & Deploy AI Applications with Python & Flask · Building Generative AI-Powered Applications with Python · Data Analysis with Python · Machine Learning with Python · Deep Learning & Neural Networks with Keras · Generative AI and LLMs: Architecture and Data Preparation · Gen AI Foundational Models for NLP · Generative AI Language Modeling with Transformers · Generative AI Engineering and Fine-Tuning Transformers · Generative AI Advanced Fine-Tuning for LLMs · Fundamentals of AI Agents Using RAG and LangChain · Project: Generative AI Applications with RAG and LangChain

**AI Agent Developer – Vanderbilt** (11/2025 – 01/2026)
AI Agents and Agentic AI with Python & Generative AI · AI Agents and Agentic AI Architecture in Python · OpenAI GPTs: Creating Your Own Custom AI Assistants · Prompt Engineering for ChatGPT · ChatGPT Advanced Data Analysis · Trustworthy Generative AI

**Exam Prep NCA-GENL – Whizlabs** (02/2026 – 03/2026)
Fundamentals of Machine Learning · Fundamentals of Deep Learning · Fundamentals of NLP and Transformers · Large Language Models and Generative AI Deployment · Prompt Engineering and Data Analysis · LLM Experimentation, Deployment, and Ethical AI

**Introduction to Generative AI – Google Cloud** (06/2025)
Introduction to Generative AI · Introduction to Large Language Models · Introduction to Responsible AI · Responsible AI: Applying AI Principles with Google Cloud

</details>

## 📫 Kontakt

- LinkedIn: [linkedin.com/in/stefan-menne](https://www.linkedin.com/in/stefan-menne/)
