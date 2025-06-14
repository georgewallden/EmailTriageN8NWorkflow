# EmailTriageN8NWorkflow

This repository contains the JSON configuration for an N8N workflow designed to automatically triage, filter, and categorize my personal emails to improve productivity.

## The Problem
I was receiving a high volume of daily emails, including newsletters, alerts, and personal messages. Manually sorting through them was time-consuming and led to missed high-priority communications.

## The Solution
This N8N workflow connects to my Gmail account via API and runs on a schedule. It automatically processes each new email using a series of conditional logic checks to:
-   Archive low-priority newsletters and promotional content.
-   Apply specific labels to emails from key senders (e.g., "Work," "Family").
-   Identify urgent emails based on keywords (e.g., "urgent," "action required") and send a push notification to my phone.
-   Star important messages so they are easy to find later.

## Key Technologies
-   **N8N:** The core automation platform.
-   **Gmail API:** For reading and managing emails.
-   **Slack API:** For sending real-time alerts.

## Visualization
Here is a screenshot of the workflow canvas in N8N:

![N8N Workflow Screenshot](path/to/your/screenshot.png) 
*(**Pro-tip:** Taking a screenshot of the N8N visual editor and including it here is extremely effective!)*

## How to Use
1.  Download the `workflow.json` file.
2.  In your N8N instance, choose "Import from File."
3.  Select the downloaded JSON file.
4.  Update the credentials for the Gmail and notification nodes.
