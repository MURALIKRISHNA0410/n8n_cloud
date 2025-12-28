# n8n Cloud Deployment

This repository is ready to deploy n8n on Render.com free Node.js service without Docker.

## Setup Instructions

1. Connect this repo to Render.com
2. Runtime: Node.js
3. Build Command: `npm install`
4. Start Command: `npm start`
5. Add environment variable:
   - `N8N_USER_FOLDER=/opt/render/n8n-data`
6. Optional for security:
   - `N8N_BASIC_AUTH_ACTIVE=true`
   - `N8N_BASIC_AUTH_USER=<username>`
   - `N8N_BASIC_AUTH_PASSWORD=<password>`
