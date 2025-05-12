# 🗄️ Demo 04: Galactic N-Tier Application

**Mode**: Ask mode, Edit Mode, Agent mode

**Prompts**:
```
git clone https://github.com/Azure-Samples/azure-sql-db-django
@azure Please recommend Azure services for my project.
@azure Please use Azure App Service instead of Azure Container App for my project.
@azure Why would I use Azure Cosmos DB instead of Azure SQL?
@azure replace the sql db with a Cosmos DB
@azure The SERVICE_URL value should be bing.com; also add an environment variable STAGE=dev to my project.
@azure Let's use GitHub to deploy my app to Azure. Set up a GitHub Actions pipeline to deploy my app to Azure.
```

**Reminders**:
- ⚠️ **Switch model!** Can I get well architected recommendations for my app?
- ⚠️ **Switch to agent mode** 

**Boosted Agent Mode Prompt**:
```
update the readme file so that it has more info including structure and purpose and also add a mermaid chart
```

**Expected Output**:
- Recommendations for Azure services suitable for the Django application.
- Explanation of the benefits of Cosmos DB over Azure SQL for specific scenarios.
- Guided code modifications to migrate the Django app from Azure SQL to Cosmos DB.
- Assistance in configuring Azure App Service environment variables.
- A generated GitHub Actions workflow file for CI/CD.
- An updated README file with project details and a Mermaid architecture diagram.

**Purpose**:  
Showcase Copilot's ability to guide architectural decisions, database migrations, environment configuration, and CICD setup with different levels of intelligent assistance.

**Key Capability**: Architectural guidance, database migration assistance, multi-step code modification, CI/CD pipeline generation, and documentation update (Agent Mode).
