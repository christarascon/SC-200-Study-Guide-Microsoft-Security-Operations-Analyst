## 🧪 Practice Labs & Hands-On

### Free Practice Environments

1. **Microsoft Learn Sandbox**
   - No credit card required
   - Temporary Azure environment
   - Guided exercises
   - [Start Learning](https://learn.microsoft.com/en-us/training/)

2. **Azure Free Account**
   - $200 credit for 30 days
   - Free services for 12 months
   - Always-free services
   - [Get Started](https://azure.microsoft.com/en-us/free/)

3. **Microsoft 365 Developer Program**
   - Free E5 developer tenant
   - Renewable every 90 days
   - Full feature access
   - [Sign Up](https://developer.microsoft.com/en-us/microsoft-365/dev-program)

### Recommended Lab Exercises

| Lab # | Topic | Duration | Link |
|-------|-------|----------|------|
| Lab 1 | Deploy and Configure Microsoft Sentinel | 2 hours | [Lab Guide](./Hands-On-Labs/lab-01-sentinel-deployment.md) |
| Lab 2 | Configure Data Connectors | 1.5 hours | [Lab Guide](./Hands-On-Labs/lab-02-data-connectors.md) |
| Lab 3 | Create Analytics Rules | 2 hours | [Lab Guide](./Hands-On-Labs/lab-03-analytics-rules.md) |
| Lab 4 | Investigate Incidents | 2 hours | [Lab Guide](./Hands-On-Labs/lab-04-incident-investigation.md) |
| Lab 5 | Threat Hunting with KQL | 3 hours | [Lab Guide](./Hands-On-Labs/lab-05-threat-hunting.md) |
| Lab 6 | Configure Defender for Endpoint | 2 hours | [Lab Guide](./Hands-On-Labs/lab-06-defender-endpoint.md) |
| Lab 7 | Security Copilot Integration | 1.5 hours | [Lab Guide](./Hands-On-Labs/lab-07-security-copilot.md) |
| Lab 8 | Create Playbooks & Automation | 2.5 hours | [Lab Guide](./Hands-On-Labs/lab-08-playbooks.md) |

### Lab Setup Prerequisites

```bash
# Azure CLI Installation
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash

# PowerShell Installation
sudo apt-get install -y powershell

# Connect to Azure
az login
az account set --subscription "<subscription-id>"

# Install Required Modules
Install-Module -Name Az -AllowClobber -Scope CurrentUser
Install-Module -Name AzSentinel -Scope CurrentUser
