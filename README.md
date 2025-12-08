# Kaggle-5-Day-AI-Agents-Intensive-Course-with-Google
Kaggle 5-Day AI Agents Intensive Course with Google
https://www.kaggle.com/learn-guide/5-day-agents
5-Day AI Agents Intensive Course with Google
Kaggle-Mentor3



What is the 5-Day AI Agents Intensive?
The 5-Day AI Agents Intensive course with Google is a hands-on program originally held live from November 10 - 14, 2025. It is now available as a self-paced Kaggle Learn guide so anyone can explore the foundations, architecture and practical development of AI agents.

This course was crafted by Google’s ML researchers and engineers to help developers explore the foundations and practical applications of AI agents. You’ll learn the core components – models, tools, orchestration, memory and evaluation. Finally, you’ll discover how agents move beyond LLM prototypes to become production-ready systems.

Each day blends conceptual deep dives with hands-on examples, codelabs, and live discussions. By the end, you’ll be ready to build, evaluate, and deploy agents that solve real-world problems.

Welcome to our Agents Intensive Learn Guide!
Other Resources
What’s being covered?
Day 1 - Introduction to Agents: Explore the foundational concepts of AI agents, their defining characteristics, and how agentic architectures differ from traditional LLM applications, laying the groundwork for building intelligent, autonomous systems.
Day 2 - Agent Tools & Interoperability with Model Context Protocol (MCP): Dive into the world of tools, understanding how AI agents can "take action" by leveraging external functionalities and APIs, and explore the ease of discovering and using tools offered by the MCP.
Day 3 - Context Engineering: Sessions & Memory: Explore how to build AI agents that can remember past interactions and maintain context. Learn how to implement short-term and long-term memory to create more robust agents capable of handling complex, multi-turn tasks.
Day 4 - Agent Quality: Learn to build robust and reliable AI agents by mastering the critical disciplines of evaluating and improving agents. This session will cover observability, logging, and tracing to provide visibility, alongside key metrics and evaluation strategies to optimize agent performance.
Day 5 - Prototype to Production: Go beyond local testing and learn to deploy and scale AI agents for real-world use. This session will cover the best practices for deploying your agents so that others can use them, including how to create a truly multi-agent system with the Agent2Agent (A2A) Protocol.
Other Resources
Setup Instructions
To ensure you are ready for the course, please complete these essential setup steps:

 Kaggle account: Sign up for a Kaggle account and learn how Notebooks work. Make sure to phone verify your account, it’s necessary for the course’s codelabs.
 AI Studio account: Sign up for an AI Studio account and ensure you can generate an API key.
 Kaggle Discord: Sign up for a Discord account and join us on the Kaggle Discord server to connect and collaborate with fellow learners in this course.
Other Resources
Day 1 (Introduction to Agents)
Welcome to Day 1.

This whitepaper introduces Al agents. It presents a taxonomy of agent capabilities, emphasizes the need for an Agent Ops discipline for reliability and governance, and discusses the importance of agent interoperability and security through identity and constrained policies.

In the codelabs, you'll be building your first AI agent and your first multi-agent system, using Agent Development Kit (ADK), powered by Gemini, and giving it the ability to use Google Search to answer questions with up-to-date information. In the second codelab, the focus will be on multi-agent systems, where you'll learn how to create teams of specialized agents and explore different architectural patterns.

Day 1 Assignments

1. Complete the Unit 1 – “Introduction to Agents”:

 Listen to the summary podcast episode for this unit.
 To complement the podcast, read the “Introduction to Agents” whitepaper
 Complete these codelabs on Kaggle:
 Build your first agent using Gemini and ADK.
 Build your first multi-agent systems using ADK.
 Make sure you phone verify your Kaggle account before starting, it's necessary for the codelabs.
 We also have a troubleshooting guide for the codelabs. Be sure to check there for solutions to common problems.
 Want to have an interactive conversation? Try adding the whitepapers to NotebookLM.

[Optional]: Watch the recorded YouTube livestream. Kanchana Patlolla and Anant Nawalgaria hosted the first livestream on Kaggle’s YouTube channel. They were joined by codelab authors Kristopher Overholt and Hangfei Lin, along with special guests from Google: Alan Blount, Mike Clark, Michael Gerstenhaber, and Antonio Gulli to discuss the assignments and shared insights.
Other Resources
Day 2 (Agent Tools & Interoperability with Model Context Protocol (MCP))
Welcome to Day 2.

This whitepaper focuses on external tools functions that allow an agent to perform actions or retrieve real-time data beyond its training set and introduces best practices for designing effective tools. You'll learn about MCP, highlighting its architectural components, communication layer, risks and enterprise readiness gaps.

