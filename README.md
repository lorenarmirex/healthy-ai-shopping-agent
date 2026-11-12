
# Healthy Shopping AI Agent

A multi-agent AI system designed to help users make healthier grocery shopping decisions while staying within their budget.

## Project Overview

The Healthy Shopping AI Agent was developed as a Software Engineering II (CS 351) team project at Kean University.

The system uses multiple AI agents to process user preferences and generate personalized grocery recommendations.

### User Inputs
- Shopping budget
- Dietary restrictions
- Diet preferences
- Health and nutrition goals

### System Output
- Personalized grocery recommendations
- Nutritional considerations
- Budget-aware shopping suggestions

## Technologies

- n8n — Workflow automation
- Google Gemini — AI language model
- AI Agents — Task-specific decision making
- Calculator — Budget calculations

## Multi-Agent Architecture

The system consists of three specialized agents:

### 1. Planner Agent
Interprets user requests and extracts shopping preferences, dietary requirements, and budget constraints.

### 2. Nutritional Agent
Evaluates dietary needs and recommends appropriate grocery items.

### 3. Budget Agent
Reviews the suggested items and uses calculations to keep recommendations within the user's budget.

## Workflow

Chat Trigger
    ↓
Google Gemini
    ↓
Planner Agent
    ↓
Nutritional Agent
    ↓
Budget Agent + Calculator
    ↓
Personalized Shopping Recommendations

## Project Goals

- Make healthy grocery shopping more accessible
- Support personalized dietary preferences
- Help users manage their grocery budget
- Demonstrate multi-agent AI collaboration

## Team

- Lorena Ramirez
- Carlos Nunez

## Course

CS 351 — Software Engineering II
