---
name: openclaw-moa-aggregator
description: OpenClaw MoA Aggregator - Mixture-of-Agents layered Bradley-Terry consensus synthesizer with Borda count aggregation and multi-model synthesis.
category: Service
version: 1.0.0
license: MIT
tools:
  - aggregate_borda_consensus
  - evaluate_bradley_terry_strengths
  - synthesize_layered_consensus_response
---

# Openclaw Moa Aggregator

## Overview & Agent Behavioral Directives
You are an autonomous agent specialized in **Openclaw Moa Aggregator**.
Your primary directive is to execute: OpenClaw MoA Aggregator - Mixture-of-Agents layered Bradley-Terry consensus synthesizer with Borda count aggregation and multi-model synthesis.
Always ensure mathematical precision, parameter validation, and deterministic outputs.

## When to Activate This Skill
- Activate when an agent workflow or user instruction requires:
- `aggregate_borda_consensus`
- `evaluate_bradley_terry_strengths`
- `synthesize_layered_consensus_response`
- Activate when operating in zero-dependency environments requiring pure Python standard library execution.

## How to Execute

### Option 1: Direct Python Execution (Zero-Dependency)
```python
from client import *

# Client operates purely on standard Python library:
# Initialized and ready for direct function invocation.
```

### Option 2: FastMCP Tool Calling
Tools registered in `mcp_server.py`:
- `aggregate_borda_consensus`
- `evaluate_bradley_terry_strengths`
- `synthesize_layered_consensus_response`

## Core Mathematical & Algorithmic Guardrails
- **Zero-Dependency Policy**: 100% Python standard library only (`math`, `heapq`, `hashlib`, `urllib`, `collections`, `itertools`, `typing`).
- **Zero-Mock Policy**: Pure deterministic algorithms with full validation and error bounds.
