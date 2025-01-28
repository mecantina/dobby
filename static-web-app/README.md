# FILE: /static-web-app/static-web-app/README.md
# This file contains documentation for the static web app project.

# Static Web App Documentation

## Overview
This project is a static web app that includes a simple HTML structure and CSS styles. It serves as a template for further development.

## Project Structure
```
static-web-app
├── src
│   ├── index.html        # HTML structure of the static web app
│   └── styles
│       └── styles.css    # CSS styles for the static web app
├── main.bicep            # Bicep template for deploying the static web app
└── README.md             # Documentation for the project
```

## Deployment Instructions
1. Ensure you have the Azure CLI and Bicep installed.
2. Navigate to the directory containing the `main.bicep` file.
3. Run the following command to deploy the static web app:
   ```
   az deployment group create --resource-group <your-resource-group> --template-file main.bicep
   ```
4. Replace `<your-resource-group>` with the name of your Azure resource group.

## Additional Information
For more details on how to customize the static web app, refer to the `src/index.html` and `src/styles/styles.css` files.