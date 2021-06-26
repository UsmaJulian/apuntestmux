# Mis apuntes de TMUX

### Para los futuros hackers :) 

##### prefix / pre -> cntrol + b

- pre + c -> nueva ventana
- pre + , -> cambiar nombre a la ventana
- pre + " -> nueva consola horizontal
- pre + % -> nueva consola vertical 
- pre + z -> zoom a consola
- pre + espacio -> cambiar consola a vertical
- pre + q -> para ver los números de las consolas 
- pre + 1, 2 ,3 -> moverse entre ventanas
- pre + flechas direccionales -> moverse entre consolas
- pre + {} -> cambiar de lugar las consolas
- pre + ctrl o -> mover venanas en sentido horario
- pre + ctrl flechas dir -> redimensionar consolas
- pre + !-> shift 1  -> mueve la consola a nueva ventana
- pre + shift : -> join-pane -s 1 -t 3 -> -s es source, fuente, -t destino, me permite mover la ventana 1 a la 3, siempre va de izq a derecha, una ventana 3 no se puede mover a una menor y así solo de menor a mayor
- pre + shift : -> swap-window -s 1 -t 2 -> intercambia ventana 1 con 2


---------------------- MODO COPIA --------------------
pre + shift [ -> pre + [ -> entramos en modo copia

- en modo copia -> pre + ctrl space -> se habilita el modo selección
- en modo copia -> alt + w -> copiar
- en modo copia -> ctrl + s -> entramos a un filtro para buscar 

- una vez copiado para pegar -> pre + ] , presionar q para salir

------------------------------------------------------

- tmux new -s "nombre de la sesión" -> crea una nueva sesión
- tmux list-sessions -> lista todas las sesiones
- tmux attach -t sesion -> retorna la sesión que estaba en segundo plano
- tmux kill-session -t sesion -> mata una sesión

- pre + d -> modo atached -> manda a segundo plano la sesión
- pre + s -> me lista las diferentes sesiones en forma visual
- pre + w -> me lista las diferentes sesiones pero de forma más visual que con s

------------------------------------------------------

##### Espero les sea de ayuda, un abrazo grande :)
