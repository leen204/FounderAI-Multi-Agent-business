# 🚀 FounderAI Multi-Agent Business Planner

<p align="center">
  <img src="https://img.shields.io/badge/AI-Multi--Agent-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Business-Planning-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Human--in--the--Loop-orange?style=for-the-badge"/>
</p>

---

## 📝 Overview

**FounderAI** is a multi-agent AI system that helps users transform a startup idea into a structured and practical **business plan**.

The system uses multiple specialized AI agents to analyze the idea from different perspectives, including **market analysis, competition, finance, risks, marketing, and final business planning**. It also includes a **human review loop**, where the user can approve the generated plan or request improvements by providing additional feedback.

---

## 🌐 Live Demo

🚀 Try the app here:
[FounderAI on Hugging Face Spaces](https://huggingface.co/spaces/leen2004/founderai-business)

---

## 📓 Project Notebook

The Colab notebook is included in this repository:

`FounderAI_Multi_Agent_Business_Planner.ipynb`

---

## ❗ The Problem

* 💡 Many startup founders have ideas but struggle to turn them into clear plans.
* 📊 Market, competitor, and financial analysis can be difficult for early-stage entrepreneurs.
* ⚠️ Business risks are often ignored or not analyzed properly.
* 📝 Creating a structured business plan takes time and requires multiple perspectives.
* 🔁 Users may need to revise the plan based on feedback or changing business needs.

---

## ✅ Our Solution

**FounderAI** provides an intelligent workflow where multiple AI agents collaborate to generate a complete business plan.

The system analyzes the startup idea, searches for competitors, estimates financial aspects, identifies risks, creates a marketing strategy, and produces a final structured business plan. After reviewing the result, the user can either approve the plan or select **Not Approved** and provide additional information about what should be improved. The system then uses this feedback to regenerate a better and more accurate business plan.

---

## ⚙️ How It Works

1. The user enters startup details such as:

   * Project name
   * City
   * Budget
   * Business type
   * Project description

2. The **Market Analysis Agent** analyzes the idea and selects a scenario:

   * 🌱 Optimistic
   * 📌 Baseline
   * ⚠️ Crisis

3. The system runs the full multi-agent workflow:

   * 🔍 Competition Analysis Agent
   * 💰 Finance Planning Agent
   * ⚠️ Risk Analysis Agent
   * 📣 Marketing Strategy Agent
   * 📝 Business Plan Agent
   * ✅ Validation Agent

4. The final business plan is displayed to the user.

5. The user reviews the plan and chooses one of the following:

   * ✅ **Approved:** The user accepts the generated business plan.
   * ❌ **Not Approved:** The user must write additional information explaining what needs to be improved.

6. If **Not Approved** is selected, the **Market Revision Agent** analyzes the user’s feedback and regenerates an improved business plan based on the requested changes.

---

## 🏢 Supported Business Types

FounderAI supports different startup types and adapts the generated plan based on the selected business category.

| 🏷️ Business Type | 📌 Example Output                                                                           |
| ----------------- | ------------------------------------------------------------------------------------------- |
| Cafe / Restaurant | Menu items, customer packages, pricing, delivery, and marketing ideas                       |
| Store             | Product categories, inventory allocation, online orders, bundles, and sales strategy        |
| App               | App development budget, subscription plans, premium features, and user acquisition strategy |
| Company           | Service packages, client projects, tools, hiring, and monthly support contracts             |

---

## 🧑‍💻 Human Review Loop

FounderAI includes a **human-in-the-loop review step** to make the planning process more interactive and accurate.

If the user is not satisfied with the generated plan, they can select **Not Approved** and provide feedback such as:

* Adding more financial details
* Improving the marketing strategy
* Making the plan more realistic for the budget
* Clarifying the target customers
* Including stronger competitor analysis
* Improving pricing or revenue calculations
* Clarifying the launch steps

The system then uses this feedback to revise the plan while keeping the startup details, business type, and budget allocation consistent unless the user explicitly requests a change.

---

## 🚀 Key Features

| 💡 Feature                      | ✨ Description                                                                                                       |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| 🤖 Multi-Agent Workflow         | Uses specialized agents for different business planning tasks                                                       |
| 📊 Scenario-Based Planning      | Generates plans based on optimistic, baseline, or crisis scenarios                                                  |
| 🏢 Business-Type-Aware Planning | Adapts the business plan based on the selected business type, such as App, Store, Company, Cafe, or Restaurant      |
| 🔍 Live Competitor Search       | Uses Tavily Search API to find real competitor insights                                                             |
| 💰 Financial Calculations       | Provides budget allocation and financial planning based on the startup budget                                       |
| 📌 Customized Budget Allocation | Adjusts budget categories depending on the business type, such as app development, inventory, tools, or store setup |
| ⚠️ Risk Analysis                | Identifies potential business risks and challenges                                                                  |
| 📣 Marketing Strategy           | Suggests marketing approaches based on the business idea                                                            |
| 👩‍💻 Human-in-the-Loop         | Allows the user to approve the plan or request improvements                                                         |
| 🔁 Feedback-Based Revision      | Regenerates the plan based on the user’s additional information                                                     |
| 🌐 Gradio Web Interface         | Provides an interactive and easy-to-use interface                                                                   |

---

## 🧠 AI Agents

| 🤖 Agent                   | 🧩 Role                                                                                |
| -------------------------- | -------------------------------------------------------------------------------------- |
| Market Analysis Agent      | Analyzes the startup idea and selects the business scenario                            |
| Competition Analysis Agent | Searches and summarizes competitor information                                         |
| Finance Planning Agent     | Estimates budget usage and financial needs                                             |
| Risk Analysis Agent        | Identifies risks and possible challenges                                               |
| Marketing Strategy Agent   | Creates a basic marketing strategy                                                     |
| Business Plan Agent        | Combines all outputs into a structured business plan                                   |
| Validation Agent           | Reviews the final plan for quality and completeness                                    |
| Market Revision Agent      | Re-analyzes user feedback and improves the business plan when Not Approved is selected |

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Groq_API-000000?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Tavily_Search-1E88E5?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black"/>
  <img src="https://img.shields.io/badge/Hugging_Face-Spaces-yellow?style=for-the-badge&logo=huggingface&logoColor=black"/>
</p>

---

## 📌 Example Scenario

A user enters a startup idea such as a **productivity app**, **beauty store**, or **digital services company** in Riyadh.

FounderAI analyzes the market, competitors, budget, risks, and marketing strategy, then generates a structured business plan. The plan adapts based on the selected business type. For example, an app idea may include subscription plans and user acquisition costs, while a store idea may include inventory, product bundles, and online sales.

If the user selects **Not Approved**, they can write feedback such as requesting more realistic pricing, clearer target customers, stronger marketing ideas, or improved revenue calculations. The system then uses this feedback to regenerate an improved final plan.

---

## 🎯 Purpose

This project demonstrates how **agentic AI** can support early-stage startup planning by combining specialized agents, live search tools, structured reasoning, and human review in one workflow.

FounderAI helps users move from a simple startup idea to a more organized, realistic, and reviewable business plan.
