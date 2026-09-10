# Cómo personalizar esta landing para un cliente

## 1. Cambiar datos personales
Buscar y reemplazar en `index.html`:
- `MiWebChile` → tu nombre/marca (2 lugares: header + footer)
- `https://wa.me/56` → tu número real de WhatsApp, formato internacional sin + ni espacios
- `+56 9 XXXX XXXX` → tu número (footer)
- Email del formulario (`action` del `<form>`) → conectar a Formspree gratis
- Última línea del header: cambiar slogan si quieres

## 2. Personalizar por cliente (copiar archivo y editar)
Cada demo es el MISMO archivo copiado con 4 cambios:
1. `index.html` → `demo-ferreteria.html` (por ejemplo)
2. Título hero: "Tu negocio en internet, lista en 7 días" → "Ferretería Rengo — herramientas y servicio técnico"
3. Los 3 proyectos en `#proyectos` → reemplazar por el rubro del cliente (o dejar los tuyos)
4. URLs WhatsApp → linkear al número del CLIENTE (para que los pedidos lleguen a él)
5. Colores: si el cliente tiene marca, cambiar las variables `--primary` y `--primary-dark` en las primeras líneas del `<style>`

## 3. Nombres de archivo de demo
- `demo-clinica.html` — Clínica
- `demo-restaurante.html` — Restaurante
- `demo-taller.html` — Taller mecánico
- (Usa cualquier nombre)

## 4. Deploy (1 minuto, gratis)
1. Sube los archivos a GitHub (repo privado o público)
2. En [vercel.com](https://vercel.com) → Import Project → tu repo
3. Vercel te da URL tipo `tu-proyecto.vercel.app` automáticamente
4. Opcional: conectar un dominio `.cl` ($10 USD/año en NIC Chile)

## 5. Cambiar los 3 proyectos por los tuyos reales
Cuando tengas clientes reales, reemplaza los mockups ficticios (`Ferretería Rengo`, `Clínica Dental Sonríe`, `Gimnasio FitLab`) por capturas de pantalla reales de sus webs con su resultado.