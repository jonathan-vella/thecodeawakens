# 🛠️ Demo 03: Droid Deployment & File Ops

## Part A: Azure Extension

**Mode**: Copilot for Azure

**Prompts**:
```
Could you help me create and deploy a simple Flask website by using an azd template?
@azure Before I execute azd init, what does it do?
@azure What resources are created with this template?
@azure Are there any cost-saving tips for running this app on Azure?
@azure how can i make this application highly available?
@azure How do I undeploy this website?
```

**Expected Output**:
- Step-by-step guidance for initializing an `azd` template and deploying a Flask application to Azure.
- Clear explanations of `azd` commands and the Azure resources being provisioned.
- Actionable advice on cost optimization and high availability for the deployed application.
- Instructions for de-provisioning the Azure resources.

**Key Capability**: Azure deployment guidance, `azd` workflow assistance, and Azure best practices consultation.

## Part B: File Operations Script

**Mode**: Ask mode

**Boosted Prompt**:
```
I need 1 powershell script to create 100 random folders with 100 random files; file size must vary between a few kb to a max 50mb.
I need another powershell script to automate file operations such as copying, moving, deleting, compressing, and extracting while capturing metrics for each operation, including duration, data size, and throughput. Operations should be split into 2 options - 1 for copying, moving, deleting; 2 for compressing, and extracting.
```

**Expected Output**:
- Two functional PowerShell scripts:
    1.  A script to generate a specified number of folders and files with random sizes.
    2.  A script to perform file operations (copy, move, delete, compress, extract) with performance metrics logging.

**Purpose**:  
Demonstrate Copilot for Azure's assistance with deployment workflows and advanced PowerShell scripting capabilities for automation tasks.

**Key Capability**: Complex script generation (PowerShell), task automation logic, and integration of performance metrics.
