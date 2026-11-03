# 🎛️ Control de Equipo · Sonido

App web para que una empresa de sonido e iluminación (**Sonidos y Luces Derghon**) sepa en todo momento dónde está cada equipo: qué hay en el depósito, qué está prestado y qué salió para cada evento.

## Qué hace

| Sección | Funcionalidad |
| --- | --- |
| **Inicio** | Resumen del inventario y de los equipos en uso |
| **Inventario** | Alta, edición y detalle de equipos; selección múltiple e impresión |
| **En uso** | Equipos prestados o afuera, con cambio rápido de estado |
| **Códigos QR** | Genera un QR por equipo e imprime etiquetas, todas o solo las seleccionadas |
| **Escanear** | Lee los QR con la cámara del celular para marcar un equipo como disponible o prestado al instante |
| **Eventos** | Arma un evento, escanea los equipos que salen y revisa qué volvió |

## Tecnologías

- HTML, CSS y JavaScript puro, en un solo archivo y sin build
- [html5-qrcode](https://github.com/mebjas/html5-qrcode) para escanear con la cámara
- [qrcodejs](https://github.com/davidshimjs/qrcodejs) para generar los códigos
- `localStorage` para guardar los datos en el dispositivo
- Diseño mobile-first, pensado para usar en el depósito con el celular

## Cómo usarlo

1. Descargá o cloná el repositorio.
2. Abrí `index.html` en el navegador. Para usar la cámara, servilo por HTTPS, por ejemplo con GitHub Pages.

## Autor

**Amaro Bodrone** · Desarrollador web Full Stack · [GitHub](https://github.com/amaroebodrone-pixel)
