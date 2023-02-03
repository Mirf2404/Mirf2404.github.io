# Mirf2404.github.io

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
                                                       ANIMACIONES

Las animaciones utilizadas se basan en animaciones basicas con la estiqueta 
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 @keyframes + Nombre de la animacion {

     0% {
        [Depende de la animacion sería de una manera o otra, aquí se pone como inicia la animacion por ejemplo]
       si quieres que empiece con un 20em de width se pondría:
       width = 20em;
      }
      
      100% {
       [aquí se pone como termina la animacion por ejemplo]
       si quieres que empiece con un 200em de width se pondría:
        width = 200m 
      }
    }

[ Ahora a lo que quieres que reproduzca esta animacion tienes que utilizar la siguiente sintaxis en el apartado css de la seccion que quieres q lo reproduzca]
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  div {
    animation: Nombre de la animacion + Tiempo que dura + Direccion + tipo de animacion;
    [El tipo de animacion se pone para especificar si quieres q se repita , si quieres q se quede fija etc...]
  }
