## Documento: Creación y Misión del SCP

Este documento explica la **creación y propósito del SCP**, el sistema que se utilizará para **generar al personaje principal** y también para **crear NPCs de forma aleatoria** en el mapa, mediante distintos scripts.

### Pasos realizados para su creación:

- **[[01.1 Creación de Mallas Principales (0 Modelo Base, 1 Hombre, 2 Mujer)]]**
    



### 🔄 Flujo recomendado
**Modelado → Rig → Skinning → Blend Shapes/Morphs → Correcciones → Drivers → Animaciones → Exportación.**

1. **Modelado base**
    
    - Define la malla y la topología limpia en pose neutral (A/T pose).
        
2. **Rig corporal**
    
    - Crea el esqueleto (armature) con huesos principales y jerarquía estable.
        
3. **Skinning básico**
    
    - Une la malla al rig con pesos automáticos y corrige zonas críticas (hombros, rodillas, cadera).
        
4. **Blend shapes faciales**
    
    - Añade expresiones esenciales: phonemes (A, E, O), cejas, ojos, sonrisa, FACS básicos.
        
5. **Morphs corporales**
    
    - Crea variaciones de altura, torso, pecho, musculatura.
        
    - Usa morphs en lugar de escalado para preservar volumen.
        
6. **Skinning fino + correctivos**
    
    - Ajusta pesos y crea shapes correctivos para poses extremas (ej. hombro levantado, rodilla flexionada).
        
7. **Drivers y controles**
    
    - Conecta blend shapes y huesos a sliders o control rig para animar fácil.
        
8. **Animaciones clave**
    
    - Genera y prueba animaciones (correr, saltar, skate, disparar, parkour).
        
9. **Exportación al motor**
    
    - Exporta en FBX/GLTF, valida límites de blend shapes y optimiza para rendimiento.
        
