## Git Brach Model
EL **git branch model** es un modelo utilizado durante muchos años
por *git*.Con este modelo las modificaciones , fusiones y ramificaciones son extremadametne baratas y simples,y se consideran una de las partes centrales de su flujo de trabajo diario.
### Descentralizado pero centralizado
Es una de las caracteristicas principales,cada desarrollador que utiliza este tira y empuja al origen, ademas de eso, cada uno puede extraer cambios de otros para formar sus propias versiones.
### Ramas   
En esencia , el modelo de desarrollo tiene dos ramas principales:
>master
>develop
La rama master es la rama principal donde el codigo fuente de HEAD siempre refleja un estado de listo para la produccion.
En la rama develop,es donde el codigo fuente de HEAD siempre refleja un estado con los ultimos cambios ocurridos en el desarrollo para la proxima version.
*Cuando la rama del develop alcanza un nivel maduro,es necesario hacer un merge con la rama master, con esta, se podria considerar una nueva version, que es necesario etiquetar.*
Dicho esto, se pueden crear un monton de ramas adicionales de las cuales sirven para agregar caracteristicas,detalles,etc.A este ultimo detalle, se le debe su nombre.
