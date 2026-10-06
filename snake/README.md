# Snake con giro

Un Snake clásico en un solo archivo HTML, sin dependencias, con una vuelta: cada fruta acelera el juego y de vez en cuando aparece una fruta dorada que vale más puntos.

## Cómo jugar

Abre `index.html` en cualquier navegador moderno. No necesita servidor ni instalación.

## Controles

| Acción | Teclado | Táctil |
| --- | --- | --- |
| Moverte | Flechas o `W` `A` `S` `D` | Desliza sobre el tablero |
| Pausar / continuar | `Espacio` | Botón **Continuar** |
| Empezar / reiniciar | `Espacio` | Botón **Jugar** |

El juego se pausa solo si cambias de pestaña.

## Reglas

- La fruta roja suma **1** punto, alarga la serpiente y reduce el tiempo por paso (la velocidad sube hasta un máximo).
- La fruta **dorada** vale **5** puntos y desaparece a los 5 segundos; parpadea en el último tercio de su vida. El tiempo en pausa no cuenta.
- Chocar con las paredes o con tu propio cuerpo termina la partida.
- Llenar todo el tablero es una victoria.
- El récord se guarda en el navegador (`localStorage`).
