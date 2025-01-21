# Que es la inteligencia artificial?

Es el desarrollo de **Agentes Racionales**
Es el desarrollo de agente que al _interactuar con un entorno_
(y posiblemente otros agentes) **maximice** la **esperanza** de
una **utilidad** futura

Esto en ecuacion lo podemos escribir como $x = y$

Racional es **hacer lo que se puede con lo que se tiene**

**Espacio de estado:** todos los posibles estados del entorno.
De la forma $X = X_1 + X_2 + \dots + X_n$, donde $X_i$ es un subestado.
Un subestado es un conjunto de

## Agentes

Un agente recibe percepciones del entorno, y en base a eso actua
con el entorno.

Pipeline del agente

$p_0,\ p_1,\ \dots,\ p_t \rightarrow \text{agente} \rightarrow a_t$

Donde $p_i$ son las percepciones del agente y $a_t$ es la accion del agente
en base a esas percepciones.

El funcionamiento del agente se ve como

$\text{preprocesamiento} \rightarrow \text{Funcion de agente}
\rightarrow \text{post procesamiento}$

## Costo

El costo lo asignamos nosotros, y muchas veces puede ser la parte mas dificil

## Pequena Introduccion al aprendizaje maquina

> [!NOTE]
> Siempre que existen soluciones para un problema que,
> no usan aprendizaje maquina, las preferimos, ya que el
> aprendizaje maquina se basa en reglas inductivas, y
> estas nunca van a ser verdaderas.
