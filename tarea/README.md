# Proyecto: Topologías Mininet

Este proyecto contiene las pruebas realizadas en Mininet usando distintas topologías de red.

## Comandos ejecutados

### 1. Árbol (`tree`)
```bash
sudo mn --topo tree,4,3```

Crea una topología en forma de árbol con profundidad 4 y 3 hijos por nodo.

Ideal para simular jerarquías en redes corporativas.

### 2. Lineal (`linear`)

```bash

sudo mn --topo linear,5,4```

Crea una topología lineal de 5 switches, cada uno con 4 hosts conectados.

### 3. Torus

```bash

sudo mn --topo torus,3,4,5```

Genera una topología tipo malla toroidal de 3 filas, 4 columnas y 5 hosts por nodo.
