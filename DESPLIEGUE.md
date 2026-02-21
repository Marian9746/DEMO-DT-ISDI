# 🚀 Despliegue en GitHub Pages - Guía Paso a Paso

## 📋 Archivos incluidos en tu proyecto

Tu proyecto ya está listo con todos los archivos necesarios:

- `index.html` - Página principal
- `digital-twin-demo.html` - Demo de turbina hidroeléctrica  
- `digital-twin-simulator.html` - Simulador de sensores y alertas
- `README.md` - Documentación del proyecto
- `_config.yml` - Configuración de GitHub Pages

## 🎯 Pasos para subir a GitHub Pages

### Paso 1: Crear repositorio en GitHub

1. Ve a [github.com](https://github.com) e inicia sesión
2. Haz clic en "New repository" o el botón "+"
3. Nombre sugerido: `demo-DT` 
4. Marca como "Public" (necesario para GitHub Pages gratuito)
5. NO marques "Add a README file" (ya tienes uno)
6. Haz clic en "Create repository"

### Paso 2: Subir archivos

**Opción A: Interfaz web (más fácil)**
1. En tu nuevo repositorio, haz clic en "uploading an existing file"
2. Arrastra todos los archivos de tu carpeta `demo DT` 
3. Escribe mensaje: "Initial commit - Digital Twins educational website"
4. Haz clic en "Commit changes"

**Opción B: Git desde terminal**
```bash
cd "C:\Users\maria\demo DT"
git init
git add .
git commit -m "Initial commit - Digital Twins educational website"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/demo-DT.git
git push -u origin main
```

### Paso 3: Activar GitHub Pages

1. Ve a la pestaña **"Settings"** de tu repositorio
2. Desplázate hasta la sección **"Pages"** en el menú lateral
3. En **"Source"**, selecciona **"Deploy from a branch"**
4. Elige branch: **"main"** 
5. Carpeta: **"/ (root)"**
6. Haz clic en **"Save"**

### Paso 4: Acceder a tu sitio web

- Tu sitio estará disponible en: `https://TU-USUARIO.github.io/demo-DT/`
- GitHub te mostrará la URL exacta en la sección Pages
- La primera vez puede tardar 5-10 minutos en estar activo

## ✏️ Personalización final

Antes de publicar, actualiza estos datos en los archivos:

### En `README.md`:
- Cambia `[your-username]` por tu usuario de GitHub
- Actualiza las URLs de ejemplo

### En `_config.yml`:
- Cambia `[username]` por tu usuario real de GitHub

### En `index.html` (ya actualizado):
- ✅ Ya dice "Marian Diaz" en lugar de "Eduard Torres"  
- ✅ La sección About ya está personalizada
- Solo actualiza la URL de LinkedIn si quieres

## 🎉 ¡Listo para usar!

Una vez desplegado, cualquier persona podrá:
- Acceder a `https://TU-USUARIO.github.io/demo-DT/`
- Usar las demos interactivas
- Aprender sobre Digital Twins
- Compartir el enlace con estudiantes

## 🔄 Actualizaciones futuras

Para hacer cambios:
1. Edita los archivos localmente
2. Súbelos nuevamente al repositorio 
3. Los cambios se publican automáticamente

¡Tu página web educativa de Digital Twins estará lista para usar en tu clase!