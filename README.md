# mini-link ✂️

> Acortador de URLs minimalista, rápido y sin registro.  
> Construido con HTML, CSS y JavaScript puro. Sin backend, sin base de datos.

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-brightgreen?logo=github)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-blue)
![No Backend](https://img.shields.io/badge/backend-none-lightgrey)

---

## ✨ Características

- 🔗 Acorta cualquier URL al instante
- 📋 Copia el link corto con un clic
- 🕓 Historial de los últimos 5 links (guardado localmente)
- 📱 Responsive — funciona en móvil y desktop
- 🌙 Dark mode automático
- ☁️ Sin servidores propios — usa la API pública de [is.gd](https://is.gd)
- ⚡ Sin dependencias — un solo archivo HTML
- 🔒 Sin tracking, sin cookies, sin registro

---

## 🚀 Demo

👉 ****

---

## 🛠️ Cómo usar la herramienta

1. Abrí la página web
2. Pegá cualquier URL larga en el campo de texto
3. Hacé clic en **Acortar URL** (o presioná `Enter`)
4. Copiá el link corto generado con el botón **Copiar**
5. ¡Listo! El link funciona en cualquier navegador del mundo

---

## 📦 Instalación local

Si querés correr el proyecto en tu computadora:

```bash
# 1. Clonar el repositorio
git clone https://github.com/mdefatimaperez/mini-link

# 2. Entrar a la carpeta

# 3. Abrir en el navegador
# Simplemente abrí el archivo index.html en tu navegador
# No necesita servidor, no necesita npm install
```

## 🔌 API utilizada

Este proyecto usa la API pública de **[is.gd](https://is.gd)**:

```
GET https://is.gd/create.php?format=json&url=TU_URL
```

Respuesta:

```json
{ "shorturl": "https://is.gd/abc123" }
```

No requiere API key. Límite de uso: uso razonable según [términos de is.gd](https://is.gd/terms.php).

---
## 📄 Licencia

Este proyecto está bajo la licencia **MIT**.  
Podés usarlo, modificarlo y distribuirlo libremente.

---
