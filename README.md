## Prerequisites

Before you begin, make sure you have the following:

- An **Azure subscription**.
- **Python 3.7 or later**.
- A Python installation that includes **pip**. To verify, run:

  ```bash
  pip --version
  ```

- The Azure Document Intelligence SDK:

  ```bash
  pip install azure-ai-documentintelligence==1.0.2
  ```

- The latest version of **Visual Studio Code**, or your preferred IDE.
- A **Document Intelligence** resource in Azure.
- The **Cognitive Services User** role assigned to your Microsoft Entra ID (AAD) identity for the target Document Intelligence resource.

## Authentication

This project uses **Microsoft Entra ID (AAD)** authentication.
