# 📜 Documento de Diseño del Juego (GDD)

## Título Provisional: Skater Life RPG (SLRPG)

### I. Visión General del Juego

|**Aspecto**|**Descripción**|
|---|---|
|**Género**|Mundo Abierto _Sandbox_ (GTA-like) con Simulación de Vida (Sims-like) y Progresión RPG.|
|**Plataforma**|PC (Objetivo inicial: Unity + Blender).|
|**Premisa**|Un/a Skater recién graduado abraza el profesionalismo y la vida de la calle. Su ascenso se ve interrumpido por una invasión zombi, forzándolo a sobrevivir en un mundo post-apocalíptico.|
|**Tono**|Oscuro y satírico, con drama emocional y acción.|

### II. Módulos de Juego (Core Gameplay)

|**Módulo**|**Objetivo y Sistemas Principales**|**Inspiración**|
|---|---|---|
|**A. Supervivencia (Simulación)**|Gestión de barras de necesidades: **Hambre, Sueño, Energía (Estamina), Vida**. Sistema de cocina y gestión de tiempo (similar a adelantar tiempo en Sims).|_The Sims 4_|
|**B. Locomoción**|Control en **1ra persona** (Shooter) y **3ra persona** (Exploración, Skate). Conducción de vehículos (coches, motos, aviones, barcos) con físicas tipo arcade.|_GTA V_|
|**C. Skate System**|Mecánica de trucos y combos con progresión de habilidades. Vinculado directamente a la trama principal.|_Skate 4_|
|**D. Economía/Trabajos**|**Múltiples:** Skater profesional, Trabajos Sims-like (avanzan el tiempo), Trabajos Ilegales (Venta de drogas, Bandas, Prostitución).|_GTA San Andreas_, _The Sims 4_|
|**E. Combate**|Sistema _Shooter_ en 1ra y 3ra persona. Combate _melee_ básico. **Enemigos:** Pandillas, Policía, Zombis (post-apocalipsis).|_GTA V_|

### III. Personaje Personalizado (Estructura de Base)

| **Aspecto**                                         | **Detalles y Relevancia**                                                                                                                                                               |
| --------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[[Sistema de creación de personajes (SCP)]]**<br> | Edición profunda de proporciones (**Blend Shapes**): Cara, Cuerpo (Gordo/Flaco, Músculo). Peinados y Accesorios (Activación/Desactivación de modelos). Color de piel/ojos (Materiales). |
| **Estético**                                        | El personaje debe ser visible en todas las cinemáticas (similar a _Saints Row_). Tiendas de ropa y tatuajes.                                                                            |
| **Progresión (Habilidades)**                        | **Habilidad Skater**, **Habilidades de Trabajo/Vida** (Lógica, Fuerza, Resistencia). Aprendizaje mediante escuelas, cursos e internet.                                                  |
| **Estadísticas de Interacción**                     | **Respeto/Reputación:** Afecta la reacción de NPCs y Bandas. **Orientación Sexual:** Libre.                                                                                             |

### IV. Mundo y Ambientación

|**Fase**|**Ambientación**|**Eventos Clave**|
|---|---|---|
|**Fase 1: Vida Normal**|Ciudad moderna _sandbox_ con skateparks, tiendas, antros, prostíbulos. Barrios controlados por pandillas.|Misiones de Skater Profesional, Trabajos, Romance con pareja principal.|
|**Fase 2: Apocalipsis Zombi**|Transformación del entorno. Muerte de la pareja principal. _Core Gameplay_ cambia a Supervivencia y Transporte de víveres.|Misiones de transporte e intercambio entre civilizaciones de supervivientes. Desbloqueo de vehículos militares.|

### V. Narrativa Clave

- **Protagonista:** Skater (hombre/mujer) con doble vida.
    
- **Adictividad:** Relación tipo **Cortana/John Spartan** con la pareja principal (romance en la trama).
    
- **Punto de No Retorno:** Un torneo profesional detona la invasión zombi y la muerte de la pareja.
    
- **Post-Apocalipsis:** Objetivo de crear una **Nueva Civilización** de sobrevivientes, manteniendo opciones morales oscuras (drogas, prostitución). **Meta:** Opción de tener un bebé (Sims-like) con otro superviviente.
    

### VI. Plataforma y Tecnología

- **Motor:** Unity (con Blender para _assets_).
    
- **Distribución:** PC inicialmente.
    
- **Multijugador:** Planeado para modo historia cooperativo y modo libre.
    
