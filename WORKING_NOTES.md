# Working Notes — Jack Laughlin Personal Landing Page

> This is an internal working document for developer and AI assistant reference. It is not intended for public audiences. This file should be updated at the end of every work session.

---

## 1. How to Use This File (For AI Assistants)

1. Read this entire file before suggesting changes or writing code  
2. Read README.md for the public-facing description  
3. Do not change the folder structure or conventions without discussion  
4. Follow all listed conventions exactly  
5. Do not suggest approaches listed in "What Was Tried and Rejected"  
6. Ask clarifying questions before making large structural changes  
7. This project is AI-assisted (Replit + ChatGPT); refactor conservatively  

---

## 2. Current State

**Last Updated:** 2026-03-23  

This project is a completed first version (MVP) of a personal landing page built using HTML and CSS. The site includes a homepage with sections for bio, skills, projects, leadership, and contact information. It is deployed via Azure Static Web Apps and connected to a GitHub repository.

### What Is Working
- [x] Homepage layout implemented  
- [x] Navigation with anchor links  
- [x] Skills section (grouped categories)  
- [x] Projects section with descriptions and outcomes  
- [x] Leadership section (football + achievements)  
- [x] Contact section with LinkedIn, GitHub, email  
- [x] Responsive layout  
- [x] Deployed to Azure  

### What Is Partially Built
- [ ] Styling refinements (spacing, alignment improvements)  
- [ ] Additional project detail formatting  

### What Is Not Started
- [ ] Additional pages (if needed in future)  
- [ ] Interactive features or dashboards  
- [ ] Analytics tracking  

---

## 3. Current Task

**What I was working on when I last stopped:**  
Finalizing project documentation and preparing deliverables for submission, including README.md and WORKING_NOTES.md.

**The very next step is:**  
Push final updates to GitHub and verify deployment on Azure.

---

## 4. Architecture and Tech Stack

| Technology | Version | Why It Was Chosen |
|-----------|--------|-------------------|
| HTML5 | Latest | Standard for building structured web pages |
| CSS3 | Latest | Used for styling and layout |
| GitHub | N/A | Version control and project hosting |
| Azure Static Web Apps | N/A | Hosting and deployment of the website |
| Replit | N/A | AI-assisted development environment |

---

## 5. Project Structure Notes
/Landing-page
├── index.html
├── /css
│ └── stylesheet.css
├── /images
│ └── headshot.jpg
├── PRD.md
├── STANDARDS.md
├── README.md
└── WORKING_NOTES.md

- Single-page application structure for simplicity  
- All styling is in external CSS (no inline styles)  
- Images are stored locally in `/images`  
- PRD and STANDARDS guide development decisions  

---

## 6. Data / Database

This project does not use a database or persistent data storage. All content is static.

---

## 7. Conventions

**Naming conventions:**
- Files use lowercase with no spaces (e.g., index.html, stylesheet.css)  

**Code style rules:**
- Semantic HTML elements used throughout  
- CSS stored in external stylesheet only  

**Framework patterns:**
- No framework — vanilla HTML and CSS  

**Git commit style:**
- Simple descriptive messages (e.g., "added projects section")  

---

## 8. Decisions and Tradeoffs

- **Decision made:** Use a single-page layout  
  → Keeps the site simple and easy to navigate  

- **Decision made:** Use only HTML/CSS (no frameworks)  
  → Matches assignment requirements and keeps implementation manageable  

- **Decision made:** Focus on MVP features only  
  → Prioritize completion due to time constraints  

---

## 9. What Was Tried and Rejected

- Attempting overly complex layouts  
  → Rejected due to time constraints and beginner skill level  

- Adding additional pages  
  → Rejected to keep scope manageable  

---

## 10. Known Issues and Workarounds

- Minor spacing inconsistencies  
  → Will be addressed in future iterations  

- Limited styling polish  
  → Acceptable for MVP version  

---

## 11. Browser / Environment Compatibility

- Tested on Chrome  
- Expected to work on Safari and Firefox  
- Mobile responsive (tested on small screen sizes)  

---

## 12. Open Questions

- Should additional projects be added in the future?  
- Should interactive elements be introduced later?  
- Should analytics tracking be implemented?  

---

## 13. Session Log

### 2026-03-23
- Created PRD.md and STANDARDS.md  
- Built landing page using Replit  
- Connected project to GitHub and Azure  
- Generated README.md and WORKING_NOTES.md  
- Finalized project for submission  

**Next step:** Submit deliverables and verify live site  

---

## 14. Useful References

- Replit (AI development tool)  
- GitHub (version control and hosting)  
- Azure Static Web Apps (deployment)  
- Course materials for BAIS 3300  

AI tools used:
- ChatGPT for PRD, README, and documentation  
- Replit AI for generating and editing code
