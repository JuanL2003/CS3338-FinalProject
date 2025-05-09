
**CS3338 - Group 6**  
Juan La Serna, Hang Bao, Steven Ariza-Arzate, Toran Tran  
May 2025

---

## Project Repository and Task Board

**Project Management and Issue Tracking:**  
[Jira Project Board](https://calstatela-team-walcjwu7.atlassian.net/jira/software/projects/AJ/boards/5)

---

## Formal Objective Breakdown

The **AI Judge System** is a web-based academic simulation tool designed to emulate judicial decision-making using artificial intelligence. The system enables users to input legal case descriptions, which are processed via natural language processing (NLP) and decision engines to output a verdict and explanation.

### Core Components:
- A user-friendly web interface for case input and verdict display
- An NLP engine for identifying case-relevant facts and metadata
- A decision engine for rendering AI-based verdicts
- A fairness/bias detection module to ensure transparency
- Role-based access control for judges, technicians, and admins

---

## Goals and Reason for Development

- **Education and Research:** Demonstrate how AI can simulate legal reasoning for academic settings
- **Transparency:** Deliver human-readable explanations for AI-generated verdicts
- **Accessibility:** Provide a platform for students and educators to interact with AI-based legal simulation tools
- **Bias Detection:** Ensure AI decisions are fair and report on potential demographic biases
- **Scalability:** Designed using microservices to support modular upgrades and future database integrations

---

## System Access and Deployment

### Requirements
- **Operating System:** Windows / macOS / Linux
- **Software:** Docker, Python, Flask, MySQL
- **Browser:** Modern browser (Chrome, Firefox, Safari)

### Installation Steps
1. Clone the repository from GitHub
2. Ensure Docker is installed and running
3. Run the included `docker-compose.yml` to build and start containers:
   ```bash
   docker-compose up --build