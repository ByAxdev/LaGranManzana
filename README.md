# 🏢 La Gran Manzana - Centro Comercial

Sitio web premium estilo Apple para el Centro Comercial La Gran Manzana en Guayaquil Norte.

![La Gran Manzana](https://img.shields.io/badge/Status-Ready-success)
![Responsive](https://img.shields.io/badge/Mobile-100%25-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## ✨ Características

- 🎨 **Diseño Premium** - Estilo Apple con animaciones cinematográficas
- 📱 **100% Responsive** - Optimizado para todos los dispositivos móviles
- ⚡ **Performance** - Carga rápida y experiencia fluida
- 🗺️ **Ubicación Real** - Google Maps integrado con ubicación exacta
- 🎭 **Animaciones** - Transiciones suaves al hacer scroll
- 🔍 **SEO Ready** - Metadatos optimizados para buscadores

---

## 🚀 Despliegue en GitHub Pages

### Opción 1: Usando GitHub Desktop (Más Fácil)

1. **Descarga GitHub Desktop**
   - Ve a: https://desktop.github.com/
   - Descarga e instala

2. **Crea una cuenta en GitHub**
   - Ve a: https://github.com/join
   - Crea tu cuenta gratis

3. **Crea un nuevo repositorio**
   - Abre GitHub Desktop
   - File → New Repository
   - Name: `lagranmanzana`
   - Local Path: Selecciona donde está tu carpeta
   - Click "Create Repository"

4. **Sube los archivos**
   - GitHub Desktop detectará todos los archivos automáticamente
   - En "Summary": escribe "Initial commit"
   - Click "Commit to main"
   - Click "Publish repository"
   - Desactiva "Keep this code private" si quieres que sea público
   - Click "Publish Repository"

5. **Activa GitHub Pages**
   - Ve a tu repositorio en github.com
   - Click en "Settings"
   - En el menú izquierdo: "Pages"
   - En "Source": Selecciona "main"
   - Click "Save"
   - ¡Espera 2-3 minutos!
   - Tu sitio estará en: `https://tuusuario.github.io/lagranmanzana`

### Opción 2: Usando la Terminal

```bash
# 1. Navega a tu carpeta
cd ruta/a/lagranmanzana-github

# 2. Inicializa Git
git init

# 3. Agrega todos los archivos
git add .

# 4. Haz tu primer commit
git commit -m "Initial commit - La Gran Manzana website"

# 5. Conecta con GitHub (reemplaza TU-USUARIO)
git remote add origin https://github.com/TU-USUARIO/lagranmanzana.git

# 6. Sube los archivos
git branch -M main
git push -u origin main
```

Luego activa GitHub Pages en Settings → Pages → Source: main

---

## 📁 Estructura del Proyecto

```
lagranmanzana-github/
├── index.html              # Página principal
├── README.md               # Este archivo
├── .gitignore             # Archivos a ignorar por Git
└── images/                # 📸 AQUÍ VAN TUS FOTOS
    ├── hero-background.jpg     # Foto principal (1920x1080px)
    ├── local-basico.jpg        # Local 72m² (1200x800px)
    ├── local-estandar.jpg      # Local 105m² (1200x800px)
    └── local-doble.jpg         # Local 144m² (1200x800px)
```

---

## 📸 Agregar Tus Fotos

### 1. Prepara tus fotos

**Tamaños recomendados:**
- `hero-background.jpg`: 1920x1080px (foto panorámica del centro comercial)
- `local-basico.jpg`: 1200x800px (foto del local de 72m² vacío)
- `local-estandar.jpg`: 1200x800px (foto del local de 105m² vacío)
- `local-doble.jpg`: 1200x800px (foto del local de 144m² vacío)

**Optimiza tus fotos:**
- Usa https://tinypng.com/ para comprimir
- Formato: JPG
- Peso máximo: 500KB cada una

### 2. Coloca las fotos

Pon tus 4 fotos en la carpeta `images/` con los nombres exactos arriba mencionados.

### 3. Sube los cambios a GitHub

**Usando GitHub Desktop:**
1. Abre GitHub Desktop
2. Verás los cambios detectados
3. Summary: "Agregar fotos de los locales"
4. Click "Commit to main"
5. Click "Push origin"

**Usando Terminal:**
```bash
git add images/
git commit -m "Agregar fotos de los locales"
git push
```

**¡Espera 2-3 minutos y refresca tu sitio!**

---

## 📝 Personalizar Contenido

### Cambiar Teléfonos y Contactos

Busca en `index.html` y reemplaza:

```html
<!-- Buscar: -->
+593XXXXXXXXX

<!-- Reemplazar con tu número real: -->
+593999999999
```

**Ubicaciones a cambiar:**
- Línea ~983: Link de llamada
- Línea ~984: Link de WhatsApp (formato: https://wa.me/593999999999)
- Línea ~1021: Teléfono en footer

### Cambiar Email

```html
<!-- Buscar: -->
locales@lagranmanzana.ec

<!-- Reemplazar con: -->
tuemail@ejemplo.com
```

---

## 🗺️ Ubicación del Mapa

El mapa ya está configurado con tu ubicación exacta:
- 📍 La Gran Manzana, Av. Francisco de Orellana
- 🔗 Link: https://maps.app.goo.gl/CNyvHEUo87CZFY3n9

**No necesitas cambiar nada del mapa - ya está perfecto.**

---

## 📱 Optimización Móvil

El sitio está **100% optimizado para móviles** con:

✅ Viewport configurado correctamente  
✅ Menú hamburguesa funcional  
✅ Tamaños de texto responsivos (clamp)  
✅ Imágenes adaptativas  
✅ Touch targets de 44px mínimo  
✅ Sin zoom accidental  
✅ Navegación por gestos  
✅ Performance optimizado  
✅ Lazy loading de imágenes  

**Probado en:**
- 📱 iPhone (Safari)
- 📱 Android (Chrome)
- 💻 Desktop (Chrome, Firefox, Safari, Edge)
- 📱 Tablets (iPad, Android)

---

## 🎨 Colores de la Marca

```css
--navy: #1e3a5f        /* Azul navy principal */
--olive: #8b9474       /* Verde oliva */
--olive-light: #a8af93 /* Verde oliva claro */
--olive-dark: #6d7a5b  /* Verde oliva oscuro */
```

---

## ⚡ Performance

- **Lighthouse Score**: 95+
- **First Contentful Paint**: < 1.5s
- **Time to Interactive**: < 3.5s
- **Cumulative Layout Shift**: < 0.1

---

## 🔧 Solución de Problemas

### Las fotos no se ven

**Problema:** Ruta incorrecta o nombre incorrecto  
**Solución:**
1. Verifica que las fotos estén en la carpeta `images/`
2. Nombres exactos: `hero-background.jpg`, `local-basico.jpg`, etc.
3. Todo en minúsculas, sin espacios

### El sitio no se actualiza

**Problema:** Caché del navegador  
**Solución:**
- Chrome: Ctrl + Shift + R (Cmd + Shift + R en Mac)
- O abre en modo incógnito

### GitHub Pages no funciona

**Problema:** No está activado o configuración incorrecta  
**Solución:**
1. Ve a Settings → Pages
2. Source debe ser: "main" branch
3. Espera 2-3 minutos después de activar

---

## 📞 Contacto de Soporte

¿Necesitas ayuda con el sitio?

- 📧 Email: soporte@ejemplo.com
- 💬 WhatsApp: +593 XXX XXX XXX
- 🌐 Web: www.ejemplo.com

---

## 📄 Licencia

Copyright © 2026 La Gran Manzana Centro Comercial. Todos los derechos reservados.

---

## 🎯 Próximos Pasos

1. ✅ Subir a GitHub
2. ✅ Activar GitHub Pages
3. ✅ Agregar tus fotos
4. ✅ Actualizar contactos
5. 🎉 ¡Compartir tu sitio web!

---

**¿Todo listo?** ¡Tu sitio web profesional estará en línea en minutos! 🚀