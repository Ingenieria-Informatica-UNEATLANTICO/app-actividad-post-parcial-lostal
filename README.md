# 📝 Examen [IdSw1] - Grado en Ingeniería Informática

Este repositorio contiene la entrega del examen correspondiente a la asignatura **[IdSw1]** del Grado en Ingeniería Informática en UNEATLANTICO. A continuación, se detallan los diagramas entregados en el examen, los diagramas pasados a UML y sus respectivas iteraciones.

---

## 📑 Índice
1. [Examen entregado](#1-examen-entregado)
2. [Examen pasado a UML](#2-examen-pasado-a-uml)
3. [Diagramas mejorados](#3-diagramas-mejorados)  
   - [Diagrama de clases](#31-diagrama-de-clases)  
   - [Diagrama de objetos](#32-diagrama-de-objetos)  
   - [Diagrama de estados](#33-diagrama-de-estados)

## 1: **Examen entregado**

| Diagrama              | Imagen                          |
|-----------------------|----------------------------------|
| Diagrama de Clases    | ![Diagrama de Clases](/images/png/diagramaDeClasesExamen.jpg) |
| Diagrama de Objetos   | ![Diagrama de Objetos](/images/png/diagramaDeObjetosExamen.jpg) |
| Diagrama de Estados   | ![Diagrama de Estados](/images/png/diagramaDeEstadosExamen.jpg) |

---

## 2: **Examen pasado a UML**

| Diagrama              | Ver SVG                          | Ver Código                          |
|-----------------------|-----------------------------------|-------------------------------------|
| Diagrama de Clases    | ![Diagrama de Clases](/images/svg/examen/DiagramaDeClasesExamen.svg) | [Ver Código](/modelosUML/examen/diagramaDeClasesExamen.puml) |
| Diagrama de Objetos   | ![Diagrama de Objetos](/images/svg/examen/diagramaDeObjetosExamen.svg) | [Ver Código](/modelosUML/examen/diagramaDeObjetosExamen.puml) |
| Diagrama de Estados   | ![Diagrama de Estados](/images/svg/examen/diagramaDeEstadosExamen.svg) | [Ver Código](/modelosUML/examen/diagramaDeEstadosExamen.puml) |

---
## 3. **Diagramas mejorados**
### 3.1: **Diagrama de clases**  
#### Primera iteración  

| Ver SVG                           | Ver Código                          |
|-----------------------------------|-------------------------------------|
| ![Diagrama de Clases](/images/svg/mejora/diagramaDeClasesMejora1.svg) | [Ver Código](/modelosUML/mejora/diagramaDeClasesMejora1.puml) |

**Comentarios**:  
- Cambiado "MenúPrincipal" por "Recomendaciones".  
- Añadidos atributos `listaDeVideos` y `categoría`.  
- Simplificados atributos eliminando `DRM` y `tipoDeUsuario`.  
- Relación `Usuario --> Recomendaciones` actualizada.  
- Uniformados nombres como `métodoDePago`.  
- Relación y estructura general optimizadas.

#### Segunda iteración

| Ver SVG                           | Ver Código                          |
|-----------------------------------|-------------------------------------|
| ![Diagrama de Clases](/images/svg/mejora/diagramaDeClasesMejora2.svg) | [Ver Código](/modelosUML/mejora/diagramaDeClasesMejora2.puml) |

**Comentarios**:  
- Añadidas cardinalidades a todas las relaciones para especificar multiplicidades.

---

### 3.2: **Diagrama de objetos**
#### Primera iteración  

| Ver SVG                           | Ver Código                          |
|-----------------------------------|-------------------------------------|
| ![Diagrama de Objetos](/images/svg/mejora/diagramaDeObjetosMejora1.svg)           | [Ver Código](/modelosUML/mejora/diagramaDeObjetosMejora1.puml)                      |

**Comentarios**:  
- Cambios similares a la primera iteración del diagrama de clases para mantener la coherencia.

#### Segunda iteración  

| Ver SVG                           | Ver Código                          |
|-----------------------------------|-------------------------------------|
| ![Diagrama de Objetos](/images/svg/mejora/diagramaDeObjetosMejora2.svg)           | [Ver Código](/modelosUML/mejora/diagramaDeObjetosMejora2.puml)                      |

**Comentarios**:  
- Cambios similares a la segunda iteración del diagrama de clases para mantener la coherencia.

---

### 3.3: **Diagrama de estados**
#### Primera iteración  

| Ver SVG                           | Ver Código                          |
|-----------------------------------|-------------------------------------|
| ![Diagrama de Estados](/images/svg/mejora/diagramaDeEstadosMejora1.svg)           | [Ver Código](/modelosUML/mejora/diagramaDeEstadosMejora1.puml)                      |

**Comentarios**:  
- Añadidos estados `Reproducción` y `AjustesDeCuenta`.  
- Mejoradas transiciones con condiciones claras como `Credenciales válidas`, `Registro exitoso`, y `Cerrar sesión`.  
- Flujo optimizado manteniendo un estado final `[*]` para reflejar la salida completa.
