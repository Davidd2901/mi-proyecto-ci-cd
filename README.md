# mi-proyecto-ci-cd

Proyecto de práctica para la asignatura Gestión y Configuración del Software (Universidad de Guayaquil).

Estructura del proyecto:
- .github/workflows/ci.yml
- src/index.js
- src/index.test.js
- package.json

Instrucciones rápidas (Windows - Git Bash):

1. Descomprime el ZIP y entra a la carpeta del proyecto:
   cd entrega_ci_cd_salomondavid

2. Inicializa git y sube al repositorio (reemplaza <tu_usuario>):
   git init
   git add .
   git commit -m "Proyecto CI/CD inicial"
   git branch -M main
   git remote add origin https://github.com/<tu_usuario>/mi-proyecto-ci-cd.git
   git push -u origin main

3. Cuando Git solicite autenticación, usa tu usuario y en la contraseña pega el Personal Access Token (PAT) generado en https://github.com/settings/tokens (permiso repo + workflow).

Ejecutar pruebas localmente:
- Instala dependencias: npm install
- Ejecuta: npm test
