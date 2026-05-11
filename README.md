## Manual de Despliegue
Manual de Despliegue 
Versión: 1.0
Fecha: 11 de Mayo de 2026

## Objetivo

Restablecer la operatividad de la aplicación y la base de datos PostgreSQL tras una caída del sistema 

# Requisitos
PreviosDocker y Docker Compose instalados.

Archivo docker-compose.yml en el directorio de despliegue.

docker-compose ps

## RBAC(Diseño de seguridad)
    Este es el diseño óptimo de permisos para los roles , diseñada especificamente para evitar que usuarios con roles especificos accedan a información sensible.
    
    Administrador: Todos los permisos.
    Comercial:Permisos Lectura --> Acceso a los contratos de alquiler, Acceso a la información de facturación de los clientes .
    Contable: Permisos Edicion,Borrado -->  Acceso a la información de facturación de los clientes .
    Operario Almacen: Permisos Edicion,Borrado --> Acceso a historiales de servicio de los equipos .