In the codelabs, you will create custom tools for your agents by turning your own Python functions into actions your agent can perform. You'll also use MCP and implement long-running operations where an agent can pause tool calls while waiting for human approval, before resuming.

Day 2 Assignments:

Complete Unit 2 - “Agent Tools & Interoperability with Model Context Protocol (MCP)”:

 Listen to the summary podcast episode for this unit.
 To complement the podcast, read the “Agent Tools & Interoperability with Model Context Protocol (MCP)” whitepaper.
 Complete these codelabs on Kaggle:
 Explore new ways to add tools to extend what your agents can do.
 Explore best practices for tools, including using MCP and long-running operations.
[Optional]: Watch the recorded YouTube livestream. Kanchana Patlolla and Anant Nawalgaria were joined by codelab author Laxmi Harikumar, along with Google guests Edward Grefenstette, Mike Styer, and Oriol Vinyals, as well as external speaker Alex Wissner-Gross from Reified, to discuss the assignments and share insights.
Other Resources
Day 3 (Context Engineering: Sessions & Memory)
Welcome to Day 3.

This whitepaper explores context engineering as the practice of dynamically assembling and managing information within an agent's context window to create stateful and personalized Al experiences. It defines Sessions as the container for a single, immediate conversation's history, and Memory as the long-term persistence mechanism.

In the codelabs, you will learn how to make agents stateful by managing conversation history through context engineering in ADK, and working memory within a session, allowing your agent to remember context and have coherent, multi-turn conversations. In the second notebook, you'll give your agent long-term memory that persists across different sessions.

Day 3 Assignment

Complete Unit 3 - “Context Engineering: Sessions & Memory”:

 Listen to the summary podcast episode for this unit.
 To complement the podcast, read the “Context Engineering: Sessions & Memory whitepaper”.
 Complete these codelabs on Kaggle:
 Build stateful agents and perform context engineering.
 Explore how to use memory with your agent.
[Optional]: Watch the recorded YouTube livestream. Kanchana Patlolla and Anant Nawalgaria were joined by codelab author Kristopher Overholt, along with guests from Google: Steven Johnson, Kimberly Milam and Julia Wiesinger, and external speaker Jay Alammar from Cohere.
Other Resources
Day 4 (Agent Quality)
Welcome to Day 4.

This whitepaper addresses the challenge of assuring quality in Al agents by introducing a holistic evaluation framework. The necessary technical foundation for this is Observability, built on three pillars: Logs (the diary), Traces (the narrative), and Metrics (the health report), enabling a continuous feedback loop using scalable methods like LLM-as-a-Judge and Human-in-the-Loop (HITL) evaluation.

In the codelabs, you'll learn how to use logs, traces, and metrics to get full visibility into your agent's decision-making process, allowing you to debug failures and understand why your agent behaves the way it does. In the second codelab, you'll learn how to evaluate your agents to score your agent's response quality and tool usage.

Day 4 Assignment

Complete Unit 4 - “Agent Quality”:

 Listen to the summary podcast episode for this unit.
 To complement the podcast, read the Agent Quality whitepaper.
 Complete these codelabs on Kaggle:
 Implement observability to help you debug your agents.
 Evaluate your agents.
[Optional]: Watch the recorded YouTube livestream. Kanchana Patlolla and Anant Nawalgaria were joined by codelab author Sita Lakshmi Sangameswaran, along with guests from Google: Wafae Bakkali, Turan Bulmus and Sian Gooding, and external guest Jiwei Liu from NVIDIA.
Other Resources
Day 5 (Prototype to Production)
Welcome to Day 5.

This whitepaper provides a technical guide to the operational lifecycle of AI agents, focusing on deployment, scaling and productionization. It explores the challenges of transitioning agentic systems from prototypes to enterprise-grade solutions, with special attention to Agent2Agent (A2A) Protocol.

In the codelabs, you'll learn how to build systems of multiple, independent agents that can communicate and collaborate using A2A Protocol. You'll also learn how to take your agent from your local machine to a production-ready, scalable service, by deploying your agent to Vertex AI Agent Engine on Google Cloud.

Final Assignment

Complete Unit 5 - “Prototype to Production”:

 Listen to the summary podcast episode for this unit.
 To complement the podcast, read the “Prototype to Production” whitepaper. .
 Complete these codelabs on Kaggle:
 Explore how to use A2A Protocol to have agents interact with each other.
 [Optional] Deploy your agent to Agent Engine on Google Cloud.
[Optional]: Watch the recorded YouTube livestream. Kanchana Patlolla and Anant Nawalgaria were joined by codelab author Laxmi Harikumar, along with guests from Google: Will Grannis, Sokratis Kartakis, Elia Secchi and Saurabh Tiwary.
Congratulations on completing the Agents Intensive Learn Guide!
Happy Kaggling!
