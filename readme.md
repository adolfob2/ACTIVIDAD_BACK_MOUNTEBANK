# 🧩 Stubs Mountebank - LimpiezaPro

## Requisitos
- Tener **Node.js** instalado.
- Instalar **Mountebank** de forma global:
  ```bash
  npm install -g @mbtest/mountebank
  
Ejecución
Dentro de la carpeta del proyecto, ejecuta en la terminal:

bash
Copiar código
mb --configfile imposters.json
Esto levantará el servidor de Mountebank en el puerto 4545.

Endpoints simulados
Método	Endpoint	Descripción
GET	http://localhost:4545/api/categorias	Devuelve las categorías disponibles
GET	http://localhost:4545/api/productos	Devuelve todos los productos
GET	http://localhost:4545/api/productos?id=1	Devuelve el producto con id=1
POST	http://localhost:4545/api/pedidos	Simula la creación de un pedido

Prueba en Postman
Abre Postman.

Importa la colección:
Mountebank_Stubs.postman_collection.json

Ejecuta las peticiones y verifica las respuestas simuladas.

Autor: Adolf B.
Proyecto: LimpiezaPro (Simulación Backend con Mountebank)

