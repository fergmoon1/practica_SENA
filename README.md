# 🚀 Mi Primer Proyecto en GitHub 🚀

## 📝 Descripción
Este es mi primer proyecto utilizando Git y GitHub para control de versiones. Aquí estoy aprendiendo las mejores prácticas de versionamiento de código y colaboración en proyectos de software.

## 🛠️ Comandos Básicos de Git

### Configuración Inicial
```bash
# Configurar nombre de usuario
git config --global user.name "Tu Nombre"

# Configurar email
git config --global user.email "tu@email.com"
```

### Comenzando un Proyecto
```bash
# Inicializar un repositorio
git init

# Conectar con repositorio remoto
git remote add origin https://github.com/usuario/repositorio.git
```

### Flujo de Trabajo Diario
```bash
# Ver estado de archivos
git status

# Añadir archivos al área de preparación
git add archivo.txt    # Añadir archivo específico
git add .              # Añadir todos los archivos

# Crear un commit
git commit -m "Mensaje descriptivo del cambio"

# Actualizar repositorio local
git pull origin main

# Enviar cambios al repositorio remoto
git push origin main
```

### Ramas (Branches)
```bash
# Crear una nueva rama
git branch nueva-rama

# Cambiar a una rama
git checkout nueva-rama
# o con el comando moderno
git switch nueva-rama

# Crear y cambiar a una nueva rama
git checkout -b otra-rama
```

### Fusionar Cambios
```bash
# Fusionar rama con la rama actual
git merge nombre-rama

# Resolver conflictos si es necesario
```

## 📊 Visualización
```bash
# Ver historial de commits
git log
git log --oneline --graph

# Ver diferencias
git diff
```

## 🤝 Colaboración
```bash
# Clonar un repositorio
git clone https://github.com/usuario/repositorio.git

# Hacer fork desde GitHub
# (Botón en la interfaz web de GitHub)
```

## 💡 Consejos
- Haz commits frecuentes con mensajes claros
- Actualiza tu repositorio local antes de enviar cambios
- Utiliza ramas para desarrollar nuevas funcionalidades
- Revisa siempre los cambios antes de hacer commit

---

⭐ ¡No olvides dar una estrella a este repositorio si te ha sido útil! ⭐
