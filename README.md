# 🏐 BlackNova League - Official Website

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?logo=github)](https://github.com)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Sitio web oficial de **BlackNova League**, la liga competitiva más prestigiosa de VolleyBall Legends en Roblox.

![BlackNova League Banner](https://via.placeholder.com/1200x400/1a0d2e/d946ef?text=BlackNova+League)

---

## 🌟 Características

- ✅ **Diseño Responsive** - Perfectamente adaptado para móviles, tablets y desktop
- 🎨 **Colores Personalizados** - Gradientes morados, rosas y rojos
- ❄️ **Efectos Visuales** - Nieve animada y partículas brillantes
- 📱 **Menú Móvil** - Navegación hamburguesa funcional
- ⚡ **Animaciones Suaves** - Transiciones CSS optimizadas
- 🏆 **Secciones Completas**:
  - Guía de Ingreso (6 pasos)
  - Reglas de la Liga (6 reglas expandibles)
  - Anuncios y Noticias
  - Calendario de Partidos (Oficiales/Amistosos/Resultados)
  - Clubs Registrados
  - Divisiones y Clasificaciones
  - Redes Sociales

---

## 🚀 Cómo Publicar en GitHub Pages

### Paso 1: Crear Repositorio en GitHub

1. Ve a [GitHub](https://github.com) e inicia sesión
2. Click en el botón **"New"** (o **"+"** → **"New repository"**)
3. Nombre del repositorio: `blacknova-league` (o el nombre que prefieras)
4. Descripción: `Official website for BlackNova League - VolleyBall Legends`
5. Selecciona **"Public"**
6. ✅ Marca **"Add a README file"**
7. Click en **"Create repository"**

### Paso 2: Subir los Archivos

**Opción A: Usando la interfaz web de GitHub**

1. En tu repositorio, click en **"Add file"** → **"Upload files"**
2. Arrastra el archivo `index.html` a la página
3. Escribe un mensaje de commit: `Initial commit - BlackNova League website`
4. Click en **"Commit changes"**

**Opción B: Usando Git (línea de comandos)**

```bash
# Clona tu repositorio
git clone https://github.com/TU_USUARIO/blacknova-league.git
cd blacknova-league

# Copia el archivo index.html a la carpeta
# (coloca tu index.html en esta carpeta)

# Agrega, commitea y sube
git add index.html
git commit -m "Initial commit - BlackNova League website"
git push origin main
```

### Paso 3: Activar GitHub Pages

1. En tu repositorio, ve a **"Settings"** (Configuración)
2. En el menú lateral, busca **"Pages"**
3. En **"Source"**, selecciona **"main"** (o **"master"**) branch
4. En **"Folder"**, deja **"/ (root)"**
5. Click en **"Save"**
6. ⏳ Espera 1-2 minutos...
7. 🎉 Tu sitio estará disponible en: `https://TU_USUARIO.github.io/blacknova-league/`

---

## 🔧 Personalización

### Cambiar Enlaces (IMPORTANTE)

Busca en `index.html` los comentarios marcados con `🔴 IMPORTANTE` y reemplaza:

#### 1. Discord (aparece 4 veces)
```html
<!-- Busca esto: -->
<a href="https://discord.gg/TU_SERVIDOR">

<!-- Reemplaza con tu servidor: -->
<a href="https://discord.gg/abc123xyz">
```

**Cómo obtener el link de Discord:**
1. Abre Discord → Tu servidor
2. Click derecho en el nombre del servidor
3. "Configuración del servidor" → "Invitaciones"
4. "Crear invitación"
5. ⚠️ **Importante:** Marca "Nunca caduca" y "Sin límite de usos"
6. Copia el código (ejemplo: `abc123xyz`)

#### 2. YouTube
```html
<a href="https://youtube.com/@TU_CANAL">
```

#### 3. Twitter/X
```html
<a href="https://twitter.com/TU_CUENTA">
```

#### 4. Instagram
```html
<a href="https://instagram.com/TU_CUENTA">
```

#### 5. TikTok
```html
<a href="https://tiktok.com/@TU_CUENTA">
```

#### 6. Link del Juego de Roblox
```html
<a href="https://www.roblox.com/games/TU_GAME_ID">
```

#### 7. Email
```html
<a href="mailto:blacknova@league.com">
```

### Búsqueda Rápida

Usa `Ctrl + F` (o `Cmd + F` en Mac) y busca:
- `TU_SERVIDOR`
- `TU_CANAL`
- `TU_CUENTA`
- `TU_GAME_ID`
- `🔴 IMPORTANTE`

---

## 📱 Compatibilidad

✅ **Móviles** - iPhone, Android (todos los tamaños)
✅ **Tablets** - iPad, Android tablets
✅ **Desktop** - Windows, Mac, Linux
✅ **Navegadores** - Chrome, Firefox, Safari, Edge

---

## 🎨 Paleta de Colores

| Color | Hex | Uso |
|-------|-----|-----|
| 💜 Morado | `#6a0dad` | Color principal |
| 💖 Magenta | `#d946ef` | Acentos brillantes |
| 🌸 Rosa | `#ec4899` | Secundario |
| ❤️ Rojo | `#dc2626` | Detalles |
| 🌹 Rose | `#ff006e` | Neón |
| 🖤 Negro | `#0a0e1a` | Fondo |

---

## 📁 Estructura del Proyecto

```
blacknova-league/
├── index.html          # Página principal (TODO EN UNO)
└── README.md          # Este archivo
```

**Nota:** Todo el CSS y JavaScript están incluidos dentro de `index.html` para facilitar el despliegue.

---

## 🐛 Solución de Problemas

### Problema: La página no se muestra después de activar GitHub Pages
**Solución:** Espera 5-10 minutos. GitHub necesita tiempo para construir y publicar tu sitio.

### Problema: Los enlaces no funcionan
**Solución:** Verifica que hayas reemplazado todos los placeholders (`TU_SERVIDOR`, `TU_CUENTA`, etc.)

### Problema: El diseño se ve roto en móvil
**Solución:** Asegúrate de que el archivo `index.html` esté completo y no haya sido modificado incorrectamente.

### Problema: Las reglas no se despliegan
**Solución:** Verifica que el JavaScript al final del archivo esté intacto.

---

## 🔄 Actualizar el Sitio

1. Edita tu archivo `index.html` localmente
2. Sube los cambios a GitHub:

```bash
git add index.html
git commit -m "Actualización: descripción del cambio"
git push origin main
```

3. Los cambios aparecerán en tu sitio en 1-2 minutos

---

## 📊 Analytics (Opcional)

Si quieres trackear visitantes, puedes agregar Google Analytics:

1. Crea una cuenta en [Google Analytics](https://analytics.google.com)
2. Obtén tu código de seguimiento
3. Agrega el código antes de `</head>` en tu `index.html`

---

## 🎯 Dominio Personalizado (Opcional)

Si quieres usar un dominio propio (ejemplo: `blacknovaleague.com`):

1. Compra un dominio en Namecheap, GoDaddy, etc.
2. En GitHub Pages settings, ingresa tu dominio personalizado
3. Configura los DNS de tu dominio:
   ```
   Type: A
   Host: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   ```

---

## 📞 Soporte

- **Problemas con GitHub:** [GitHub Support](https://support.github.com/)
- **Dudas sobre HTML/CSS:** [MDN Web Docs](https://developer.mozilla.org/)
- **Comunidad:** Stack Overflow

---

## 📄 Licencia

Este proyecto es de código abierto. Siéntete libre de usarlo y modificarlo para tu propia liga.

---

## 🏆 Créditos

Diseñado y desarrollado para **BlackNova League** - VolleyBall Legends Community

**¿Te gustó el diseño?** ⭐ Dale una estrella al repositorio!

---

## 🚀 ¡Tu Sitio Está Listo!

URL de tu sitio: `https://TU_USUARIO.github.io/blacknova-league/`

¡Comparte este link con tu comunidad! 🏐💜

---

**Última actualización:** Febrero 2026
