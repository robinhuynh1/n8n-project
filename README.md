# Cybersecurity News Briefing Bot

An automated cybersecurity intelligence bot that collects news, summarizes it using Gemini Flash Lite, evaluates severity, and posts a concise briefing into a Discord server. The workflow is orchestrated entirely through n8n.

## What It Does
- Scrapes cybersecurity news from multiple sources
- Extracts key details from each article
- Uses Gemini Flash Lite to generate a short, readable summary
- Assigns a severity score based on keywords and context
- Sends the final briefing to a Discord channel for quick review

## Why I Built It
Cybersecurity news moves fast. This bot reduces noise by turning long articles into short, ranked briefings that can be reviewed in seconds.

## Tools Used
- **n8n** for automation and workflow logic  
- **Gemini Flash Lite** for AI-powered summarization  
- **Discord** for delivering briefings to my server  

## Future Improvements
- Add more news sources
- Improve severity scoring logic
- Add tagging (e.g., ransomware, data breach, vulnerability)
- Add more features to the Discord server (unknown as of right now)
