# PneumoAI

> [!NOTE]
> In Bearbeitung ...

# Module
`Asthma` `COPD` `ILD` `BC` `Allergologie` `Schlafmedizin` `TBC` `Bronchiektasen` `PAH` `LAE` `Pneumonie`

- [ ] 🔴 **Asthma**: in Bearbeitung
- [ ] COPD: next
- [ ] ILD: next
- [ ] Allergologie: next
- [ ] Schlafmedizin: next
- [ ] Bronchiektasen / TBC: next
- [ ] PAH: next
- [ ] BC: next

# Architektur
PneumoAI
- Frontend (docker container)
  - Typescript / HTML / CSS
  - UI: React / Shadcn UI / Tailwind
  - State management: Zustand / Tanstack Query
  - Libs: React Hook Forms, Zod
- Backend (docker container)
  - Typescript
  - Express + middleware(s)
  - ORM: Prisma
  - DB: SQLite + Postgres (vector embeddings)
  - Python backend für Transcription / speaker diarezation (docker container)
- AI
  - Ollama (local (Mac) für GPU acceleration) oder 
  - Ollama (docker container (Windows))
    - Chat model: Z. B. LLAMA 3.3
    - Embeding model: x
  - Local Whisper (docker container)
- App
  - Typescript / HTML / CSS
  - React native / Zustand / Zod 

# Sponsoren

- Asthma:
- COPD:
- ILD:
- Allergologie:
- Schlafmedizin:
- Bronchiektasen / TBC:
- PAH:
- BC:

# Warnung / Packungsbeilage

> [!CAUTION]
> 
> 🧠 **Packungsbeilage – Künstliche Intelligenz (KI) zur Unterstützung medizinischer Entscheidungen**  
> **Wirkstoff**: KI-Modul mit verantwortungsvollem Algorithmusverhalten  
> **Darreichungsform**: Digital, sporadisch inspirierend  
> 
> ### 🩺 Anwendungsgebiete  
> Zur Unterstützung medizinischer Fachkräfte bei der Entscheidungsfindung, Analyse komplexer Daten und zur Förderung von Gesprächen zwischen Mensch und Maschine. Nicht zur Alleinanwendung geeignet. KI kann helfen, medizinische Daten schneller zu analysieren, Muster zu erkennen und Entscheidungsprozesse zu unterstützen. Sie eignet sich besonders als Zweitmeinung mit digitalem Durchblick – aber bleibt ein Werkzeug, kein Ersatz für ärztliche Expertise.
> 
> ### ⚠️ Warnhinweise  
> - KI ersetzt **nicht** ärztliches Urteilsvermögen, Bauchgefühl oder die berühmte „intuitive Diagnose beim dritten Espresso“.  
> - Anwendung nur unter Anleitung und Supervision von medizinischem Fachpersonal.  
> - Bei Symptomen wie „blindem Vertrauen“ oder „automatisiertem Aktionismus“ sofort menschliche Expertise hinzuziehen.
> 
> ### 🤖 Nebenwirkungen  
> Gelegentliche Verwirrung bei inkonsistenten Datensätzen, temporäre Begeisterung über scheinbare Allwissenheit, spontane philosophische Fragen über Menschlichkeit und Moral.
> 
> ### 💡 Wechselwirkungen  
> Kann in Kombination mit klinischem Denken zu erstaunlich präzisen Ergebnissen führen. Vorsicht bei gleichzeitiger Einnahme von Bürokratie und Zeitmangel.
> In Kombination mit:
> - strukturierten Daten → klarere Analysen
> - Erfahrung & Empathie → bessere Patientenversorgung
> - multiprofessionellen Teams → spannende Diskussionen und tragfähige Lösungen
> 
> ⚠️ Gegenanzeigen
> Nicht verwenden bei:
> - blindem Vertrauen in Technologie
> - Verzicht auf ärztliches Bauchgefühl
> - Verdrängung menschlicher Verantwortung durch digitale Effizienz
> 
> ### ⏱️ Dosierung  
> - Mit Bedacht und kritisch hinterfragt verwenden.  
> - Niemals überdosieren – eine KI kann viel, aber sie spürt nicht, wie sich Verantwortung anfühlt – zwischen Klinikflur und Praxissystem.
> 
> ### 📌 Lagerung und Haltbarkeit  
> Am besten in einer Umgebung mit ethischen Standards, transparenter Kommunikation und interdisziplinärem Austausch aufbewahren. Kühl, aber mit menschlicher Wärme behandeln.
> 
> ### 📞 Bei Fragen oder ethischen Dilemmata  
> Bitte wenden Sie sich an Ihre innere Stimme, das Ethikkomitee oder Kolleg*innen mit gesundem Menschenverstand.
> **Hinweis**: Dieses KI-Projekt ist kein Ersatz für Mitgefühl, Erfahrung oder medizinische Verantwortung – sondern ein Werkzeug, das diese stärken kann.  


**Languages and Tools:** 

![JavaScript](https://img.shields.io/badge/-JavaScript-black?logo=javascript&style=social)&nbsp;&nbsp;
![TypeScript](https://img.shields.io/badge/-TypeScript-black?logo=typescript&style=social)&nbsp;&nbsp;
![HTML5](https://img.shields.io/badge/-HTML5-black?logo=html5&style=social)&nbsp;&nbsp;
![CSS3](https://img.shields.io/badge/-CSS3-black?logo=css3&style=social)&nbsp;&nbsp;
![Material UI](https://img.shields.io/badge/-Material_UI-black?logo=material-ui&style=social)&nbsp;&nbsp;
![NodeJS](https://img.shields.io/badge/-NodeJS-black?logo=node.js&style=social)&nbsp;&nbsp;
![React](https://img.shields.io/badge/-React-black?logo=react&style=social)&nbsp;&nbsp;
![GraphQL](https://img.shields.io/badge/-GraphQL-black?logo=graphql&style=social)&nbsp;&nbsp;
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-black?logo=rabbitmq&style=social)&nbsp;&nbsp;
![Docker](https://img.shields.io/badge/-Docker-black?logo=Docker&style=social)&nbsp;&nbsp;
![Kubernetes](https://img.shields.io/badge/-Kubernetes-black?logo=Kubernetes&style=social)&nbsp;&nbsp;

<!-- 
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
-->

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Github-sponsors](https://img.shields.io/badge/sponsor-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=#EA4AAA)
![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Radix UI](https://img.shields.io/badge/radix%20ui-161618.svg?style=for-the-badge&logo=radix-ui&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Zod](https://img.shields.io/badge/zod-%233068b7.svg?style=for-the-badge&logo=zod&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![mlflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=numpy&logoColor=blue)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)
![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Windows 11](https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)
![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
https://github.com/Ileriayo/markdown-badges
