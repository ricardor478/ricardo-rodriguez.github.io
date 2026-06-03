[README.md](https://github.com/user-attachments/files/28557549/README.md)
# ricardo-rodriguez.github.io# Ricardo Rodríguez Morales — Portafolio personal

Web personal alojada con **GitHub Pages**: portafolio profesional, CV descargable y un panel de inversiones con resumen de mercados e ideas semanales.

> ℹ️ Sustituye `tu-usuario` por tu nombre de usuario real de GitHub en todos los enlaces.

## 🌐 Páginas

| Página | Enlace | Descripción |
|--------|--------|-------------|
| Portafolio (ES) | https://tu-usuario.github.io/ | Página principal: perfil, experiencia, proyectos, stack y contacto |
| Portfolio (EN) | https://tu-usuario.github.io/index-en.html | Versión en inglés |
| Panel de Inversiones | https://tu-usuario.github.io/inversiones.html | Resumen de mercados e ideas de inversión semanales |
| CV (PDF) | https://tu-usuario.github.io/CV_Ricardo_Rodriguez.pdf | Currículum descargable |

## 📁 Estructura

```
.
├── index.html                  # Portafolio (español) — página principal
├── index-en.html               # Portafolio (inglés)
├── inversiones.html            # Panel de inversiones (resumen + ideas)
├── CV_Ricardo_Rodriguez.pdf    # CV descargable
└── README.md
```

## 🔄 Actualizar el panel de inversiones

El contenido semanal vive en un único objeto `WEEKLY_DATA` al principio del `<script>` de `inversiones.html`.

1. Pídele a Claude: *"actualiza mi web de inversiones"* (regenera el bloque con datos reales de la semana).
2. En el repo, abre `inversiones.html` → icono del lápiz (editar).
3. Pega el archivo actualizado → **Commit changes**.
4. En ~1 minuto la web queda actualizada.

El **ticker de cripto** (BTC/ETH) de la cabecera se actualiza solo en cada visita mediante la API pública de CoinGecko.

## 🛠️ Tecnología

- Sitio **100% estático** (HTML + CSS + JavaScript), sin dependencias de servidor.
- Tipografías vía Google Fonts.
- Datos de cripto en vivo: API gratuita de CoinGecko (cliente).

## ⚠️ Aviso

El panel de inversiones es **meramente informativo y educativo**. No constituye asesoramiento financiero ni una recomendación de compra o venta. Toda inversión conlleva riesgo de pérdida del capital.

## 📫 Contacto

- Email: ricardo.r478@gmail.com
- LinkedIn: https://www.linkedin.com/in/ricardo-rodriguez-8b5aa91a5/
