# Multi-Agent-Orchestration-Banking-use-case
How to transform a traditional banking application into a modern, AI-powered solution using watsonx Orchestrate

Welcome to the GFM Bank Agentic AI Lab! This hands-on workshop guides you through transforming a traditional banking application into a modern, AI-powered solution using watsonx Orchestrate.

As the banking industry rapidly evolves through digital transformation, GFM Bank is at the forefront, leveraging innovative AI agents to enhance customer interactions and streamline operations. Currently, traditional teller and back-office processes are manual, time-consuming, and often lead to long customer wait times. By adopting an Agentic AI solution, GFM Bank aims to:

- Provide 24/7 customer support for common banking operations
- Reduce wait times for transactions and approvals
- Maintain strict compliance with banking regulations
- Improve customer satisfaction by delivering faster service
- Enable human staff to focus on more complex customer needs

In this lab, you will build a system of collaborating AI agents capable of handling a variety of banking operations, including:

- Account balance inquiries
- Money transfers between accounts
- Overdraft limit approvals
- Fee reversals
- Product information requests

  
# User Scenario

## Current Situation

John, a GFM Bank customer, needs to make an urgent payment of €8,000, but he only has €5,000 in his account. The process today looks like this:

1. John visits the bank branch and waits in line to speak with a teller.
2. The teller checks his balance and informs him he has insufficient funds.
3. John requests an overdraft of €5,000.
4. The teller must escalate the request to a back-office manager.
5. John waits again for approval.
6. Once approved, he returns to the teller to complete the transfer.
7. If John realizes he sent too much money, he needs to request a reversal, which requires another approval process.

This process typically takes 1–2 hours of John’s time and involves multiple staff members.

## Future with Agentic AI

With the AI-powered system you’ll build today, the process is streamlined:

1. John messages the GFM Bank Orchestrator Agent.
2. He requests to transfer €8,000.
3. The Teller Agent checks his balance and informs him of insufficient funds.
4. John requests an overdraft.
5. The Orchestrator automatically routes this to the Backoffice Agent.
6. Upon approval, the Teller Agent completes the transfer.
7. If John needs a reversal, it’s handled quickly within the same conversation.

The entire process takes minutes instead of hours, and John never has to leave his home.

# Lab Instructions

In this lab, you will build a complete Agentic AI solution for GFM Bank using watsonx Orchestrate. You’ll create multiple specialized agents that collaborate to handle customer requests efficiently.

## Prerequisites

- Access to your assigned watsonx Orchestrate instance
- Basic understanding of banking operations (e.g., transfers, balance checks, overdraft requests)
- Familiarity with AI agent concepts (e.g., instructions, tools, collaborators)

  Lab Steps Overview
1. ConnecttowatsonxOrchestrate
2. CreatetheGFMTellerAgent
3. CreatetheGFMBackofficeAgent
4. CreatetheGFMProductInformationAgent 5. CreatetheGFMBankOrchestratorAgent 6. Testthecompletesolution
