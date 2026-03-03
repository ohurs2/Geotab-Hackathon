# Fleet Health Autopilot

Fleet Health Autopilot is a lightweight Geotab add-in that automatically scans fleet databases and surfaces device health issues including:

- Not installed devices
- Low asset battery faults
- General device health conditions
- Fleet-level status overview

## Problem

Fleet managers often lack visibility into hidden device health issues across multiple databases. Manual checks are time-consuming and reactive.

## Solution

Fleet Health Autopilot provides:
- Automated scanning
- Clean visual reporting
- Structured email-ready summaries
- Actionable fleet insights in seconds

## Key Features

### 🤖 AI Chat Assistant
Embedded AI chatbot allows users to:
- Ask natural language questions about fleet health
- Investigate device issues conversationally
- Get contextual explanations of faults and anomalies

### 📬 Automated Email Notifications
- Structured health summaries
- Exception-based alerts
- Ready-to-send fleet status reports

### 🔐 Group & Security Aware
- Respects Geotab group structures
- Maintains security clearance boundaries
- Works across multi-database environments

### 🔥 Exception HotSpot
- Automatically clusters recurring issues
- Highlights high-risk vehicles
- Surfaces hidden operational blind spots

### ⚙ n8n Automated Workflows
- Triggers external automations
- Enables recurring health scans
- Connects fleet health data into broader operational pipelines

### 🔗 Native Geotab Integration
- Deep SDK integration
- Direct record links inside the add-in
- Seamless navigation back to Geotab entities

## How It Works

The add-in runs inside MyGeotab and:
1. Queries device and vehicle data
2. Identifies health anomalies
3. Displays structured health summaries
4. Generates email-ready reports

## Tech

- HTML
- Vanilla JavaScript
- Geotab SDK API
- Config-driven add-in architecture

## Architecture Overview

- Frontend: HTML + Vanilla JavaScript
- Platform: Geotab Add-In SDK
- AI Layer: Embedded conversational assistant
- Automation Layer: n8n webhook-triggered workflows
- Reporting Layer: Structured email generator
- Security Model: Group-aware, clearance-respecting queries

## Prompts Used

Development leveraged AI-assisted "vibe coding" workflows to:
- Architect device health detection logic
- Refactor UI animation and layout
- Structure structured health categorisation
- Improve reporting clarity

---

Built by Owen Hurst
