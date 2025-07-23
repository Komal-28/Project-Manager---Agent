# AI-Assisted Food Delivery App - Project Plan

## Overview

This project is a **Software Project Management (SPM)** case study focused on using **AI agents** to automate the planning and documentation of a **web-based food delivery application** using the **Waterfall Model**.

Team: **Team 11**  
Course: **ITM Project Management**  
Institution: Illinois Institute of Technology  

## Project Goal

To create an AI-assisted project plan for automating the development of a food delivery web application and perform a comparative analysis of different GenAI frameworks based on their planning accuracy and efficiency.

---

## Features of the App

- Browse and order food from multiple restaurants
- Make secure online payments
- Track orders in real-time
- Rate and review restaurants
- Receive personalized offers

---

## Agent Roles and Responsibilities

| Agent | Role |
|-------|------|
| **Customer Proxy Agent** | Gathers customer requirements |
| **Project Manager Agent** | Plans phases and features |
| **Requirement Engineer Agent** | Documents system requirements |
| **System Engineer Agent** | Designs system architecture |
| **Software Developer Agent** | Builds the application |
| **Test Engineer Agent** | Performs functional and security testing |
| **Documentation Engineer Agent** | Creates user guides and technical documents |

---

## Methodology

- **Development Model**: Waterfall
- **GenAI Frameworks Used**: 
  - AutoGen
  - LangChain
- **Model**: GPT-4o-Mini
- **Chat Structures**:
  - **Round Robin** – Agents take turns in fixed order
  - **Nested Chat** – Agents dynamically call sub-agents for sub-tasks

---

## Experiments and Key Findings

### Framework Comparison:
- **AutoGen Nested Chat** provided the most time-efficient project plans.
- **Prompt engineering** significantly affects output quality.
- **LangChain** and **AutoGen** both produce well-structured outputs but require refinement.

### Strengths:
- Fast generation of structured project plans.
- Useful as a starting draft for real projects.

### Weaknesses:
- Generic outputs when prompts are vague.
- Lacks domain-specific precision in some cases.

---

## Future Improvements

- Train AI agents on industry-specific terminology and requirements.
- Enhance natural flow and coherence of generated plans.
- Add validation logic for timeline accuracy.

---

## Demo

> A demonstration of the AI-generated project plans is available in the attached presentation and can be adapted into a live walkthrough upon request.

---

## Team Members

- **Raviraj Khopade**   
- **Chinmay Chaudhari**  
- **Komal Naik**  
- **Prashant Salunkke**  

---

## License

This repository is for educational purposes only as part of ITM Project Management coursework. Please do not redistribute without permission.
