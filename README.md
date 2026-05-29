# Docker Lab con WSL2 + Ubuntu

## Descripción

Este proyecto implementa un entorno de desarrollo basado en contenedores Docker utilizando WSL2 y Ubuntu sobre Windows.

---

# Tecnologías Utilizadas

- WSL2
- Ubuntu
- Docker
- Nginx
- Node.js
- PostgreSQL
- pgAdmin 4
- Jupyter Lab
- Git & GitHub

---

# Arquitectura del Proyecto

```text
Windows
│
├── WSL2
│   └── Ubuntu
│
└── Docker Compose
    ├── nginx
    ├── node-app
    ├── postgres
    ├── pgadmin
    └── jupyter
```

---

# Servicios y Puertos

| Servicio    | Puerto |
|-------------|--------|
| Nginx       |  8080  |
| Node.js API |  3000  |
| PostgreSQL  |  5432  |
| pgAdmin 4   |  5050  |
| Jupyter Lab |  8888  |

---

# Estructura del Proyecto

```text
docker-lab/
│
├── nginx/
│   ├── Dockerfile
│   └── html/
│       └── index.html
│
├── node-app/
│   ├── Dockerfile
│   ├── package.json
│   └── server.js
│
├── postgres/
├── jupyter/
│
├── docker-compose.yml
├── .env
├── .gitignore
└── README.md
```

---

# Instalación y Ejecución

## 1. Clonar repositorio

```bash
git clone https://github.com/JuanCruzUV12/docker-lab.git
```

---

## 2. Entrar al proyecto

```bash
cd docker-lab
```

---

## 3. Levantar contenedores

```bash
docker compose up -d
```

---

## 4. Verificar contenedores

```bash
docker ps
```

---

# Evidencias del Funcionamiento

## Nginx funcionando

<img width="1920" height="1080" alt="Captura de pantalla 2026-05-20 092050" src="https://github.com/user-attachments/assets/6e6ecf33-19e4-401c-a8c5-f6b026e0ed15" />

---

## API Node.js funcionando

<img width="1920" height="1080" alt="Captura de pantalla 2026-05-20 092058" src="https://github.com/user-attachments/assets/031042ef-10f6-4a78-af27-b94c6dda9e72" />

---

## PostgreSQL y pgAdmin funcionando

<img width="1920" height="1080" alt="Captura de pantalla 2026-05-20 092118" src="https://github.com/user-attachments/assets/5b047e8b-1f54-4a3c-9005-f7b75a8bfc22" />

---

## Jupyter Lab funcionando

<img width="1920" height="1080" alt="Captura de pantalla 2026-05-20 092125" src="https://github.com/user-attachments/assets/e0713c60-54c4-4cb5-85f6-f6acab2419fc" />

---

## Contenedores Docker activos

<img width="1919" height="318" alt="Captura de pantalla 2026-05-20 090925" src="https://github.com/user-attachments/assets/5eae2da8-4212-436c-90d7-2923cc67be75" />

<img width="955" height="164" alt="Captura de pantalla 2026-05-20 095151" src="https://github.com/user-attachments/assets/5db9253f-a9e6-499b-b4d1-0b45ce36d27e" />

---

# Laboratorio 2 - Gestión y Optimización de Procesos en Linux

## Herramientas incorporadas

- stress
- stress-ng
- htop
- cpulimit
- ps
- pstree

## Objetivos

- Monitorear procesos
- Generar carga artificial
- Analizar consumo de CPU y memoria
- Gestionar prioridades
- Aplicar limitaciones de recursos

## Evidencias

### htop en reposo

<img width="1919" height="1079" alt="Captura de pantalla 2026-05-29 170351" src="https://github.com/user-attachments/assets/c0b1ccd6-af0e-4360-8e8f-8cf1d1dae7ba" />

### Saturación de CPU

<img width="786" height="70" alt="Captura de pantalla 2026-05-29 171016" src="https://github.com/user-attachments/assets/b080cfa0-815d-4353-a4b9-83a1c9ead204" />

### Saturación de memoria

<img width="895" height="74" alt="Captura de pantalla 2026-05-29 171224" src="https://github.com/user-attachments/assets/d91f2c69-3640-446f-b0c2-f6f6c47729d1" />

### Competencia de procesos

<img width="1919" height="1043" alt="Captura de pantalla 2026-05-29 171319" src="https://github.com/user-attachments/assets/b8ceeac5-686d-4f45-8b7a-53b6c03b4dfb" />

### Prioridades con nice

<img width="940" height="91" alt="Captura de pantalla 2026-05-29 171531" src="https://github.com/user-attachments/assets/1044d664-191d-405c-88f4-a102f8538bf6" />

<img width="942" height="85" alt="Captura de pantalla 2026-05-29 171637" src="https://github.com/user-attachments/assets/ed550f56-1155-4836-b534-50b5d3098fe3" />

---

# Integrantes del Proyecto

| Nombre                 | Codigo  |
|------------------------|---------|
| Juan Stevan Cruz       | 2459437 |
| Jhoan Fabricio Hurtado | 2459472 |

---
