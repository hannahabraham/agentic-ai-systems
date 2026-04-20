# agentic-ai-systems

## 1_Single_vs_Multi_Agent_System.ipynb :
Compares single-agent and multi-agent architectures for healthcare utilization review using LLMs.
Simulates patient data, medical guidelines, and care recommendations within a structured workflow.
The single-agent approach handles the entire process end-to-end in one system.
The multi-agent setup divides tasks among specialized agents coordinated by a supervisor.
The notebook highlights differences in modularity, scalability, and decision-making performance.

## 2_Customer_Support_Router_Agentic_RAG_System.ipynb:
This notebook implements an agentic RAG-based customer support system that automatically understands and routes user queries.
It uses a GROQ-powered LLM to classify query type (billing, technical, general) and detect sentiment for intelligent decision-making.
Queries are answered using category-specific vector databases for accurate retrieval.
Negative or complex cases are escalated to human agents, ensuring efficient and reliable support.

## 3_Multi_Server_MCP_Architecture_for_AI_Agents.ipynb
This notebook demonstrates how to build a multi-server MCP architecture for AI agents.  
It sets up separate Finance and HR MCP servers with domain-specific tools.  
A unified MCP client connects to both servers and dynamically discovers available tools.  
An LLM-powered ReAct agent is created to orchestrate tool usage across services.  
The result is a single intelligent agent capable of handling multi-domain tasks seamlessly.


**Reference** : https://github.com/dipanjanS/building-effective-agentic-ai-systems-dhs2025
