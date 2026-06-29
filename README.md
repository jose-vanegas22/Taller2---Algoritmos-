# Taller2---Algoritmos-

# PRIMER ALGORITMO
Linked List - Detect a Cycle

## Problema
Detectar si una linked list contiene un ciclo.
Retorna 1 si hay ciclo, 0 si no hay.

## Solución
Se usa un conjunto (set) para guardar los nodos visitados.
Si un nodo se repite, hay ciclo → retorna 1.
Si llega a None sin repetir → retorna 0.

## Complejidad
O(n)

## Cómo ejecutarlo

### Opción 1: En HackerRank
1. Ir a https://www.hackerrank.com
2. Buscar el problema "Linked Lists - Detect a Cycle"
3. Pegar el contenido de `has_cycle.py`
4. Hacer clic en "Run" o "Submit"

### Opción 2: Localmente
1. Tener Python 3 instalado
2. Clonar el repositorio:
   git clone [https://github.com/tu-usuario/tu-repo.git](https://github.com/jose-vanegas22/Taller2---Algoritmos-)
3. Entrar a la carpeta:
   cd tu-repo
4. Ejecutar:
   python3 has_cycle.py

## Requisitos
- Python 3.x

## Autor
Jose Vanegas 2060558
Wilson Gomez 2060535
