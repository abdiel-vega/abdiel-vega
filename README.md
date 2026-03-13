<div align="center">

# Abdiel Y. Vega Vélez

**cs student - developer - cloud engineer - websec researcher**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdiel-vega2004)
[![HackerOne](https://img.shields.io/badge/-HackerOne-%23494649?style=for-the-badge&logo=hackerone&logoColor=white)](https://hackerone.com/notaquacc?type=user)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://abdiel-vega.dev)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdiel.vega@outlook.com)

**Open to internship & entry-level opportunities - Summer/Fall 2026**

</div>

---

## About Me

Third-year Computer Science student at **Inter-American University of Puerto Rico** with hands-on experience in **Python development**, **cloud infrastructure**, and **security research**.

Recent Highlights:
- Identified a **CVSS 8.1 Broken Access Control** vulnerability in a U.S. Department of State web API, exposing PII for **5,000+ individuals** including 3,900+ plaintext passwords — responsibly disclosed, triaged, and **patched**
- Built a full-featured **Spotify CLI** with real-time ASCII album art rendering, threaded keypress controls, and complete Spotify Web API integration
- Deployed my portfolio, containerized on **GCP Cloud Run** with a full CI/CD pipeline via Cloud Build and Artifact Registry at <$1/month
- Full-stack food recipe web app using **React, Next.js, TypeScript, and Supabase**

Active security researcher on **HackerOne and Bugcrowd**.

---

## Projects & Research

### Vulnerability Disclosure Program (VDP) – U.S. Department of State
Security Researcher &nbsp;|&nbsp; **Status:** Resolved – High Severity (CVSS 8.1) &nbsp;|&nbsp; *Dec 2025 – Jan 2026*

Identified critical security vulnerabilities through the U.S. Department of State's federal VDP.

- **The Finding:** Identified a **Broken Access Control (IDOR)** vulnerability on a Microsoft Dynamics 365 Web API endpoint used in visa scheduling infrastructure
- **The Impact:** Discovered exposure of Personally Identifiable Information (PII) for **5,000+ individuals**, including names, emails, and **3,900+ plaintext passwords**
- **The Result:** Authored a comprehensive proof-of-concept report with reproduction steps, impact analysis, and remediation recommendations.

`Burp Suite` `OWASP ZAP` `Kali Linux` `API Testing` `Web App Security`

🔗 [Read the Write-up](vdps/department-of-state/dos-vdp-report-censored-write-up.pdf)

<br>

### Spotify CLI
Python &nbsp;|&nbsp; *Feb 2026 – Mar 2026*

A full-featured terminal music playback controller built in Python using the **Spotify Web API**.

- Renders **true-color ASCII album art** in real time by converting album covers pixel-by-pixel into ANSI half-block characters using Pillow. Results are LRU-cached so art only re-renders on track change
- Implements a flicker-free **live dashboard** (4 Hz refresh) using Rich layouts with track name, artist, album, progress bar, and playback state
- **Single-keypress controls** (play, pause, skip, shuffle, repeat, volume) via a threaded msvcrt input listener, which means no Enter key is required
- Supports **full search** across tracks, albums, and playlists with numbered results and instant playback on selection
- Available as **standalone CLI commands** (play, pause, next, search, etc.) for scripting use

`Python` `Spotipy` `Rich` `Click` `Pillow` `python-dotenv`

🔗 [Repository](https://github.com/abdiel-vega/spotify-cli)

<br>

### Cloud Portfolio Website
Cloud Engineer &nbsp;|&nbsp; **Migration:** AWS ECS ➡ Google Cloud Platform &nbsp;|&nbsp; *Oct 2025 – Present*

Designed and deployed a containerized portfolio website on **Google Cloud Platform (GCP)**.

- **Architecture:** Migrated from AWS ECS to **Google Cloud Run** to achieve a scale-to-zero serverless architecture at <$1/month
- **CI/CD:** Implemented a pipeline using **Google Cloud Build** and Artifact Registry. Every commit is automatically built, tested, and deployed to production within minutes
- **Security & Performance:** Configured serverless networking, custom domain mapping with managed SSL, and integrated **Cloudflare** for global edge caching

`GCP (Cloud Run, Cloud Build, Artifact Registry)` `Docker` `Nginx` `Cloudflare`

🔗 [Repository](https://github.com/abdiel-vega/portfolio) | [Live Site](https://abdiel-vega.dev)

<br>

### i_Cooked – Full Stack Recipe App
Full Stack Web App &nbsp;|&nbsp; *May 2025 – Jul 2025*

Developed a complete web application featuring:

- Secure user registration and login system
- Database integration for recipe storage and user management
- Applied cybersecurity best practices in authentication implementation
- Responsive design for optimal user experience

`React` `Next.js` `TypeScript` `Supabase` `Spoonacular API` `TailwindCSS`

🔗 [Repository](https://github.com/abdiel-vega/i_Cooked) | [Live Demo](https://icooked.vercel.app/)

<br>

---

## Skills

**Security & Vulnerability Research**
<br>
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-EB5B46?style=flat-square&logo=burpsuite&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-4A90E2?style=flat-square&logo=owasp&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![HackerOne](https://img.shields.io/badge/-HackerOne-%23494649?style=flat-square&logo=hackerone&logoColor=white)

**Cloud & Infrastructure**
<br>
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Languages & Frameworks**
<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Education & Certifications

**Inter-American University of Puerto Rico** | Metro
<br>
Bachelor's Degree in Computer Science - GPA: 3.45
<br>
*August 2023 – May 2027*

### In Progress
- **CompTIA Security+** — *In Progress*

---

<div align="center">

**Open to software engineering, cloud/DevOps, AppSec, or Python internship opportunities - Summer/Fall 2026.**
<br>
Bilingual (English / Spanish) · Remote-friendly · Puerto Rico

<br>

*Thanks for visiting — feel free to reach out!*

</div>
