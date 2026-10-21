# AI Design Pipeline Documentation

## Project Overview
A reusable AI-assisted design workflow for moving from a business problem to a validated product design.

## Pipeline Stages
1. Business Problem
2. Research
3. Persona & Pain Points
4. Ideation
5. Information Architecture
6. Wireframes
7. UI Design
8. Prototype
9. Review & Validation
10. Handoff

## Agents
- Research Agent
- UI Design Agent
- Prototype Agent
- Review Agent
- Handoff Agent

## Orchestrator
The orchestrator coordinates the agents, manages the sequence of tasks, checks review gates, and passes outputs from one stage to the next.

## Project Memory
Project memory stores important context, decisions, research findings, constraints, and approved outputs so agents can work consistently across the pipeline.

## Inputs and Outputs
Each stage receives an input, performs a task, and produces an output for the next stage.

## Review Gates
Review gates are checkpoints used to verify quality, accuracy, safety, and readiness before moving to the next stage.

## Trust and Human Review
Important decisions are reviewed by a human before final approval, especially research interpretation, design decisions, safety-sensitive content, and final handoff.