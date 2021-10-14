# Notas para Branches (ramas) y Merge (fusión de ramas)

## crear rama

    git branch NombreRama

## moverse a una rama
    git checkout NombreRama
    
## Fusionar ramas  (merge) 

> Primero es IMPORTANTE moderse a la rama receptora  
> y en la rama receptora hacer el merge  

    git merge NombreRama

> Si no hay conflictos, se funciona para adelente  
> FastForward

> Si HAY conflictos, no te deja hacer el merge.
> Aparecen la opcioens de solución de conflictos y debemos 

1. Elegir opción
2. Guardar archivo
3. hacer el commit 

> De este modo se genera la fucnión de ramas

