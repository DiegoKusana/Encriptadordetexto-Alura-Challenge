# # Desafio Encriptador / Desencriptador de textos

El desafío consisitía en crear una aplicación que encripta textos para poder intercambiar mensajes secretos con otras personas que sepan el secreto de la encriptación utilizada.

Las "llaves" de encriptación que se utilizaron son las siguientes:
- La letra "e" es convertida para "enter"
- La letra "i" es convertida para "imes"
- La letra "a" es convertida para "ai"
- La letra "o" es convertida para "ober"
- La letra "u" es convertida para "ufat"

Requisitos:
- Debe funcionar solo con letras minúsculas
- No deben ser utilizados letras con acentos ni caracteres especiales
- Debe ser posible convertir una palabra para la versión encriptada también devolver una palabra encriptada para su versión original.

Por ejemplo:
"gato" => "gaitober" <>
"gaitober" => "gato"

La página debe tener campos para la inserción del texto que será encriptado o desencriptado, y el usuario debe poder escoger entre las dos opciones.

El resultado debe ser mostrado en la pantalla.

Como tarea extra se pidió incluir un botón que copie el texto encriptado/desencriptado para la sección de transferencia, o sea que tenga la misma funcionalidad del ctrl+C o de la opción "copiar" del menú de las aplicaciones.
