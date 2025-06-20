# Instalación de it-caribe-nginx con Docker

## Crear red externa

Para que el contenedor se conecte a la red correcta, primero crea la red llamada `it-caribe-network`:

```bash
docker network create it-caribe-network
```