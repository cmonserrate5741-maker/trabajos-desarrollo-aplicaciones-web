# Actividad 3: Calculadora Científica Web

**Asignatura:** Desarrollo de Aplicaciones Web  
**Estudiante:** ROBERTO CARLOS AGILA AGILA-CINDY YIMABEL MONSERRATE IBARRA-GENNY ISABEL GARCIA RAMIREZ  
**Tecnologías:** HTML5, CSS3 y JavaScript (sin dependencias externas)

## Objetivo

Desarrollar una calculadora científica funcional mediante programación del lado del cliente, diseñar su interfaz, implementar la lógica y publicar el proyecto en GitHub.

## Funciones implementadas

- Operaciones aritméticas y jerarquía de operadores, con paréntesis.
- Funciones trigonométricas y trigonométricas inversas, en grados o radianes.
- Funciones hiperbólicas.
- Potencias, raíces, raíces de índice personalizado, logaritmos y exponenciales.
- Factorial (enteros de 0 a 170), porcentajes, módulo, combinaciones (nCr), permutaciones (nPr), redondeos, valor absoluto e inverso.
- Constantes π y e, notación científica y respuesta anterior `Ans`.
- Memoria `MC`, `MR`, `M+`, `M−`; historial persistente de hasta 20 operaciones.
- Pantalla con vista previa del resultado, control de errores, teclado físico y tema claro/oscuro.
- Interfaz adaptable a móviles y computadoras.

## Archivos

- `index.html`: pantalla, botones, accesibilidad y distribución del contenido.
- `estilos.css`: colores, diseño de los botones y adaptación a tamaños de pantalla.
- `script.js`: motor de expresiones y eventos que hacen funcionar la calculadora.


| Expresión | Resultado esperado |
|---|---|
| `5+3*2` | `11` |
| `(5+3)*2` | `16` |
| `sqrt(81)` | `9` |
| `sin(30)` en DEG | `0.5` |
| `log(1000)` | `3` |
| `2^8` | `256` |
| `5!` | `120` |
| `root(3,27)` | `3` |
| `1E3` | `1000` |
| `comb(5,2)` | `10` |
| `perm(5,2)` | `20` |
| `1/0` | Mensaje de error |

