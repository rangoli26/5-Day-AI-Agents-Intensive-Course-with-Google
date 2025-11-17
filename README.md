# 5-Day-AI-Agents-Intensive-Course-with-Google
Welcome to our 5-Day AI Agents Intensive Course with Google!

What is the 5-Day AI Agents Intensive?

This 5-day online course was crafted by Google’s ML researchers and engineers to help developers explore the foundations and practical applications of AI agents. You’ll learn the core components – models, tools, orchestration, memory and evaluation. Finally, you’ll discover how agents move beyond LLM prototypes to become production-ready systems.

Each day blends conceptual deep dives with hands-on examples, codelabs, and live discussions. By the end, you’ll be ready to build, evaluate, and deploy agents that solve real-world problems.
This page serves as the central hub for all course materials, updates and resources.
Other Resources
How the Course Works:

The course is designed to be flexible and interactive, allowing you to learn at your own pace while benefiting from live sessions and community engagement.

    Daily Content Release: New assignments will be posted each day on this Kaggle course page - your primary source for all course materials.
    Assignment Notifications (Fast Follow): Given the large number of participants, links to all assignment materials including whitepapers, codelabs and podcast episodes — will also be shared on the Kaggle Discord and sent via follow-up email shortly after being posted.
    Support & Discussion: Join the discussion on our dedicated Discord channels to connect with other learners, ask questions, and get support from Google researchers and engineers who will be monitoring the channels throughout the week.
    Daily Livestreams: Join Kanchana Patlolla and Anant Nawalgaria live each day starting Monday, November 10th at 11 AM PT / 8 PM CET / 12:30 AM IST on Kaggle’s YouTube channel. They will be joined by special guests from Google, NVIDIA, Cohere and more. After each session, recordings will be shared on Discord.
    Course Completion: To get the most out of this intensive, we recommend completing all course materials including whitepapers, podcasts and codelabs before starting the capstone project. Assignments are provided for your learning, so assignment submissions are not required and you can complete them at your own pace.
    Capstone Project: On the final day, you’ll have the chance to apply everything you’ve learned by building your own AI agent. By participating in the capstone project, you will earn a badge on Kaggle.
    Community: We want this community to be positive and supportive. Please follow Kaggle’s community guidelines found here.

Other Resources
Setup Instructions

To ensure you are ready for the course, please complete these essential setup steps:

    Kaggle account: Sign up for a Kaggle account and learn how Notebooks work. Make sure to phone verify your account, it’s necessary for the course’s codelabs.
    AI Studio account: Sign up for an AI Studio account and ensure you can generate an API key.
    Kaggle Discord: Sign up for a Discord account and join us on the Kaggle Discord server. We have the following channels dedicated to this event:
        #5dgai-announcements: find official course announcements and livestream recordings.
        #5dgai-introductions: introduce yourself and meet other participants from around the world.
        #5dgai-question-forum: Discord forum-style channel for asking questions and discussions about the assignments.
        #5dgai-general-chat: a general channel to discuss course materials and network with other participants.
        Please note that if you would like to post on other channels on the Kaggle discord you will need to link your Kaggle account to discord here: https://kaggle.com/discord/confirmation. 

Other Resources
Day 1 (Introduction to Agents)
Today’s whitepaper introduces Al agents. It presents a taxonomy of agent capabilities, emphasizes the need for an Agent Ops discipline for reliability and governance, and discusses the importance of agent interoperability and security through identity and constrained policies.

In today's codelabs, you'll be building your first AI agent and your first multi-agent system, using Agent Development Kit (ADK), powered by Gemini, and giving it the ability to use Google Search to answer questions with up-to-date information. In the second codelab, the focus will be on multi-agent systems, where you'll learn how to create teams of specialized agents and explore different architectural patterns.

Day 1 Assignments

1. Complete the Unit 1 – “Introduction to Agents”:


    Listen to the summary podcast episode for this unit, created by NotebookLM.
    To complement the podcast, read the “Introduction to Agents” whitepaper
    Complete these codelabs on Kaggle:
        Build your first agent using Gemini and ADK.
        Build your first multi-agent systems using ADK.
        Make sure you phone verify your Kaggle account before starting, it's necessary for the codelabs.
        We also have a troubleshooting guide for the codelabs. Be sure to check there for solutions to common problems.
        Want to have an interactive conversation? Try adding the whitepapers to NotebookLM. 

Other Resources
Day 2 (Agent Tools & Interoperability with Model Context Protocol (MCP))
Today’s whitepaper focuses on external tools functions that allow an agent to perform actions or retrieve real-time data beyond its training set and introduces best practices for designing effective tools. You'll learn about MCP, highlighting its architectural components, communication layer, risks and enterprise readiness gaps.

