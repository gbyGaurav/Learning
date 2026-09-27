# My Learning Log

This file contains my personal learning notes and technical learnings.

## What is ml

**Date:** 2026-09-27 15:29

ml is branch of ai that used to 

---

## OKF (Open Knowledge Foundation)

**Date:** 2026-09-27 16:29

OKF most commonly stands for the Open Knowledge Foundation, a UK-based nonprofit founded in 2004. It promotes the idea that data and information — such as government data, scientific research, and cultural resources — should be freely available for anyone to access, use, reuse, and share, a concept known as "open data" or "open knowledge." The organization is known for building and maintaining CKAN, an open-source data portal platform widely used by governments and institutions to publish open datasets, as well as past initiatives like the Global Open Data Index, which tracked how open government data was around the world. Depending on context, "OKF" can also be informal shorthand for "OK, Fine" in casual text/chat, or an abbreviation specific to a particular industry or codebase.

---

## Building an MCP server with FastMCP, uv, and MCP Inspector

**Date:** 2026-09-27 16:38

Learned how to build and connect a Python MCP (Model Context Protocol) server using three key tools: FastMCP, uv, and MCP Inspector. FastMCP is a high-level Python framework that simplifies creating MCP servers by letting you define tools, resources, and prompts using simple decorators (like @mcp.tool()) instead of manually implementing the full MCP protocol. uv is a fast Python package and project manager (an alternative to pip/poetry) used here to set up the project environment, manage dependencies, and run the server reliably. MCP Inspector is a developer tool (typically run via `npx @modelcontextprotocol/inspector`) that provides a web UI to connect to a running MCP server, list its available tools/resources, and manually invoke them to test that the server works correctly before wiring it into a client like Claude. Together, this workflow covers writing the server code with FastMCP, using uv to manage the Python environment and run the server process, and using MCP Inspector to interactively verify the server's tools respond as expected.

---

## OKF (Open Knowledge Foundation / Open Knowledge Format)

**Date:** 2026-09-27 17:47

OKF has two common meanings.

1) Open Knowledge Foundation: a global non-profit network founded in 2004 in Cambridge, UK by Rufus Pollock. It promotes free access to information and data, and creates tools/projects for openness and transparency, particularly in science — encouraging unrestricted sharing of research data, publications, and educational resources. It created CKAN (a data-cataloging platform) and the Open Definition standard for what counts as "open" data/content.

2) Open Knowledge Format: a newer, more technical specification from Google Cloud (announced around June 2026, now at version 0.2). It represents organizational knowledge as a directory ("bundle") of plain markdown files with YAML frontmatter, where each file describes one concept (e.g. a database table, an API endpoint, a business metric, a playbook). It exists to let AI agents answer questions about a company's own systems, standardizing the container knowledge travels in (not the knowledge itself). No proprietary SDK is needed to read or write it — any producer can write it and any agent can consume it.

Minor/less common meanings: OKF is also the IATA airport code for Okaukuejo Airport in Namibia, and the name of a South Korean beverage company (OKF Corporation).

---

## What is AI?

**Date:** 2026-09-27

**Tags:** AI, Machine Learning, Concepts

AI (artificial intelligence) is the field of computer science focused on building systems that perform tasks normally requiring human intelligence: understanding language, recognizing images, solving problems, making decisions, and learning from experience.

Broad categories:
- Narrow AI: built for a specific task (spam filters, recommendation engines, voice assistants, image recognition). This is essentially all AI in use today.
- General AI (AGI): a hypothetical system with human-level ability across virtually any intellectual task. Doesn't exist yet.

Common approaches:
- Machine learning: the dominant approach today, where systems learn patterns from data rather than following explicit hand-written rules.
- Deep learning: a subset of machine learning using neural networks (loosely inspired by the brain) with many layers, responsible for most recent breakthroughs.
- Large language models (LLMs): trained on huge amounts of text; powers systems like ChatGPT/Claude.
- Rule-based / symbolic AI: older approach relying on explicit logic rules rather than learning from data.

Common applications: search engines, recommendation systems (Netflix, Spotify), voice assistants (Siri, Alexa), self-driving car tech, medical image analysis, fraud detection, and chatbots.

---
