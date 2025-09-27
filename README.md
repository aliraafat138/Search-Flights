# ✈️ Flight Search Agent with LangGraph

## 📌 Overview
This project is a **LangGraph-powered conversational agent** that helps users search for flights.  
It combines:
- **LangGraph** – to build the agent and orchestrate reasoning.  
- **Tavily** – for contextual web search.  
- **Amadeus API** – to fetch live flight information (airlines, times, prices).  

The agent can:
- Understand natural-language flight queries.  
- Use Tavily to enrich results with travel information (airports, destinations, etc.).  
- Call Amadeus to return **real flight options**.  

---

## 🛠️ Tech Stack
- [LangGraph](https://github.com/langchain-ai/langgraph)  
- [LangChain](https://www.langchain.com/)  
- [Tavily API](https://tavily.com/)  
- [Amadeus Travel APIs](https://developers.amadeus.com/)  
 

---

## ⚙️ How It Works
1. **User Input**  
   User asks: *“Find me flights from Cairo to Paris tomorrow evening.”*  

2. **LangGraph Agent**  
   Parses the intent and determines the right tools to call.  

3. **Tavily Tool**  
   Retrieves contextual data about the airports/destinations if needed.  

4. **Amadeus Tool**  
   Queries live flight data (price, airline, departure, arrival).  

5. **Final Response**  
   The agent formats and delivers results in a human-friendly way.  

---

## 📂 Project Structure
