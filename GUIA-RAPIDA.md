# 🚀 GUÍA RÁPIDA - Subir a GitHub

## Pasos Súper Simples (5 minutos)

### 1️⃣ Prepara tus Fotos

Coloca estas 4 fotos en la carpeta `images/`:

```
✅ hero-background.jpg  (foto panorámica del centro comercial)
✅ local-basico.jpg     (local de 72m²)
✅ local-estandar.jpg   (local de 105m²)
✅ local-doble.jpg      (local de 144m²)
```

**💡 Tip:** Comprime las fotos en https://tinypng.com/ antes

---

### 2️⃣ Crea tu Repositorio en GitHub

**Opción A: GitHub Desktop (Más Fácil)**

1. Descarga: https://desktop.github.com/
2. Crea cuenta en: https://github.com/
3. Abre GitHub Desktop
4. "File" → "New Repository"
5. Name: `lagranmanzana`
6. Local Path: Selecciona esta carpeta
7. "Create Repository"
8. "Publish repository"
9. ✅ ¡Listo! Tus archivos están en GitHub

**Opción B: Línea de Comandos**

```bash
# 1. En tu terminal, ve a esta carpeta
cd ruta/a/lagranmanzana-github

# 2. Inicializa Git
git init

# 3. Agrega archivos
git add .

# 4. Primer commit
git commit -m "Initial commit"

# 5. Conecta con GitHub (crea el repo en github.com primero)
git remote add origin https://github.com/TU-USUARIO/lagranmanzana.git

# 6. Sube
git branch -M main
git push -u origin main
```

---

### 3️⃣ Activa GitHub Pages

1. Ve a tu repositorio en GitHub.com
2. Click en **"Settings"** (⚙️)
3. En el menú lateral: **"Pages"**
4. En **"Source"**: Selecciona **"main"**
5. Click **"Save"**
6. **¡Espera 2-3 minutos!**

📱 **Tu sitio estará en:**
```
https://TU-USUARIO.github.io/lagranmanzana
```

---

### 4️⃣ Actualiza Contactos

Abre `index.html` y busca/reemplaza:

```
Buscar: +593XXXXXXXXX
Reemplazar: Tu número real

Buscar: locales@lagranmanzana.ec
Reemplazar: Tu email real
```

Guarda y sube los cambios:

```bash
git add .
git commit -m "Actualizar contactos"
git push
```

---

## ✅ ¡YA ESTÁ LISTO!

Tu sitio web profesional ya está en línea. Compártelo:

📱 WhatsApp: "Mira nuestro nuevo sitio: https://..."  
📧 Email: Agrega el link en tu firma  
📱 Redes: Comparte en Instagram/Facebook  

---

## 🎨 ¿Quieres Cambiar Algo?

### Cambiar un Texto
1. Abre `index.html`
2. Busca el texto con Ctrl+F
3. Cámbialo
4. Guarda
5. `git add . && git commit -m "Cambiar texto" && git push`

### Cambiar una Foto
1. Reemplaza la foto en `images/`
2. Mantén el mismo nombre
3. `git add . && git commit -m "Actualizar foto" && git push`

---

## 📞 ¿Problemas?

### Las fotos no se ven
- Verifica nombres exactos en la carpeta `images/`
- Todo en minúsculas
- Formato JPG

### El sitio no se actualiza
- Espera 2-3 minutos después de hacer push
- Limpia caché: Ctrl+Shift+R

### GitHub Pages no funciona
- Settings → Pages → Source: "main"
- Espera 2-3 minutos

---

## 🎯 Dominio Personalizado (Opcional)

¿Quieres usar `www.tugranmanzana.com`?

1. Compra un dominio (Namecheap, GoDaddy, etc)
2. En Settings → Pages → Custom domain
3. Escribe tu dominio
4. Sigue las instrucciones de DNS

---

¡Eso es todo! Tu sitio web premium está listo. 🚀

**Comparte el link y empieza a alquilar locales!** 🏢✨