# 🚀 Strapi Setup & Task-1 Completion

This repository contains the setup, configuration, and exploration of the Strapi Monorepo as part of the **Pearlthoughts_1** assignment.

## 📋 Prerequisites

Before running the project, ensure the following tools are installed and verified:

* **Node.js v20.x**: `node -v`
* **npm**: `npm -v`
* **Git**: `git --version`
* **VS Code** (IDE)

---

## 🛠️ Step-by-Step Setup Guide

### 1. Project Directory Setup
The project is organized in the following directory structure:
```text
D:\Pearlthoughts_1\taskone
2. InstallationOpen your terminal in VS Code (PowerShell) and execute the following commands:Clone the official Strapi monorepo:Bashgit clone [https://github.com/strapi/strapi.git](https://github.com/strapi/strapi.git)
cd strapi
3. Repository ExplorationThe Strapi architecture consists of the following key directories:DirectoryDescriptionpackages/Core Strapi packagespackages/core/strapiMain framework logicpackages/plugins/Official pluginsexamples/Sample Strapi applicationstests/Test casesdocs/Documentation💻 Running the Application1. Navigate to Example AppWe use the getstarted example provided in the repo:Bashcd examples/getstarted
2. Install DependenciesBashnpm install
3. Start the ServerBashnpm run develop
Success:✔ Strapi server starts successfully✔ Backend running on port 1337⚙️ Configuration & Content Management1. Admin PanelURL: http://localhost:1337/adminAction: Created Admin account and accessed Dashboard.2. Content Type CreatedA new collection type named Article was created using the Content-Type Builder.Fields:title (Text)description (Rich Text)3. DatabaseType: SQLite (Default)Status: Automatically configured by Strapi.🔗 API VerificationThe API was tested to ensure the content is accessible.Endpoint: http://localhost:1337/api/articlesResult: ✔ API returns created content successfully.📹 Video DemonstrationLoom Video Link: [Insert Your Loom Link Here]Contents:Folder structure walkthroughStrapi running locallyAdmin panel overviewContent type creationAPI response checkGitHub repository verification📦 Version ControlThe project is tracked using Git with the following workflow:Bash# Check branch
git branch

# Stage files
git add .

# Commit changes
git commit -m "Completed Strapi setup and Task-1"

# Push to Main (Direct Push)
git push -u origin main
