# AgenticAI / CrewAI Learning Lab 🚀  

📂 **Repository:** `crewai-learning` *(formerly crewai-learning-journey)*  
🔍 **Purpose:** Hands-on experiments with CrewAI and agentic workflows, including project code and environment setup.

## 🗂 Current Structure
```
.
├── .gitignore           # Ignores Python/IDE artifacts
├── README.md            # You're here!
├── requirements.txt     # Python dependencies (crewai, openai, crewai-tools)
├── practice.ipynb       # Jupyter notebook for experiments
├── research_crew/       # First CrewAI implementation
│   ├── src/             # Core crew implementation
│   ├── knowledge/       # User preference data
│   ├── report.md        # Generated reports
│   └── pyproject.toml   # Project config
└── .venv/               # Virtual environment (ignored)
```

## 🛠️ Setup  
1. **Create & activate virtual env** (recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Linux/Mac
   .venv\Scripts\activate     # Windows
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## ✨ Recent Updates
- Added `crewai-tools` to requirements
- Created first CrewAI implementation in `/research_crew`
- Added Jupyter notebook for experimentation
- Implemented basic crew structure with:
  - Agents configuration
  - Custom tools
  - Task workflows

