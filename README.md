# sistema-gestion-streaming
# Sistema de Gestión Empresarial de Streaming (Go)

Proyecto integrador desarrollado en **Golang** bajo el paradigma de **programación funcional** y arquitectura modular por paquetes.

## Autor
* **Jhair Guanipatin** 
## Objetivo del Sistema
Desarrollar un Sistema de Gestión Empresarial para Plataformas de Streaming en Go bajo programación funcional, con el fin de automatizar la administración de suscriptores, el inventario de contenido audiovisual (películas y series) y el control de acceso a transmisiones y facturación mensual.

## Módulos y Estructura del Repositorio
```text
├── go.mod
├── main.go
└── pkg/
    ├── usuarios/
    │   └── suscriptores.go    # Alta de clientes y validación de planes
    ├── catalogo/
    │   └── multimedia.go      # Registro de títulos y búsqueda variádica
    └── streaming/
        └── operaciones.go     # Habilitación de transmisión y cálculo de cobros
