# AI-Driven Adaptive Agile Software Development and Intelligent Project Management System

## Team

| Name | Roll Number / ID |
|------|------------------|
| Aarya Damera (D. Aarya Deeksha) | 2420030530 |
| Y. Anuhya | 2420030514 |

**Team ID:** 2420030530
**Branch:** [e.g. CSE]
**Academic Year:** [e.g. 2025–26]

## Supervisor

Swapna Reddy, CSE, KL University

## Abstract

The AI-Driven Adaptive Agile Software Development and Intelligent Project Management System is a platform that uses AI to improve how Agile software projects are planned, monitored, and managed. It helps teams handle requirements, tasks, sprints, and team activity while adapting to change throughout the development lifecycle, following the principles of Adaptive Software Engineering so plans and priorities can shift dynamically as requirements, progress, and feedback evolve.

The system analyzes project data to generate intelligent recommendations — task prioritization, effort estimation, risk identification, sprint planning, and progress prediction — alongside core Agile workflows such as product backlog management, sprint management, task assignment, progress tracking, and retrospective analysis. By combining AI with Agile practice, the goal is to cut down manual project management overhead, surface issues earlier, and improve team decision-making, productivity, and collaboration.

## Key Features

- **AI-Assisted Task Prioritization** — recommends what to work on next based on project data and history
- **Effort Estimation** — AI-driven estimates for tasks and sprints
- **Risk Identification** — early detection of potential project risks/blockers
- **Sprint Planning Assistance** — intelligent support for planning upcoming sprints
- **Progress Prediction** — forecasts sprint/project progress based on current trends
- **Product Backlog Management** — create, prioritize, and refine the backlog
- **Sprint Management** — manage sprint lifecycle from planning to closure
- **Task Assignment & Tracking** — assign tasks to team members and track status
- **Retrospective Analysis** — AI-assisted insights from sprint retrospectives
- **Adaptive Planning** — plans and priorities adjust dynamically as requirements and feedback change

## Tech Stack

- **Backend:** Python, FastAPI
- **Frontend:** React.js, Tailwind CSS
- **Database:** PostgreSQL / MySQL
- **AI/ML:** Machine Learning, NLP, Generative AI / LLM
- **APIs:** REST APIs
- **Methodology:** Agile / Scrum
- **Version Control:** Git & GitHub

## Repository Structure

```
.
├── src/        # Source code
├── docs/       # Design docs, architecture notes, references
├── data/       # Datasets or DATA_SOURCES.md if data can't be committed
├── results/    # Output artifacts: metrics, plots, model checkpoints
├── reports/    # Phase reports, review presentations
└── README.md
```

## Setup & Execution

### Prerequisites

- Python 3.10+
- Node.js 18+
- PostgreSQL / MySQL instance

### Installation

```bash
git clone https://github.com/aaryadamera/ASE-2420030530-AIDrivenAdaptiveAgile.git
cd ASE-2420030530-AIDrivenAdaptiveAgile

# backend
pip install -r requirements.txt

# frontend
cd frontend
npm install
```

### Running the project

```bash
# backend (FastAPI)
uvicorn src.main:app --reload

# frontend (React)
cd frontend
npm run dev
```

