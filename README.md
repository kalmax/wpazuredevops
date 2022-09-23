# wpazuredevops

-----ACR *******/
1.APP root: app
Dockerfile path: app/Dockerfile

### Build pipeline
auzre-pipelines/auzre-pipelines-1.yml

### Release pipeline
templates/deploy/template.jon
Azure CLI command: az mysql flexible-server parameter set --name require_secure_transport --resource-group numotionWPRGDEV --server-name numotionwpdbdev --value OFF

### Blob Container setup
Go to wordpress site
User: admin Pass: admin@1234
Settings->Microsoft Azure plugin
Go to azure portal->AppService->Configuration->Application Settings
Copy MICROSOFT_AZURE_ACCOUNT_KEY value and add to plugin 
Copy MICROSOFT_AZURE_ACCOUNT_NAME value and add to plugin
Enable Use for default upload checbox