In today's codelabs, you will create custom tools for your agents by turning your own Python functions into actions your agent can perform. You'll also use MCP and implement long-running operations where an agent can pause tool calls while waiting for human approval, before resuming.

Day 2 Assignments

Complete Unit 2 - “Agent Tools & Interoperability with Model Context Protocol (MCP)”:


    Listen to the summary podcast episode for this unit, created by NotebookLM.
    To complement the podcast, read the “Agent Tools & Interoperability with Model Context Protocol (MCP)” whitepaper.
    Complete these codelabs on Kaggle:
        Explore new ways to add tools to extend what your agents can do.
        Explore best practices for tools, including using MCP and long-running operations.
        Want to have an interactive conversation? Try adding the whitepapers to NotebookLM. 

Other Resources
Day 3 (Context Engineering: Sessions & Memory)
This whitepaper explores context engineering as the practice of dynamically assembling and managing information within an agent's context window to create stateful and personalized Al experiences. It defines Sessions as the container for a single, immediate conversation's history, and Memory as the long-term persistence mechanism.

In the codelabs, you will learn how to make agents stateful by managing conversation history through context engineering in ADK, and working memory within a session, allowing your agent to remember context and have coherent, multi-turn conversations. In the second notebook, you'll give your agent long-term memory that persists across different sessions.

Day 3 Assignment

Complete Unit 3 - “Context Engineering: Sessions & Memory”:


    Listen to the summary podcast episode for this unit, created by NotebookLM.
    To complement the podcast, read the “Context Engineering: Sessions & Memory whitepaper”.
    Complete these codelabs on Kaggle:
        Build stateful agents and perform context engineering.
        Explore how to use memory with your agent.
        Want to have an interactive conversation? Try adding the whitepapers to NotebookLM. 

Other Resources
Day 4 (Agent Quality)
This whitepaper addresses the challenge of assuring quality in Al agents by introducing a holistic evaluation framework. The necessary technical foundation for this is Observability, built on three pillars: Logs (the diary), Traces (the narrative), and Metrics (the health report), enabling a continuous feedback loop using scalable methods like LLM-as-a-Judge and Human-in-the-Loop (HITL) evaluation.

For today's codelabs, you'll learn how to use logs, traces, and metrics to get full visibility into your agent's decision-making process, allowing you to debug failures and understand why your agent behaves the way it does. In the second codelab, you'll learn how to evaluate your agents to score your agent's response quality and tool usage.

Day 4 Assignment

Complete Unit 4 - “Agent Quality”:


    Listen to the summary podcast episode for this unit, created by NotebookLM.
    To complement the podcast, read the Agent Quality whitepaper.
    Complete these codelabs on Kaggle:
        Implement observability to help you debug your agents.
        Evaluate your agents.

Other Resources
Day 5 (Prototype to Production)
This whitepaper provides a technical guide to the operational lifecycle of AI agents, focusing on deployment, scaling and productionization. It explores the challenges of transitioning agentic systems from prototypes to enterprise-grade solutions, with special attention to Agent2Agent (A2A) Protocol.

For today's codelabs, you'll learn how to build systems of multiple, independent agents that can communicate and collaborate using A2A Protocol. You'll also learn how to take your agent from your local machine to a production-ready, scalable service, by deploying your agent to Vertex AI Agent Engine on Google Cloud.

Final Assignment

Complete Unit 5 - “Prototype to Production”:


    Listen to the summary podcast episode for this unit.
    To complement the podcast, read the “Prototype to Production” whitepaper.
    Complete these codelabs on Kaggle:
        Explore how to use A2A Protocol to have agents interact with each other.
        [Optional] Deploy your agent to Agent Engine on Google Cloud. 

Other Resources
Final Reminders and Announcements

Congrats on completing the 5-day AI Agents Intensive course!

    🎯 Capstone Project: You’ll create an AI agents project showcasing a use case that leverages some of the key capabilities learned throughout this course. The top 12 winners will receive Kaggle swag and have their work featured on Kaggle’s social media platforms. More details about the Capstone Project, including the evaluation and submission process will be shared in an email later today. Participation in the Capstone Project is optional.
    ⭐ Kaggle badge and certificate: Due to high demand, participants in the Capstone Project are eligible to earn a badge and certificate on their Kaggle profile. These will be added to all eligible profiles by the end of December 2025.
    👀 Look out for the Kaggle Learn Guide: We are actively working to transition this content into a convenient Kaggle Learn Guide. We will be sharing this updated resource with you as soon as it is ready.
    🤖 GEAR: If you’d like to continue building on what you learned in the Agents Intensive, Google’s upcoming Gemini Enterprise Agent Ready (GEAR) initiative offers a deeper dive into learning, building and deploying AI agents. GEAR launches in early 2026 - learn more here.

Check out the Agents Intensive - Capstone Project here.
