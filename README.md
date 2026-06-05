# GitHub Actions CI/CD 🚀

Pipeline de integración y despliegue continuo con GitHub Actions.
Cada push a main dispara automáticamente validación y deploy a GitHub Pages.

## Workflows

### 🔍 CI Pipeline (ci.yml)
- **Trigger:** push o pull_request a main
- **Pasos:** checkout código, verificar HTML, reportar resultado
- **Resultado:** build verde o rojo visible en GitHub

### 🚀 Deploy (deploy.yml)
- **Trigger:** push a main
- **Pasos:** checkout, configurar Pages, subir artefacto, desplegar
- **Resultado:** sitio actualizado automáticamente en GitHub Pages

## Flujo completo
git push → GitHub Actions dispara →
├── CI Pipeline: valida el código
└── Deploy: publica en GitHub Pages automáticamente
## Conceptos aplicados

- **CI/CD** — Integración y Despliegue Continuo
- **Workflow YAML** — definición del pipeline como código
- **Triggers** — eventos que disparan el pipeline (push, PR)
- **Jobs y Steps** — unidades de trabajo del pipeline
- **Actions** — pasos reutilizables del marketplace de GitHub
- **Artifacts** — archivos generados durante el pipeline
- **Environments** — entornos de despliegue con protecciones

## Ver en vivo

🔗 https://10101985.github.io/github-actions-cicd

## Tecnologías

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat&logo=yaml&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-181717?style=flat&logo=github&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)

## Autor
Cristian Robledo Macleood — [LinkedIn](https://www.linkedin.com/in/cristian-robledo-macleood-7538331b5/) | [Portfolio](https://10101985.github.io/web-portfolio-personal)
