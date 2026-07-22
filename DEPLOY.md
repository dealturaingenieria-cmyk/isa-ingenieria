# 📋 Guía de Despliegue - ISA Ingeniería

## ✅ Pasos para poner en línea tu sitio

### Paso 1: Verificar que el repositorio esté actualizado

```bash
git status
```

Deberías ver:
- `index.html`
- `style.css`
- `README.md`
- `DEPLOY.md`
- `.gitignore`

### Paso 2: Activar GitHub Pages

1. Ve a tu repositorio: https://github.com/dealturaingenieria-cmyk/isa-ingenieria
2. Haz clic en **Settings** (Configuración)
3. En el menú izquierdo, busca **Pages**
4. Bajo "Source", selecciona:
   - **Branch:** main
   - **Folder:** / (root)
5. Haz clic en **Save**

### Paso 3: Esperar a que se despliegue

- GitHub tardará 2-5 minutos en desplegar
- Verás un mensaje de confirmación cuando esté listo

### Paso 4: Acceder a tu sitio

Tu sitio estará disponible en:
```
https://dealturaingenieria-cmyk.github.io/isa-ingenieria
```

---

## 🌐 Agregar un dominio personalizado (Opcional)

### Opción A: Namecheap

1. Compra `isaingenieria.com` en https://namecheap.com
2. Ve a tu cuenta → **Manage Domain**
3. Haz clic en **DNS Settings**
4. Agrega estos **A Records**:
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```
5. O agrega un **CNAME**:
   ```
   dealturaingenieria-cmyk.github.io
   ```

### Opción B: GoDaddy

1. Compra `isaingenieria.com` en https://godaddy.com
2. Ve a **My Products** → **Manage DNS**
3. Busca **DNS Management** → **Edit DNS**
4. Agrega los mismos A Records o CNAME que arriba

### Opción C: Google Domains

1. Compra `isaingenieria.com` en https://domains.google.com
2. Ve a **DNS** en el panel izquierdo
3. Haz clic en **Custom name servers** (Servidores de nombres personalizados)
4. O agrega los A Records directamente

### Configurar dominio en GitHub

1. Ve a tu repositorio → **Settings** → **Pages**
2. Bajo "Custom domain", escribe: `isaingenieria.com`
3. Haz clic en **Save**
4. Marca **Enforce HTTPS** (espera 5-10 minutos)

---

## ✨ Tu sitio estará en línea en:

### Con GitHub Pages:
```
https://dealturaingenieria-cmyk.github.io/isa-ingenieria
```

### Con dominio personalizado:
```
https://isaingenieria.com
```

---

## 🔄 Actualizar contenido después

Si necesitas cambiar textos, imágenes o información:

1. Edita `index.html` directamente en GitHub (haz clic en el archivo)
2. Haz clic en el lápiz (✏️) para editar
3. Haz los cambios
4. Haz clic en "Commit changes"

Los cambios se publicarán automáticamente en 2-5 minutos.

---

## 🆘 Solución de problemas

**¿El sitio no aparece después de 10 minutos?**
- Presiona Ctrl+F5 (o Cmd+Shift+R en Mac) para limpiar el caché
- Verifica que el repositorio sea público
- Revisa el tab **Actions** para ver si hubo errores en el despliegue

**¿El dominio no funciona?**
- Espera 24-48 horas para que se propague el DNS
- Verifica que escribiste el dominio correcto en GitHub Pages
- Confirma que los A Records o CNAME están correctos en tu proveedor de dominio

---

**¿Necesitas ayuda?** Contáctanos en contacto@isaingenieria.com