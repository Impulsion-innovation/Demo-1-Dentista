# Clínica Dental Dra. Cortés — web demo

Landing de demostración para **Clínica Dental Dra. Cortés** (Esplugues de Llobregat).
Una sola página con scroll normal y fondo lila: inicio, forma de trabajar, tratamientos, horario,
ubicación con mapa y llamada a pedir cita. Animaciones suaves de aparición (motion-kit).

## Ver en local

```
python3 -m http.server 8777
```

y abre http://localhost:8777

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | La web |
| `clinica-dental-dra-cortes.html` | La web en un solo archivo: se abre con doble clic |
| `motion.css`, `motion.js` | Motor de animación (motion-kit) |
| `assets/` | Logo y favicon |
| `branding.json` | Datos, colores y tipografías usados |
| `web-lista.zip` | La web empaquetada para Netlify Drop / Hostinger |

## Datos reales usados

- Teléfono: 93 371 76 97
- Dirección: Av. de Cornellà, 2, 1-3, 08950 Esplugues de Llobregat, Barcelona
- Horario: lunes a viernes 9:00–13:00 y 16:00–20:00; sábado y domingo cerrado

## Pendiente de confirmar con la clínica

- **Lista de tratamientos**: es la oferta típica de una clínica general; hay que validarla con la Dra. Cortés.
- **Fotos**: son de stock (Unsplash) enlazadas en directo. Si alguna no cargara, el hueco muestra un
  fondo de marca. Lo ideal es sustituirlas por fotos reales de la clínica en `assets/`.
- Reseñas, años de experiencia, email o WhatsApp: no se han incluido porque no tenemos esos datos.
