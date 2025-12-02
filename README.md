# Comandos básicos de Git y GitHub

Chuleta rápida para trabajar con Git y subir proyectos a GitHub.

---

## Flujo típico (crear repo y subir a GitHub)

```bash
# 1) Configurar Git (solo una vez por PC)
git config --global user.name "Tu Nombre"
git config --global user.email "tu_correo@example.com"

# 2) Inicializar repositorio en la carpeta del proyecto
git init

# 3) Ver estado de archivos
git status

# 4) Añadir archivos al commit
git add .          # todos los archivos

# 5) Crear commit
git commit -m "Primer commit"

# 6) Conectar con repositorio remoto (GitHub)
git remote add origin https://github.com/USUARIO/NOMBRE-REPO.git
git remote -v      # ver remotos configurados

# 7) Subir a GitHub (rama main)
git push -u origin main
