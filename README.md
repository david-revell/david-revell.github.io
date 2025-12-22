# David Revell – AI Engineering Portfolio

This page brings together my current applied AI engineering work.  
My focus is on practical agentic systems, tool-calling, and integrations using the OpenAI Agents SDK and MCP.

## Projects

### Agent Evaluation Orchestrator  
A generic orchestration layer for running, logging, and post-hoc evaluating AI agent behaviour across different implementations.  
Supports scenario-driven runs, structured conversation logs, and decouples execution from judgement for consistent evaluation.  
Validated with both multi-turn tool-using agents and single-turn RAG-based agents, this framework focuses on agent-agnostic behavioural analysis.  
[📁 GitHub repo](https://github.com/david-revell/agent-evaluation-orchestrator)

### Calendar Agent Evaluation Framework
An evaluation harness for testing MCP-based AI agents using scenario-driven synthetic users.
Runs repeatable multi-turn conversations, captures plain-text transcripts with stop reasons, and uses Phoenix tracing to inspect agent reasoning, tool use, and failure modes.
Focused on surfacing behavioural issues such as off-scope responses, unsupported capability claims, and non-converging dialogues.  
[📁 GitHub repo](https://github.com/david-revell/calendar-agent-controller)

### Google Calendar MCP Agent  
An MCP server and agent for managing Google Calendar through tool calls.  
Implements event listing/creation/update, conflict checking, local SQLite memory, and Phoenix tracing.  
[📁 GitHub repo](https://github.com/david-revell/google-calendar-mcp)

### RAG Evaluation Workflow (Bank of England)  
A Python workflow for assessing retrieval quality using context-precision and context-recall (RAGAS).  
Applied to multi-part financial Q&A questions for an industry-sponsored project.  
[📁 GitHub repo](https://github.com/david-revell/bank-of-england-ai-document-analysis)

### Market Trend & Fill Modelling  
A two-stage model combining weekly trend prediction with limit-order fill detection, based on engineered technical indicators.  
[📁 GitHub repo](https://github.com/david-revell/market-trend-fill-model)
