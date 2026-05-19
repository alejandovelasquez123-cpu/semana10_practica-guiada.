# Bitacora de practica - Semana 10

## Nombre del estudiante
Estudiante: ____________________

## Objetivo del sistema evaluado
Validar registros de produccion rural y mostrar mensajes claros de error, advertencia y exito para comparar el resultado esperado con el obtenido.

## Registro de acciones

| Nro | Accion realizada | Dato ingresado | Resultado esperado | Resultado obtenido | Interpretacion |
|---|---|---|---|---|---|
| 1 | Abrir el proyecto en VS Code | No aplica | Ver archivos organizados | Proyecto abierto correctamente | La estructura del proyecto se visualizo sin problemas. |
| 2 | Ejecutar index.html | No aplica | Pagina cargada correctamente | Interfaz cargada en el navegador | La aplicacion inicio sin errores visibles. |
| 3 | Revisar consola | No aplica | Sin errores en rojo | Sin errores graves en consola | La pagina pudo continuar funcionando normalmente. |
| 4 | Probar dato valido | Leche, 12 litros | Mensaje de exito | Registro valido: la informacion fue procesada correctamente | El sistema acepto el registro y el mensaje fue claro. |
| 5 | Probar campo vacio | Producto vacio | Error por campo obligatorio | Debe completar todos los campos del registro | El sistema detecto informacion incompleta. |
| 6 | Probar texto en cantidad | abc | Error por dato no numerico | La cantidad debe ser un numero valido | El sistema bloqueo un valor invalido. |
| 7 | Probar cantidad negativa | -5 | Error por cantidad negativa | La cantidad no puede ser negativa | El sistema impide valores negativos. |
| 8 | Probar cantidad cero | 0 | Advertencia | La cantidad registrada es cero | El sistema permite revisar el dato porque requiere observacion. |
| 9 | Probar cantidad muy alta | 99999 | Advertencia | La cantidad es inusualmente alta | El sistema avisa que el valor debe verificarse. |
| 10 | Repetir pruebas despues de mejorar | Varios casos | Mayor numero de casos cumplidos | Mas casos coinciden con lo esperado | Las salidas quedaron mas especificas y faciles de interpretar. |

## Mensajes interpretados

1. Mensaje observado: `La cantidad debe ser un numero valido.`
   - Interpretacion: el sistema detecta que el valor ingresado no corresponde a un numero y detiene el proceso.

2. Mensaje observado: `La cantidad es inusualmente alta.`
   - Interpretacion: el sistema permite el registro, pero avisa que el dato debe revisarse antes de considerarlo confiable.

## Validacion del objetivo

- Si, el sistema cumple su objetivo funcional porque valida los datos, muestra mensajes claros y permite comparar lo esperado con lo obtenido.
- La salida mas clara fue el mensaje de exito, porque explica que el registro fue procesado correctamente.
- La salida que necesitaba mejora era la de error por campo vacio, porque antes era muy general y ahora es mas especifica.

## Conclusion breve
Durante la practica observe como una aplicacion puede evaluarse a partir de sus salidas y mensajes.
Identifique la diferencia entre error, advertencia y exito al probar distintos casos.
Tambien pude comparar el resultado esperado con el obtenido para confirmar si el objetivo se cumplia.
Al mejorar la logica, los mensajes se volvieron mas precisos y faciles de interpretar.
Esto ayudo a validar mejor el comportamiento del sistema y a documentar el proceso de prueba.
