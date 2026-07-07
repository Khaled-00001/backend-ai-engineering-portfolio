# Prompt Iteration Log

## Selected Task

Building Backend APIs using Java Spring Boot.

---

# Version 1 — Naive Prompt

Prompt

Create a REST API for user management using Spring Boot.

Output Summary

Generated a basic CRUD API with minimal explanation.

Observation

The output worked but lacked structure, validation, and best practices.

---

# Version 2 — Role Assignment

Technique

Role Assignment

Prompt

You are a senior Backend Engineer.
Create a production-ready Spring Boot REST API for user management.

Output Summary

The response included cleaner architecture and better practices.

Observation

Giving Claude a role produced more professional recommendations.

---

# Version 3 — Context & Motivation

Technique

Context and Motivation

Prompt

You are helping me build a backend project for my internship portfolio.
The project should demonstrate clean architecture and production-ready practices.

Output Summary

The answer focused more on maintainability.

Observation

Adding context aligned the response with my real goal.

---

# Version 4 — Few-shot

Technique

Few-shot Examples

Prompt

Example:

Controller
↓

Service
↓

Repository

Use the same architecture for a User Management API.

Output Summary

The structure became more consistent.

Observation

Providing an example reduced ambiguity.

---

# Version 5 — Output Structure

Technique

Output Structure

Prompt

Return your answer in this format:

Architecture

Project Structure

Entities

Controllers

Services

Repositories

Validation

Testing

Output Summary

The response became easier to read.

Observation

Structured prompts produced structured answers.

---

# Version 6 — Step Decomposition

Technique

Step Decomposition

Prompt

Build the API step by step.

1. Design Architecture.

2. Define Entities.

3. Implement Repository.

4. Implement Service.

5. Implement Controller.

6. Add Validation.

7. Add Exception Handling.

Output Summary

The response became significantly more complete.

Observation

Breaking the task into steps improved completeness and quality.

---

# Cross-model Comparison

Claude

- Better explanations.
- Better architecture suggestions.
- More educational.

ChatGPT

- Faster.
- More direct.
- Better formatted code.

Failure Points

Claude sometimes generated overly detailed explanations.

ChatGPT occasionally skipped architectural reasoning.

---

# Final Prompt Template

You are an experienced software engineer.

Task:
{TASK}

Goal:
{GOAL}

Context:
{PROJECT CONTEXT}

Requirements:
{REQUIREMENTS}

Return the answer in this structure:

1. Overview

2. Design

3. Implementation

4. Best Practices

5. Possible Improvements