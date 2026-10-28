# Hakvin Vosteen

I'm an economics student at the University of Bremen building AI systems for higher education and research. I'm interested in what happens after an AI generates an answer: where the information came from, whether a result can be checked, and how useful tools fit into everyday work.

## StudIPilot

<p align="center">
  <img src="images/studipilot-mascot.png" alt="StudIPilot mascot" width="110"><br>
  <img src="images/studipilot-wordmark.png" alt="StudIPilot" width="320">
</p>

**An LLM plugin for AI automation in German higher education.**

University life is scattered across course platforms, lecture slides, email, calendars, and deadlines. StudIPilot is an LLM plugin accessed directly inside an AI assistant, so students can ask questions in the chat instead of searching through each system separately.

The project synchronizes course materials from Stud.IP, indexes documents, and makes them searchable through an MCP gateway. It combines keyword and semantic search, retrieves the relevant source pages, and gives the assistant the information it needs to cite the original material. The same gateway connects university email, calendars, and tasks, making it possible to prepare briefings and find context across different sources.

StudIPilot is built with Python, FastMCP, SQLite, and Railway. Access is protected with OAuth 2.0 and PKCE, with separate permissions for different actions. The public repository is a development snapshot and a starting point for self-hosting; it does not contain my personal data or private app connection.

[**Explore StudIPilot on GitHub →**](https://github.com/hakvinv/studipilot-open-source)

## SuperFlow ML

<p align="center">
  <img src="images/superflow-mascot.png" alt="SuperFlow mascot" width="110"><br>
  <img src="images/superflow-wordmark.png" alt="SuperFlow" width="320">
</p>

**A verification layer for AI-generated proposals.**

AI can generate a promising answer without showing whether the underlying structure holds up. SuperFlow explores a different approach: define the space of candidate structures, check proposals against explicit rules and measurements, and record what survives independent verification. When the available evidence does not settle a claim, the system can abstain instead of forcing a decision.

The project also records checks and decisions in hash-chained, replayable logs, so the reasoning behind a result can be inspected later. SuperFlow is a private research and development project; the repository is not public.

One application is [**T3 QGT: Covariant Softspace Generator near a Complex-RHF Stability Crossing**](https://doi.org/10.5281/zenodo.22975222), a numerical research report whose underlying model structure was identified using SuperFlow. The Zenodo record is public; access to the report is restricted and available on request.

More research and working papers are available at [H. Vosteen Research](https://hakvinv.github.io/H.Vosteen-Research-/).
