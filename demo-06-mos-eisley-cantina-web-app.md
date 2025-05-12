# ☕ Demo 06: Mos Eisley Cantina Web App

**Mode**: Agent mode

**Prompts**:
```
I am the owner of a coffee shop in Amsterdam. Iwant to create a web app in app service.
```

**Boosted Prompt**:
```
I am the owner of a coffee shop in Amsterdam.
@azure i want to create a web app in app service.
i will use this web app to take orders of coffee from my customers.
customer data will be stored in azure sql database. the database will store first name, last name, username, email, preferred delivery address, marketing preference.
the web app must be vnet integrated and use the second cheapest tier. i want to use dot net core and integrate my app with application insights.
all secrets must be stored in keyvault.
the code you will create must be in bicep, and you have to apply best practices.
you need to include a github cicd pipeline, a markdown file explaining the pipeline and instructions how to configure it plus a mermaid chart which displays the entire flow.
i need you to design my website. remember that my site is for customers to order coffee. add the following: a catchy title, a description, a sign up form, an order form, an option to join a marketing list.
you need to find and add relevant images. you need to help me upload these files to my site.
```

**Additional Prompts**:
```
help me deploy this to azure in Sweden central
```

**Expected Output**:
- Bicep templates for the Azure infrastructure (App Service with VNet integration, Azure SQL Database, Key Vault, Application Insights).
- .NET Core application code for the coffee shop web app, including frontend (HTML/CSS/JS for forms and layout) and backend logic for order processing and database interaction.
- A GitHub Actions CI/CD pipeline YAML file.
- A Markdown file explaining the pipeline setup and deployment instructions.
- A Mermaid diagram visualizing the application architecture and deployment flow.
- Guidance on deploying to a specific Azure region (Sweden Central) and setting up GitHub Dependabot.

**Purpose**:  
Showcase full-stack application design, infrastructure-as-code with Bicep, CICD pipeline setup, and deployment best practices.

**Key Capability**: Full-stack application generation, Infrastructure-as-Code (Bicep), CI/CD pipeline design, UI/UX considerations, and integration of multiple Azure services.
