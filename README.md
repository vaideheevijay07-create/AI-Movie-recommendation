# AI Movie Recommendation Agent

## Project Overview

This project uses n8n and AI to recommend movies based on a user's preferred genre.

## Workflow

Webhook → AI Agent → Structured Output Parser → Respond to Webhook

## Input Example

{
"genre": "Sci-Fi"
}

## Output Example

{
"movies": [
{
"movie_name": "The Matrix",
"release_year": "1999",
"description": "A hacker discovers reality is a simulated construct and joins a rebellion."
}
]
}

## Technologies Used

* n8n
* OpenAI Chat Model
* Structured Output Parser
* Webhooks

## Features

* Accepts genre input through a webhook
* Generates 5 AI-powered movie recommendations
* Returns structured JSON output
