# Comunicaciones y Redes – Trabajo Práctico (Grupo B)

Este repositorio contiene el proyecto desarrollado para el Trabajo Práctico del curso de **Comunicaciones y Redes**, correspondiente al **Grupo B**. 

El objetivo es simular un escenario de red utilizando GNS3, conectando una Casa Central de una empresa con dos oficinas comerciales, cumpliendo con los requisitos especificados.

## Objetivos

1. **Simular la red** en GNS3 para conectar:
   - La Casa Central con dos oficinas comerciales.
   - Usuarios y servidores en todas las ubicaciones.
2. **Configurar y verificar conectividad**:
   - Todos los usuarios deben poder conectarse entre ellos y con los servidores.
   - Utilizar el comando `ping` para comprobar conectividad.

## Requisitos del Trabajo

### Escenario de Red

1. **Casa Central**:
   - **Subred dedicada** para 1600 servidores.
   - **Otra subred** para 250 usuarios.
2. **Oficinas Comerciales**:
   - **Oficina 1**: 30 usuarios.
   - **Oficina 2**: 300 usuarios distribuidos en un edificio de 3 pisos.
3. **Configuración de Routers**:
   - Un router por cada ubicación (modelo `c3745`).
   - Interfaces WAN para interconexión entre sitios.
   - Interfaces LAN necesarias para redes internas.

### Configuración en GNS3

1. **Elementos utilizados**:
   - **Router**: Imagen `c3745-adventerprisek.124-25d.bin`.
   - **PC estándar**: Imagen de VPC en GNS3.
   - **Switch Ethernet estándar**.
2. **Subredes**:
   - Configuración de parámetros IP para cada subred:
     - Nomenclatura abreviada.
     - Cantidad máxima de hosts soportados.
     - Rango de direcciones IP.
     - Dispositivos/interfaces asociados.

## Contenidos del Repositorio

1. **Plan de direccionamiento IP**:
   - Archivo `Plan_IP.md`: Detalla las subredes, direcciones IP, y dispositivos configurados.
2. **Proyecto GNS3**:
   - Archivo del proyecto: `red_grupo_b.gns3project`.
   - Capturas de pantalla del diseño y configuración.
3. **Verificaciones**:
   - Resultados de pruebas de conectividad (`ping`).
   - Archivo `verificaciones.md`.

## Instrucciones para la Revisión

1. **Abrir el proyecto**:
   - Descargar y abrir el archivo `red_grupo_b.gns3project` en GNS3.
   - Verificar la conectividad entre usuarios y servidores utilizando `ping`.
2. **Validar configuración IP**:
   - Comparar la configuración de IP en GNS3 con el archivo `Plan_IP.md`.

## Recursos Adicionales

- **Documento de referencia**: `GNS3_Redes.docx` (disponible en el drive del curso).
- **Guías de clase**: Procedimientos y ejemplos compartidos durante el curso.

---
