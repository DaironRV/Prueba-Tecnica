# Astro Starter Kit: Basics

1. Clona el repositorio en tu máquina local:
    ```bash
    git clone https://github.com/DaironRV/Django_Prueba_Tecnica.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd Prueba_Tecnica
    ```
3. Levanta el servidor de Astro
    ```bash
    npm run dev
    ```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/DaironRV/Prueba-Tecnica/blob/main/public/LibreriaSMD.jpg)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── .astro/                # Archivos temporales generados por Astro
├── .vscode/               # Configuración de VS Code
├── node_modules/          # Dependencias de Node.js
├── public/                # Archivos estáticos como imágenes y favicon
│   └── favicon.svg
├── src/                   # Código fuente principal
│   ├── assets/            # Archivos estáticos y multimedia
│   ├── components/        # Componentes reutilizables
│   │   ├── Footer.astro
│   │   ├── HeaderButton.astro
│   │   ├── Init.astro
│   │   ├── Library.astro
│   ├── layouts/           # Diseños base del proyecto
│   │   └── Layout.astro
│   ├── pages/             # Páginas individuales
│   │   └── index.astro
│   ├── styles/            # Archivos de estilos
│   │   └── global.css
├── .gitignore             # Archivos ignorados por Git
├── astro.config.mjs       # Configuración de Astro
├── package-lock.json      # Archivo de control de versiones de dependencias
├── package.json           # Información del proyecto y dependencias
├── README.md              # Documentación del proyecto
└── tsconfig.json          # Configuración de TypeScript

```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
