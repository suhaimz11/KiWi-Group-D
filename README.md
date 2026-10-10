# KIWi — AI-Powered Knowledge Assistant for THWS CampusPortal

- **Status:** Planning / early development
- **Team:** 4 students
- **Module:** MAI Project Module · Winter Semester 2026/27
- **Institution:** Technical University of Applied Sciences Würzburg-Schweinfurt (THWS)
- **Supervisor:** Prof. Dr. Ivan P. Yamshchikov

## Overview

**KIWi** (*KI-Wissensassistenz*) is a planned, locally hosted AI assistant that helps students and staff find information about the THWS CampusPortal (HISinOne).

It uses **Retrieval-Augmented Generation (RAG)** to search approved university documentation and generate answers with source citations. Document processing and model inference are intended to run on university-controlled infrastructure without external LLM API calls.

## Planned Features

- Natural-language questions about CampusPortal workflows.
- Ingestion and semantic search of approved documentation.
- Answers grounded in retrieved passages with source citations.
- Local model inference and containerized deployment.

The technology stack is still being selected. Setup and run instructions will be added when an implementation is available.

## Data Handling

Only approved documentation should be ingested. Personal or sensitive data must be handled according to THWS requirements and access permissions. Internal documents and credentials must not be published.

## Deliverables

- Dockerized prototype and source code.
- Evaluation of retrieval relevance, answer accuracy, citation correctness, and unsupported answers using representative anonymized questions.
- Technical paper, project poster, and live demonstration.
