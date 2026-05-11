## Fase 1 
**Justifica la elección basándote en el perfil de la empresa (25 empleados, presupuesto ajustado, necesidad de personalización en el etiquetado).**

Nuestra elección ha sido Odoo Enterprise ya que tiene un presupuesto ajustado ya que Odoo puede escalar el volumen de 25 empleados sin ningún problema..
A diferencia de las demás, Odoo Enterprise tiene un ERP completo, una alta escalabilidad y modularidad.
También tiene una alta personalización.

**Cálculo de TCO: Realiza una estimación a 3 años. No olvidéis incluir:
Coste de licencias/suscripción.
Coste de implantación (vuestras horas de desarrollo: estima 100h a 40€/h).
Coste operativo (Hosting en Google Cloud, AWS, Huawei Cloud o similar).**

# Presupuesto Odoo TCO (3 años)

| Concepto                    | Cálculo                          | Subtotal en 3 años   |
|:----------------------------|:---------------------------------|:---------------------|
| Suscripción Odoo Enterprise | 25 usu. x 31,10 €/mes x 36 meses | 27.990 €             |
| Implantación (Setup)        | 100 horas x 40 €/hora            | 4.000 €              |
| Hosting (AWS/Cloud)         | 45 €/mes x 36 meses              | 1.620 €              |
| Mantenimiento y Seguridad   | 50 €/mes x 36 meses              | 1.800 €              |
| **TOTAL TCO (3 años)**      | **Nuestro coste**                | **35.410 €**         |
| **VENTA AL CLIENTE**        | **Nuestro beneficio: 10.000€**              | **45.000 €**

## Manual de Despliegue
Manual de Despliegue 
Versión: 1.0
Fecha: 11 de Mayo de 2026

## Objetivo

Restablecer la operatividad de la aplicación y la base de datos PostgreSQL tras una caída del sistema 

## ¿Es coherente el TCO con la realidad de una PYME?

## ¿El comando de backup es sintácticamente correcto?
# Requisitos
PreviosDocker y Docker Compose instalados.

Archivo docker-compose.yml en el directorio de despliegue.

docker-compose ps

## ¿La matriz RBAC evita que el comercial vea los costes de producción?
## RBAC(Diseño de seguridad)
    Este es el diseño óptimo de permisos para los roles , diseñada especificamente para evitar que usuarios 
    con roles especificos accedan a información sensible.
    
    Administrador : Todos los permisos.
    Comercial:Permisos Lectura --> Acceso a los contratos de alquiler, Acceso a la información de facturación de los clientes .
    Contable: Permisos Edicion,Borrado -->  Acceso a la información de facturación de los clientes .
    Operario Almacen: Permisos Edicion,Borrado --> Acceso a historiales de servicio de los equipos .




