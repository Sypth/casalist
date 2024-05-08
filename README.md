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
# Installing Vite and Vue
1. Open the project on the available code editor e.g VsCode
2. On the VsCode terminal, run this command: npm install --save-dev vue @vitejs/plugin-vue
3. Once the installation is complete, open 'vite.config.js' file to add vue to the plugins.
Just copy and paste this inside the plugins next to the laravel plugin if it's not exist:
    "vue({
            template: {
                base: null,
                includeAbsolute: false
            }
        })"
4. To run Vue locally using Vite, run this command in the terminal:
    npm run dev

# Installing Inertia JS
1. On the Vs Code terminal, run this commands:
    -   composer require inertiajs/inertia-laravel
    -   npm install @inertiajs/vue3

    For the full guide on how to setup Inertia: https://inertiajs.com/client-side-setup

# Adding ESLint (Optional)

# Adding Laravel Debugger(Optional)
    Full Guide: https://github.com/barryvdh/laravel-debugbar#installation

# Adding Laravel IDE Helper (Optional)
    Full Guide: https://github.com/barryvdh/laravel-ide-helper#installation
```

## Useful Commands
-   php artisan serve
-   npm run dev
-   php artisan route:clear
-   php artisan route:list
-   php artisan optimize
-   composer dump-autoload
-   docker compose up

