# Pastelería Delicia · React + Vite

Tienda en línea de la Pastelería Delicia (Diseño Web · Semana 12, React paso a paso).

## Funcionalidades
- Catálogo con búsqueda (con debounce), filtros por categoría y orden animado
- Detalle de producto en modal (`<dialog>`)
- Carrito global con Context + useReducer, guardado en localStorage
- Mini carrito lateral, avisos y foto que "vuela" al carrito
- Oferta del día con cuenta regresiva y carrusel de destacados
- Carta por categorías, registro validado con RegExp
- Checkout con tarjeta validada (algoritmo de Luhn)
- Seguimiento del pedido por rol (cliente / empleado)

## Uso
```bash
npm install
npm run dev      # desarrollo
npm run build    # compilar a /dist
npm run preview  # probar el build
```

## Despliegue en Vercel
Importa el repositorio de GitHub en Vercel. Detecta Vite solo:
- Build command: `npm run build`
- Output directory: `dist`
