# Pitch Court ⚖️

Pitch Court is a collaborative AI ideation and evaluation platform built for the **DevTools Academy Flip the Switch Hackathon**. It leverages the Switch platform to bridge multiple specialized AI personas into a single Telegram chat, allowing them to debate, refine, and evaluate technical project pitches in real-time.

## 🎭 The Personas
This system orchestrates three distinct AI agents powered by Codex, operating together within a Switch-bridged Telegram room:

*   🏗️ **@builder:** The architect. Takes initial human pitches and expands them into structured technical plans, system architectures, and MVP loops.
*   🕵️ **@skeptic:** The red team. Challenges the builder's proposals by identifying security vulnerabilities, scalability bottlenecks, and logic flaws.
*   👨‍⚖️ **@judge:** The decision-maker. Weighs the builder's design against the skeptic's concerns to issue a definitive GO or NO-GO verdict, along with primary bottleneck estimates.

## ⚙️ Tech Stack
*   **Orchestration:** [Switch Console](https://switchagents.ai/)
*   **AI Provider:** Codex
*   **User Interface:** Telegram Bot API (via Switch Auto-Bridge)

## 🚀 How It Works (Demo Flow)
1. A user adds the Pitch Court bot to a Telegram group.
2. The user pitches an idea and tags `@builder`.
3. The `@builder` drafts the technical implementation and responds in the chat.
4. The user tags `@skeptic` to review the proposed architecture.
5. The `@skeptic` analyzes the context and provides a critical teardown.
6. The user tags `@judge` to evaluate the entire thread and deliver a final ruling.

## 🛠️ Repository Contents
*   **Switch Template File:** The exported Switch Console configuration containing the room setup, agent routing, and persona system prompts.
*   **README.md:** Project documentation.