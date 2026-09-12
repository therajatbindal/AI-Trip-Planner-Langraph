# AI-Trip-Planner-Langraph
A real-world multi-agent AI system for intelligent trip planning, built with LangGraph.

The system uses 4 AI agents that work together to plan a create trip plan automatically.

## Features

- ✈️ Flight Search Agent
- 🏨 Hotel Search Agent
- 🗓️ Itinerary Planning Agent
- 🤖 Final Response Agent
- 🧠 Memory using PostgreSQL
- 🌐 Real-time API Integration
- 💻 Streamlit Web Interface

---

# Tech Stack

- LangGraph
- LangChain
- Groq
- openai/gpt-oss-120b
- PostgreSQL
- Streamlit
- Tavily API
- AviationStack API

---

#### Run Streamlit Web App


		streamlit run MainDashboard.py


This will launch the Multi-Agent AI web application.

---

#### Example Prompt

Plan a complete 7 days Spain trip including flights, hotels and sightseeing under 4 lakhs.


---

# Project Workflow

1. Flight Agent searches flights
2. Hotel Agent searches hotels
3. Itinerary Agent creates travel plan
4. Final Agent combines everything together
5. PostgreSQL stores conversation memory