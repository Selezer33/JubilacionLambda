# Revisión de lista de cotejo - JubilacionLambda

Evaluación del código recibido el 30/09/2026. No equivale a calificación del docente.
Los números de línea corresponden a `JubilacionLambda.py`. No se alteraron las fórmulas ni la autoría.

| Indicador | Evidencia / estado |
|---|---|
| 01. Entrega en fecha, diligenciada y en una hoja | Pendiente de entrega por el estudiante; este repositorio no acredita ese acto. |
| 02. Análisis lambda | Hay lambda y comentarios; líneas 83 |
| 03. Análisis map | No encontrado |
| 04. Análisis filter | No encontrado |
| 05. Análisis reduce | No encontrado |
| 06. Datos procesados y resultados | Presenta resultados en Streamlit; cobertura del conjunto parcial en simuladores/estimadores. |
| 07. Lazy en filter Y map | No cumple: no usa map ni filter. |
| 08. Datos procesados mediante lambda | Presente en el cálculo o selección; véanse líneas indicadas. |
| 09. JSON para valores inmutables | Parcial: configura valores escalares en un diccionario mutable. |
| 10. CI/CD GitHub y Streamlit Server | Se añade CI de arranque; ejecución remota por comprobar. No se desplegó Streamlit. |
| 11. Clases, funciones y tipos | Parcial: funciones y tipos presentes, ninguna clase definida. |
| 13. Framework | Cumple: Streamlit. |
| 14. Comentarios de reglas | Presentes; no sustituyen validaciones en las funciones. |
| 15. Repositorio | Destino: https://github.com/Selezer33/JubilacionLambda; verificar publicación efectiva. |

## Conclusión

**No cumple íntegramente la lista.** Faltan reduce, clases y la combinación de
map y filter con su análisis y evidencia perezosa. La publicación no soluciona
estos faltantes. El conjunto de diez programas tampoco incluye reduce ni clases.

## Preparación realizada

- Archivo de dependencias corregido: `requeriments.txt` -> `requirements.txt`.
- Dependencia fijada a la versión comprobada localmente.
- Se mantienen el código y los créditos originales de Hannia Macias Gómez.
- Historiales personales de días vividos y cuentas/movimientos bancarios se
  reemplazan por colecciones vacías en la copia pública; los originales siguen intactos.
- Se incorporan pruebas de arranque/interacción básica y un flujo GitHub Actions.

## Límites de la revisión

Las pruebas de arranque no demuestran exactitud de todas las fórmulas ni cubren
todos los casos de negocio. No se presenta el simulador bancario como software
financiero real: usa JSON local y mutación, y no contempla concurrencia ni controles
de producción. La persistencia local de Streamlit no equivale a una base de datos.
