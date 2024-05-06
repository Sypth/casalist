# Casalist

## Prerequisites

Before setting up the project, make sure you have the following prerequisites installed:

-   PHP (Version 8.*)
-   Node.js (Latest version)
-   Composer (Latest version)
-   Inertia.js (Latest version)
-   Vue3 (Latest version)
-   Laravel (Version 10.*)
-   Tailwind (Latest version)
-   Docker Desktop (Latest version)

## Setup Project

Follow these steps and run the provided commands to set up the project:
```bash
# Step 1: Installing Vite and Vue using CMD Terminal
1. Open the project on the available code editor e.g VsCode
2. On the VsCode terminal, run this command: npm install --save-dev vue @vitejs/plugin-vue
3. Once the installation is complete, open 'vite.config.js' file to add vue to the plugins.
Just copy and paste this inside the plugins next to the laravel plugin:
    vue({
            template: {
                base: null,
                includeAbsolute: false
            }
        })
```

