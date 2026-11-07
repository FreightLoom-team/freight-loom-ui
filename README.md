# Freight Loom UI (Client Platform)

This repository houses the hybrid mobile and web application client runtime interface for the Freight Loom logistics system. The application is built using the Angular framework running inside an Ionic framework container with a Capacitor native mobile wrapper.
### FreightLoom PostgreSQL database
## 🛠️ Global Prerequisites

Before checking out the repository code, your local machine must match our strict enterprise development toolchain bounds. 

Open your native command terminal (macOS Terminal or Windows PowerShell) and run this check:

```bash
node -v
```

### 🔍 Does it match?
* **If it returns `v24.X.X` (starts with 24):** It MATCHES. You can skip the version manager steps below and go straight to the Quick Start Guide.
* **If it returns anything else (like v18, v20, or v22):** It DOES NOT MATCH. You must run the version manager steps below before doing anything else.

---

### 🍏 Node Version Management (macOS)
If your version does not start with 24, run these commands to switch your engine:

```bash
nvm install 24.15.0 && nvm use 24.15.0
```

### 🪟 Node Version Management (Windows)
Windows does not support the native `nvm` script engine. Windows developers must download and use the standalone installer tool.

* **Tool Required:** [nvm-windows](https://github.com)
* **Command Sequence (Run as Administrator):**

```text
nvm install 24.15.0
nvm use 24.15.0
```

---

## 🚀 Quick Start Guide

To initialize, compile, and execute the development server locally, execute this cohesive command block sequentially inside your terminal window:

```bash
git clone https://github.com
cd freight-loom-ui
npm install
npx ionic serve
```

Once the compilation engine finishes processing, your local web browser will automatically open up a live-tracking development view targeted at **`http://localhost:8100/home`**.

## 🔬 Local Validation Checkpoints

Once the application is running locally on your machine, complete these verification steps to guarantee your workspace container is completely functional:

1. **Hot-Reload Verification:** Open `src/app/home/home.page.html` in your editor, change any text line, and save the file. The terminal compilation window must instantly trigger a rebuild and update your browser window automatically.
2. **Developer Tools Mode:** Press `F12` (or `Cmd + Option + I` on macOS) inside your browser window. Toggle the **Device Toolbar** simulator icon to preview how the application layouts adjust seamlessly across responsive iPhone and Android mobile viewport screens.
3. **Environment Tracking Validation:** Open your browser console logs and verify that no connection failures are being thrown. The interface is pre-configured to look for a local Java Spring Boot API server operating over port `8080`.

## 🏗️ Architectural Folder Structure

```text
freight-loom-ui/
├── src/                       # Primary client source code layer
│   ├── app/                   # Modules, routing, components, and views
│   │   └── home/              # Main landing screen logic and views
│   ├── assets/                # Static application graphics and media
│   ├── environments/          # Target host API endpoint environment configurations
│   └── theme/                 # Global UI variables and styling sheets
├── .gitignore                 # Enterprise source control locks
├── .npmrc                     # Strict package version lock behaviors
├── package.json               # Third-party dependency manifests
└── tsconfig.json              # TypeScript compilation rules
```

## 🔒 Source Control Standards

All new contributions must strictly adhere to the project versioning guidelines. Our environment layout is protected by strict structural limits:

1. **Strict Version Locks:** The `.npmrc` profile enforces `save-exact=true`. Never use the `^` or `~` wildcards when adding packages to avoid compilation mismatches across the team.
2. **Editor Isolation:** Personal text editor configurations (such as `.vscode/` or `.idea/`) are locked out by the global `.gitignore` layout. Do not bypass the staging index profiles.
