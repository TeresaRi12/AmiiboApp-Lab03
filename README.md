## María Teresa Rivera López
## 24000579

Lab03 Parte1-Parte2
## Parte 1 – Modo sin conexión elegante

App Android que muestra Amiibos en un grid interactivo con Jetpack Compose y Material 3.

### Funcionalidades principales
- Manejo de errores de conexión:
- Iconos y mensajes claros según el tipo de error (WiFi, datos, BD).
- Reintento de carga cuando es posible, sin perder los Amiibos ya cargados.
- Selector de tamaño de página: Permite al usuario elegir cuántos Amiibos cargar por página, actualizado dinámicamente
  en el dropdown de la TopAppBar.
- Lista de Amiibos: Grid con imagen, nombre y serie, paginación infinita y pull-to-refresh.


## Parte 2 – Búsqueda local
- Búsqueda en Tiempo Real: Filtrar Amiibos a medida que el usuario escribe.
- Persistencia Local: La búsqueda debe realizarse sobre la base de datos Room, no sobre una lista en memoria.
- Reactividad: Uso de flujos (Flow) para actualizar la UI automáticamente.
- Eficiencia: Implementar Debouncing para evitar consultas excesivas a la base de datos.
- UX Consistente: Opción de limpiar la búsqueda y manejo inteligente de estados de error/vacíos.

Link del video: https://youtu.be/Cm5t5fOx54E


Con ayuda de IA pude agilizar parte del proyecto y la documentacion, asi como comprender mejor el funcionamiento de Android, 
al igual que su estructura al hacer una app y en que carpetas colocarlas.
