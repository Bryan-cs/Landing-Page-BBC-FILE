# Pendientes — Cuando compres bbcfile.co

## 1. Conectar dominio a Vercel
- Vercel → proyecto `Landing-Page-BBC-FILE` → Settings → Domains
- Agrega `bbcfile.co` y `www.bbcfile.co`
- Vercel te da los DNS records (A + CNAME)
- Pega esos records en tu registrador de dominio
- SSL automático en ~5 minutos

**DNS a configurar:**
```
A     @    76.76.21.21
CNAME www  cname.vercel-dns.com
```

## 2. Subir og-image.png
- Crear imagen 1200×630px con logo BBC File
- Guardar en `assets/img/og-image.png`
- Hacer commit + push → Vercel redeploy automático
- Esta imagen aparece cuando compartes el link en WhatsApp/redes

## 3. Google Search Console
- Entrar a search.google.com/search-console
- Agregar propiedad → dominio `bbcfile.co`
- Verificar con TXT record en el registrador
- Ir a Sitemaps → pegar `https://bbcfile.co/sitemap.xml` → Enviar
- Esperar 2-4 semanas para indexación

## 4. Actualizar canonical en index.html
- Ya apunta a `https://bbcfile.co/` ✅ (no hay que cambiar nada)

## 5. Actualizar sitemap.xml
- Ya apunta a `https://bbcfile.co/` ✅ (no hay que cambiar nada)

## 6. Verificar SEO post-dominio
- Buscar `"BBC File"` en Google → debe aparecer
- Buscar `software seguridad social Colombia` → objetivo a largo plazo
- Herramienta gratuita: https://www.seoptimer.com → pegar bbcfile.co

---

**URL actual (mientras tanto):** https://landing-page-bbc-file.vercel.app/
