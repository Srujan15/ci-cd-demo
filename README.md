# CI/CD Demo: Node.js App to Azure

This is a demo project showing how to set up an end-to-end CI/CD pipeline using GitHub Actions to deploy a simple Node.js app to Azure App Service.

## Tech Stack

- Node.js (Express)
- GitHub Actions
- Azure App Service

## CI/CD Pipeline

- Trigger: Push to `main`
- Steps:
  - Install dependencies
  - Package app
  - Deploy to Azure

## Deploy

1. Create Azure App Service
2. Add GitHub repo secrets:
   - `AZURE_WEBAPP_NAME`
   - `AZURE_PUBLISH_PROFILE`
3. Push to `main` → App is deployed



