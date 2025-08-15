# Ventas-full
```mermaid
graph TD;
    A[Cliente] -->|Petición API| B(Backend);
    B --> C{Verificar Auth};
    C -->|Éxito| D[Base de Datos];
    C -->|Fallo| E[Respuesta 401];
```
