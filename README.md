# AI Inventory Assistant

Proof of concept for an AI-powered IT inventory assistant designed to support IT Operations teams through natural language interaction.

## Overview

AI Inventory Assistant allows users to query inventory data, retrieve operational procedures and perform controlled asset updates through a human-in-the-loop workflow.

The project demonstrates how AI can support IT asset management while keeping users in control of sensitive database changes.

## Features

- Natural language inventory queries
- Asset ownership lookup by barcode
- Inventory terminology assistance
- Procedure and workflow explanations
- Controlled asset update suggestions
- Human confirmation before database writeback
- SQLite inventory database
- FastAPI backend
- Appsmith low-code frontend
- OpenAI-powered assistant

## Architecture

```text
Appsmith Cloud
↓
ngrok tunnel for PoC only
↓
FastAPI backend
↓
SQLite database
↓
OpenAI API
↓
Markdown knowledge base
