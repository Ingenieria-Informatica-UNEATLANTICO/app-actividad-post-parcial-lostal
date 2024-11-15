# Examen [IdSw1] - Grado en Ingeniería Informática

Este repositorio contiene la entrega del examen correspondiente a la asignatura **[IdSw1]** del Grado en Ingeniería Informática en UNEATLANTICO. A continuación, se detallan los diagramas entregados en el examen, los diagramas pasados a UML sus respectivas iteraciones.

---

### 1: **Examen entregado**

| Diagrama              | Imagen                          |
|-----------------------|----------------------------------|
| Diagrama de Clases    | ![Diagrama de Clases](/images/png/diagramaDeClasesExamen.jpg) |
| Diagrama de Objetos   | ![Diagrama de Objetos](/images/png/diagramaDeObjetosExamen.jpg) |
| Diagrama de Estados   | ![Diagrama de Estados](/images/png/diagramaDeEstadosExamen.jpg) |

---

### 2: **Examen pasado a UML**

| Diagrama              | Ver SVG                          | Ver Código                          |
|-----------------------|-----------------------------------|-------------------------------------|
| Diagrama de Clases    | ![Diagrama de Clases](/images/svg/examen/DiagramaDeClasesExamen.svg) | [Ver Código](/modelosUML/examen/diagramaDeClasesExamen.puml) |
| Diagrama de Objetos   | ![Diagrama de Objetos](/images/svg/examen/diagramaDeObjetosExamen.svg) | [Ver Código](/modelosUML/examen/diagramaDeObjetosExamen.puml) |
| Diagrama de Estados   | ![Diagrama de Estados](/images/svg/examen/diagramaDeEstadosExamen.svg) | [Ver Código](/modelosUML/examen/diagramaDeEstadosExamen.puml) |


---

### 3.1: **Diagrama de clases**  
#### **Primera iteración**  

| Ver SVG                           | Ver Código                          |
|-----------------------------------|-------------------------------------|
| ![Diagrama de Clases](/images/svg/mejora/diagramaDeClasesMejora1.svg) | [Ver Código](/modelosUML/mejora/diagramaDeClasesMejora1.puml) |

**Comentarios**:  
Cambiado "MenúPrincipal" por "Recomendaciones", añadidos atributos `listaDeVideos` y `categoría`. Simplificados atributos eliminando `DRM` y `tipoDeUsuario`. Relación `Usuario --> Recomendaciones` actualizada. Uniformados nombres como `métodoDePago`. Relación y estructura general optimizadas.


### 3.2: **Diagrama de objetos**
#### **Primera iteración**

| Ver SVG                           | Ver Código                          |
|-----------------------------------|-------------------------------------|
| ![Diagrama de Objetos](/images/svg/mejora/diagramaDeObjetosMejora1.svg)           | [Ver Código](/modelosUML/mejora/diagramaDeObjetosMejora1.puml)                      |

### 3.3: **Diagrama de estados**
#### **Primera iteración**

| Ver SVG                           | Ver Código                          |
|-----------------------------------|-------------------------------------|
| ![Diagrama de Estados](/images/svg/mejora/diagramaDeEstadosMejora1.svg)           | [Ver Código](/modelosUML/mejora/diagramaDeEstadosMejora1.puml)                      |

**Comentarios**:  
Añadidos estados `Reproducción` y `AjustesDeCuenta`. Mejoradas transiciones con condiciones claras como `Credenciales válidas`, `Registro exitoso`, y `Cerrar sesión`. Flujo optimizado manteniendo un estado final `[*]` para reflejar la salida completa.