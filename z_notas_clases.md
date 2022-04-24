## Clase 4 | 29032022
### Medidas relatiblas
- `em` relativo al tamaño de la fuente del padre.
- `rem` relativo al tamaño de fuente definido por el navegador.
- Usar `em` solo para definir tamaños de fuente.
- Para los tamaños de objetos usar `rem`
- Normalizar el valor de `rem` en `html` para facilitar los calculos de tamaños.
### Medidas flexibles
- `vw` Viewport width --> Ancho visible.
- `vh` viewport height --> Alto visible.

## Clase 9 | 05042022
### Selectores avanzados
- ">" Selecciona el hijo
- "+" Selecciona los hermanos adyacentes
### Selector de artributos
Nos permite seleccionar elemento en funcion de los atributos.
- "input[type="text"]" Selecciono elementos Input con prop type text.
### PseudoClases
Aplicar estilo no solo en relación al contenido sino tambien con el comportamiento.
- :visited
- :checked
- :hover
- :first-child
- :first-of-type
- :nth-of-type(1)
- :nth-of-type(n+3)
- :nth-of-type(even) ==> pares
- :last-child
- :nth-child(3n+1)
### Pseudo elementos
- ::before
- ::after
- ::selection
- ::first-letter

### Transiciones
- Duración. Sin duracion no se ve el effecto.
- Se aplican sobre el selecctor normar del elemento.
- transition: width .6s
- transition: all .2s
- transition: [elementos] [tiempo-del-efecto] [delay-del-efecto] [modificacion-del-efecto]

### Transform
-

### Animation
- animation [nombre] [duracion] [delay] [numero-de-veces]
