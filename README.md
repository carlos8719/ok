| Entrada     | Salida esperada |                                        Descripción                                                |
|-------------|-----------------|---------------------------------------------------------------------------------------------------|
|$cad= ""     |      False      |cadena vacia tiene que devolver False porque no hay nada dentro.                                   |
|$cad= "asdbd"|      False      |cadena de letras  tiene que devolver False porque no es una cadena de parentis.                    |
|$cad= "1245" |      False      |cadena de enteros tiene que devolver False porque no es una cadena de parenteis.                   |
|$cad= "()"   |      True       |cadena de "()" tiene que devolver True porque tiene sus respetivos parentesis de abertura y cierre.|
|$cad= "(("   |      False      |cadena de "((" tiene que devolver False porque los dos parentesis son de abertura.                 |
|$cad= "))"   |      False      |cadena de "))" tiene que devolver False porque los dos parentesis son de cierre.                   |
|$cad= ")(("  |      False      |cadena de ")((" tiene que devolver False porque son impares dos de abertura y uno de cierre.       |
|$cad= "))("  |      False      |cadena de "))(" tiene que devolver False porque son impares dos de cierre y uno de abertura.       |
|$cad= "()()" |      True       |cadena de "()()" tiene que devolver True porque son dos y dos cada uno con abertura y cierre.      |
|$cad= "(())" |      True       |cadena de "(())" tiene que devolver True porque son dos y dos cada uno con abertura y cierre.      |
|$cad= ")()(" |      True       |cadena de ")()(" tiene que devolver True porque son dos y dos cada uno con abertura y cierre.      |
