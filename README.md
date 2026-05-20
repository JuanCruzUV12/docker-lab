# Docker Lab con WSL2 + Ubuntu

## Descripción

Entorno de desarrollo basado en contenedores Docker usando:

- WSL2
- Ubuntu
- Docker Compose
- Nginx
- Node.js
- PostgreSQL
- pgAdmin 4
- Jupyter Lab

---

## Arquitectura

Windows
│
├── WSL2
│ └── Ubuntu
│
└── Docker Compose
├── nginx
├── node-app
├── postgres
├── pgadmin
└── jupyter

---

## Servicios

| Servicio | Puerto |
|---|---|
| Nginx | 8080 |
| Node.js | 3000 |
| PostgreSQL | 5432 |
| pgAdmin | 5050 |
| Jupyter Lab | 8888 |

---

## Instalación

### Clonar repositorio

```bash
git clone URL_DEL_REPOSITORIO
