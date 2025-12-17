# Laboratorio-3-POW
Carlos Hernandez

Funcionalidades principales:
1. Consulta de Publicaciones: Permite buscar posts filtrando por el ID de usuario (rango válido: 1 al 10).

2. Conexión a API: Realiza peticiones HTTP GET asíncronas a JSONPlaceholder utilizando fetch y async/await.

3. Persistencia de Datos (LocalStorage): Recordar Usuario: Opción para guardar el último ID consultado y rellenar el formulario automáticamente al recargar la página.

4. Caché de Resultados: Guarda las publicaciones cargadas para mostrarlas inmediatamente en la siguiente visita, incluso sin conexión a internet.

5. Gestión de Estado: Indicadores visuales de "Cargando...", mensajes de éxito o error en la petición.

6. Limpieza: Botón para borrar los resultados de la pantalla y limpiar los datos almacenados en el navegador.

Uso de la pagina:
1. Ingresa un número del 1 al 10 en el campo de "ID de usuario".

2. (Opcional) Marca la casilla "Recordar este ID de usuario".

3. Haz clic en "Cargar publicaciones".

4. Observa cómo se renderizan los resultados.

5. Recarga la página para verificar que los datos persisten.

Referencia API: 
Este proyecto utiliza la API pública y gratuita de prueba.

1. JSONPlaceholder: https://jsonplaceholder.typicode.com/.

2. Endpoint utilizado: https://jsonplaceholder.typicode.com/posts?userId={id}.

