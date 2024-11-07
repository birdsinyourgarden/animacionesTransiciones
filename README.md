# Propiedades de Animación y Transición en CSS

## Transiciones en CSS

Las transiciones en CSS permiten cambiar gradualmente una propiedad de un estado a otro, proporcionando un efecto más suave. Para que una transición funcione, debes definir el estado inicial y el estado final de una propiedad, y luego especificar la duración y el tipo de transición.

### Propiedades de Transición

- **`transition-property`**: Define la(s) propiedad(es) CSS a la que se aplicará la transición.  
  Ejemplo: `width`, `height`, `background-color`, etc.
  
- **`transition-duration`**: Establece la duración de la transición.  
  Ejemplo: `2s`, `500ms`.

- **`transition-timing-function`**: Define la curva de velocidad de la transición (como se acelera o desacelera).  
  Ejemplo: `ease`, `linear`, `ease-in`, `ease-out`, `ease-in-out`.

- **`transition-delay`**: Especifica el retraso antes de que la transición comience.  
  Ejemplo: `1s`, `200ms`.

# Animaciones en CSS

Las animaciones en CSS permiten cambiar múltiples propiedades de un elemento en el tiempo, utilizando `@keyframes` que definen cómo será la transición en cada etapa de la animación.

## Propiedades de Animación

- **`animation-name`**: Especifica el nombre de la animación que se desea aplicar, la cual debe estar definida en `@keyframes`.
  
- **`animation-duration`**: Define la duración total de la animación.  
  Ejemplo: `2s`, `5s`.

- **`animation-timing-function`**: Controla cómo la animación acelera y desacelera.  
  Ejemplo: `ease`, `linear`, `ease-in`, etc.

- **`animation-delay`**: Define cuánto tiempo esperar antes de iniciar la animación.  
  Ejemplo: `1s`.

- **`animation-iteration-count`**: Establece el número de veces que se repetirá la animación.  
  Ejemplo: `infinite`, `1`, `3`.

- **`animation-direction`**: Define la dirección de la animación, puede ser `normal`, `reverse`, `alternate`, o `alternate-reverse`.

- **`animation-fill-mode`**: Determina el estado del elemento antes y después de la animación.  
  Ejemplo: `none`, `forwards`, `backwards`, `both`.

- **`animation-play-state`**: Controla si la animación está en reproducción o en pausa.  
  Ejemplo: `running`, `paused`.


## Resumen 

| Propiedad                   | Descripción |
|-----------------------------|-------------|
| **`transition-property`**    | Define qué propiedad cambiará de forma gradual. |
| **`transition-duration`**    | Especifica la duración de la transición. |
| **`transition-timing-function`** | Controla la aceleración de la transición. |
| **`transition-delay`**       | Define un retraso antes de la transición. |
| **`animation-name`**         | Define el nombre de la animación en `@keyframes`. |
| **`animation-duration`**     | Establece la duración de la animación completa. |
| **`animation-timing-function`** | Controla la aceleración de la animación. |
| **`animation-delay`**        | Define un retraso antes de iniciar la animación. |
| **`animation-iteration-count`** | Especifica el número de veces que se repetirá la animación. |
| **`animation-direction`**    | Define la dirección de la animación. |
| **`animation-fill-mode`**    | Determina cómo se aplicarán los estilos antes y después de la animación. |
| **`animation-play-state`**   | Controla si la animación está en pausa o en reproducción. |
