# 🌐 Guía: Visualizar tu Web en GitHub Pages

## 📍 Tu URL del Sitio

Basándome en tu repositorio `lebrav.github.io`, tu sitio estará disponible en:

### **URL Principal:**
```
https://lebrav.github.io
```

O si el repositorio tiene otro nombre:
```
https://lebrav.github.io/[nombre-del-repo]
```

## 📁 Estructura de Carpetas Necesaria

Como GitHub Pages está configurado para usar `/docs`, tu estructura debe ser:

```
tu-repositorio/
├── docs/
│   ├── webaleatoria_V3.html  ← Archivo principal
│   ├── manifest.json
│   ├── service-worker.js
│   ├── icon-192.png
│   ├── icon-512.png
│   └── (otros archivos)
└── README.md (opcional)
```

## ✅ Pasos para Ver tu Web

### 1. **Verificar que los archivos estén en `/docs`**
   - Asegúrate de que `webaleatoria_V3.html` y todos los archivos estén dentro de la carpeta `docs/`
   - Si no existe la carpeta `docs/`, créala y mueve los archivos ahí

### 2. **Renombrar el archivo principal (Opcional pero Recomendado)**
   - GitHub Pages busca `index.html` por defecto
   - Puedes renombrar `webaleatoria_V3.html` → `index.html` en la carpeta `docs/`
   - O acceder directamente a: `https://lebrav.github.io/webaleatoria_V3.html`

### 3. **Esperar el despliegue**
   - GitHub tarda 1-2 minutos en construir el sitio
   - Ve a: `Settings` → `Pages` en tu repositorio
   - Verás un mensaje verde cuando esté listo

### 4. **Acceder a tu sitio**
   - Abre tu navegador
   - Ve a: **https://lebrav.github.io**
   - O si renombraste a `index.html`: **https://lebrav.github.io/index.html**

## 🔧 Si no Funciona

### Problema: "404 Not Found"
**Solución:**
- Verifica que los archivos estén en `/docs`
- Espera 2-3 minutos después de subir los archivos
- Verifica en `Settings` → `Pages` que esté activo

### Problema: "Service Worker no funciona"
**Solución:**
- GitHub Pages requiere HTTPS (ya lo tiene ✅)
- Abre la consola del navegador (F12) para ver errores
- Verifica que `service-worker.js` esté en `/docs`

### Problema: "Los iconos no aparecen"
**Solución:**
- Genera los iconos con `generate-icons.html`
- Sube `icon-192.png` e `icon-512.png` a `/docs`

## 📱 Instalar como App Móvil

Una vez que tu sitio esté online:

1. **Abre la URL en tu móvil**
2. **Android:** Menú → "Añadir a pantalla de inicio"
3. **iOS:** Compartir → "Añadir a pantalla de inicio"

## 🎯 URL Final

Tu sitio debería estar en:
```
https://lebrav.github.io
```

O si usas subcarpeta:
```
https://lebrav.github.io/docs
```

¡Disfruta de tu app online! 🚀


