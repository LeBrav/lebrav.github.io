# 🔧 Solución Error 404 en GitHub Pages

## ❌ Problema
Tu sitio muestra 404 porque GitHub Pages está configurado para `/docs` pero tus archivos están en la raíz.

## ✅ Solución RÁPIDA (Recomendada)

### Opción A: Cambiar Configuración de GitHub Pages

1. **Ve a tu repositorio:**
   ```
   https://github.com/LeBrav/lebrav.github.io/settings/pages
   ```

2. **En la sección "Build and deployment" → "Source":**
   - Cambia de: `Deploy from a branch` → `/docs`
   - A: `Deploy from a branch` → `/ (root)` o `main` (raíz)

3. **Guarda los cambios**

4. **Espera 1-2 minutos** y recarga: https://lebrav.github.io

---

## ✅ Solución ALTERNATIVA

### Opción B: Mover Archivos a `/docs`

Si prefieres mantener `/docs`, mueve estos archivos a la carpeta `docs/`:

```
docs/
├── index.html          ← Mover aquí
├── manifest.json       ← Mover aquí
├── service-worker.js   ← Mover aquí
├── icon-192.png        ← Mover aquí (si existe)
└── icon-512.png        ← Mover aquí (si existe)
```

**Pasos:**
1. Crea carpeta `docs/` en tu repositorio (si no existe)
2. Mueve todos los archivos a `docs/`
3. Haz commit y push
4. Espera 1-2 minutos

---

## 🔍 Verificar que Funciona

1. **Espera 1-2 minutos** después de cambiar la configuración
2. **Ve a:** https://lebrav.github.io
3. **Deberías ver tu app** 🎉

---

## ⚠️ Si Sigue Sin Funcionar

1. **Verifica en Settings → Pages** que aparezca un mensaje verde "Your site is live at..."
2. **Revisa que `index.html` exista** en la ubicación correcta
3. **Espera hasta 5 minutos** (a veces GitHub tarda más)
4. **Limpia la caché del navegador** (Ctrl+F5)

---

## 📱 Después de Solucionarlo

Una vez que funcione, podrás:
- ✅ Ver la app en: https://lebrav.github.io
- ✅ Instalarla en móvil como PWA
- ✅ Compartirla con tus amigos

¡Avísame cuando funcione! 🚀


