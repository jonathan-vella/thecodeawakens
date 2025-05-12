# 🧠 Demo 05: R2-D2 RAG App

**Mode**: Copilot for Azure

**Prompts**:
```
@azure i want to build a RAG app using next.js and llamaindex.ts. Can you help me find a sample and deploy it to aca?
lnk https://github.com/Azure-Samples/llama-index-javascript
azd up
```
- 💡 **Pro Tip**: Consider using the [Prompt Boost](https://marketplace.visualstudio.com/items?itemName=chrisdias.promptboost) extension to enhance your prompt.

**Boosted Prompt**:
```
Use the code from https://github.com/Azure-Samples/llama-index-javascript and guide me through deploying it to Azure, following these best practices:

Clone and set up the sample application.
Configure required environment variables (including Azure OpenAI credentials).
Test the app locally to ensure it works.
Deploy to Azure using a recommended method (App Service, Container Apps, or Static Web Apps).
Apply Azure best practices: use managed identities, store secrets in Azure Key Vault, enable monitoring/logging, and use deployment slots if available.
Provide step-by-step PowerShell commands for Windows.
Highlight any prerequisites or Azure resource setup needed.
```

**Expected Output**:
- Guidance on finding and cloning the sample RAG application.
- Step-by-step instructions for configuring environment variables, including Azure OpenAI credentials.
- Assistance with local testing procedures.
- A recommended Azure deployment strategy (e.g., Azure Container Apps).
- PowerShell commands for each step of the setup and deployment process.
- Clear articulation of Azure best practices (Managed Identities, Key Vault, Monitoring, Deployment Slots) applied to the RAG application.

**Purpose**:  
Demonstrate Copilot's ability to guide through modern AI application deployment following Azure best practices.

**Key Capability**: AI application deployment guidance, Azure best practices integration, environment configuration for AI services, and step-by-step procedural instruction.
