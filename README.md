# Prototipo de Software

El proyecto se enfoca en el desarrollo de un software que facilita el estudio eficaz mediante la implementación de múltiples funcionalidades como sesiones de estudio personalizadas, bloques de estudio con descansos, práctica sin mirar apuntes, evaluación de conocimientos y seguimiento de errores. El software permite la organización de temas, la programación de repasos, la exportación de resultados y la personalización del aprendizaje según las necesidades del usuario.

## Stack


## Arquitectura

El software se organiza en módulos que manejan funcionalidades específicas como la creación de sesiones, la práctica de conocimientos, la evaluación personalizada y el sistema de notificaciones. La arquitectura se basa en una estructura modular que permite la escalabilidad y la gestión de tareas por parte de diferentes desarrolladores. Cada módulo se encarga de una parte específica del sistema, como la gestión de sesiones, la evaluación de conocimientos o el seguimiento de errores, lo que facilita la implementación y el mantenimiento del software.

## Módulos

- **Diseño e Implementación del Sistema de Sesiones de Estudio**: Este módulo se enfoca en la creación de sesiones de estudio personalizadas, incluyendo la práctica sin mirar apuntes, la organización de temas, la implementación de bloques de estudio con descansos programados y el seguimiento de errores. Permite al usuario definir objetivos y estructurar sesiones ú
- **Sistema de Repasos y Evaluación Personalizada**: Este módulo se encarga de la programación de repasos diarios, la evaluación personalizada del usuario, la exportación de resultados y la organización de temas. Incluye un sistema de notificaciones para recordar tareas y repasos, así como la posibilidad de crear un historial de sesiones y progresos.

## Requisitos

- Docker y Docker Compose

## Cómo levantarlo

Este stack todavía no tiene servicios en Docker; revisa el README de cada carpeta.

## Estructura de carpetas

```
.
├── docker-compose.yml
├── .env.example
├── docs/
│   └── TAREAS.md
└── README.md
```

## Tareas

El plan con responsables y fechas está en [docs/TAREAS.md](docs/TAREAS.md).

---
Estructura inicial generada por Naatzo.
