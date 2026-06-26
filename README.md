# FounderAI-Multi-Agent-business


FounderAI is a multi-agent AI system that helps users turn a startup idea into a structured business plan.

The project uses multiple specialized AI agents to analyze the idea from different perspectives, including market, competition, finance, risk, marketing, and final business planning. It also includes a human review loop where the user can approve the plan or request improvements.

## Live Demo

Try the app here:  
https://huggingface.co/spaces/leen2004/founderai-business

## Project Notebook

The Colab notebook is included in this repository:

`FounderAI_Multi_Agent_Business_Planner.ipynb`

## How It Works

1. The user enters startup details such as project name, city, budget, business type, and project description.
2. The Market Analysis Agent analyzes the idea and selects a scenario:
   - Optimistic
   - Baseline
   - Crisis
3. The system runs the full multi-agent workflow:
   - Competition Analysis Agent
   - Finance Planning Agent
   - Risk Analysis Agent
   - Marketing Strategy Agent
   - Business Plan Agent
   - Validation Agent
4. The final business plan is shown to the user.
5. If the user selects **Not Approved**, the Market Revision Agent re-analyzes the feedback and regenerates the business plan.

## Features

- Multi-agent workflow
- Scenario-based business planning
- Live competitor search using Tavily
- Financial calculations
- Human-in-the-loop review
- Automatic plan revision
- Gradio web interface
- Hosted on Hugging Face Spaces

## Technologies Used

- Python
- Gradio
- Groq API
- Tavily Search API
- Google Colab
- Hugging Face Spaces

## Example Scenario

A user enters a startup idea for a study-focused cafe in Riyadh. FounderAI analyzes the market, competition, budget, risks, marketing strategy, and generates a structured business plan. If the user rejects the plan and provides feedback, the system revises the scenario and regenerates the final plan.

## Purpose

This project demonstrates how agentic AI can support early-stage startup planning by combining specialized agents, tools, live search, and human review in one workflow.
