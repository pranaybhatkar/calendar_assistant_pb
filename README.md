MCP_Server.json	An MCP Server Trigger that exposes two tools: send a Gmail message and update a Google Doc.
MCP_Client.json	A chat-triggered AI Agent with a 10-message window memory and an MCP Client tool pointing at that server.
Orchestrator_pattern_-_Agent_as_tool.json	A demo from the mentor: a manager agent with a research agent (SerpAPI web search, at most 3 searches) and a newsletter agent (which sends through MCP) as tools.
Calendar_assistant.json	A Schedule Trigger at 6 AM runs an AI Agent on Groq. The agent reads the day’s Google Calendar events and emails the top two most important ones, with reasons, from titles, descriptions and attendees.
