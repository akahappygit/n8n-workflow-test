# AI Lead Scraper (n8n)

Automation workflow built using n8n.

## Features  
Webhook-based API trigger
Dynamic input handling
End-to-end automation workflow
Cloud deployment using Railway

## Tech Stack
n8n (workflow automation)
Docker (containerization)
Railway (deployment)
Webhooks / APIs

## Workflow
See [Workflow JSON](./workflows/Lead%20Scraper.json)

##  Live Demo API 
Endpoint
https://n8n-production-3c1c.up.railway.app/webhook/demo
Method
GET
Sample Response
{
  "status": "success",
  "project": "AI lead scrapper",
  "message": "Workflow is live"
}

##  Note
Live Production link : https://n8n-production-3c1c.up.railway.app
Credentials are not included for security reasons.
Please configure your own API keys before running.
