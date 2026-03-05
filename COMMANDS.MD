# Levantar todo (DB + Backend + Frontend)
cd gestionstock && docker compose up -d --build

# Ver estado de contenedores
docker compose -f gestionstock/docker-compose.yml ps

# Ver logs en tiempo real
docker compose -f gestionstock/docker-compose.yml logs -f

# Detener contenedores
docker compose -f gestionstock/docker-compose.yml down

# Reiniciar
docker compose -f gestionstock/docker-compose.yml restart

# Solo Backend (sin frontend)
docker compose up -d --build backend db

# Solo Frontend (requiere backend corriendo)
docker compose up -d --build frontend

# LIMPIEZA TOTAL (elimina volúmenes y datos de BD)
# Esto borra TODOS los datos de PostgreSQL
docker compose -f gestionstock/docker-compose.yml down -v