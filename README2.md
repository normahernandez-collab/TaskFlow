#  TaskFlow

![Estado](https://img.shields.io/badge/Estado-En%20desarrollo-yellow)
![Versión](https://img.shields.io/badge/Versión-1.0-blue)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green)
![Markdown](https://img.shields.io/badge/Markdown-GFM-black)

##Descripción 

TaskFlow es una aplicación colaborativa para gestionar tareas de equipos de trabajo.

## Tabla de contenidos

- Descripción 
- Funcionalidades
- Requisitos
- Instalación
- Uso 
- Capturas de pantalla
- Arquitectura
- Estructura del proyecto
- Contribuidores
- Licencia

## Funcionalidades

- Crear tareas 
- Editar tareas
- Eliminar  tareas
- Asignar responsables
- Marcar tareas como completadas

### Checklist 

- [x] Crear tareas
- [x] Editar tareas
- [x] Eliminar tareas
- [ ] Notificaciones
- [ ] Modo oscuro

## Tecnologías utilizadas

| Tecnología | Uso |
|------------|----------------|
| HTML | Interfaz |
| CSS | Diseño |
| JavaScript | Lógica |
| MySQL | Base de datos |

## Requisitos 

- Visual Studio Code 
- Navegador modedrno 
- Git
- MySQL 

### Instalación 

```bash
git clone https://github.com/usuario/taskflow.git
cd taskflow
npm install
npm start
```

## Uso 

1.  Iniciar lal aplicación.
2. Crear una cuenta.
3. Agregar una tarea.
4. Administrar el pprogreso del equipo.

## Capturas de pantalla 

### Pantalla principal 
![Inicio](inicio.png)

### Inicio de sesión
![Login](login.png)

### Gestión de tareas
![Tareas](tareas.png)

### Perfil de usuario
![Perfil](perfil.png)

###  Arquitectura

```mermaid
flowchart LR
U[Usuario] --> F[Frontend]
F --> API[API]
API --> AUTH[Autenticación]
API --> DAO[DAO]
DAO --> DB[(MySQL)]
API --> LOG[Registro de actividad]
```

## Estructura del proyecto

```text
TaskFlow/
│── README.md
│── src/
│── css/
│── js/
│── images/
│── database/
```

## Contribuidores 

- Shammel Hernández
- Equipo TaskFlow

## Licencia

Este proyecto utiliza la licecncia MIT. 