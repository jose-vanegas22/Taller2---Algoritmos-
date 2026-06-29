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

---

# SEGUNDO ALGORITMO
Largest Rectangle

## Problema
Dado un conjunto de edificios con diferentes alturas, 
encontrar el área del rectángulo más grande que se puede 
formar usando edificios consecutivos.

## Solución
Se usa una pila (stack) para guardar los índices de los edificios.
- Si el edificio actual es mayor o igual al tope → se apila
- Si el edificio actual es menor → se saca el tope y se calcula su área
- Al final se procesan los edificios que quedaron en la pila

## Complejidad
O(n)

---

## Cómo ejecutarlo

### Opción 1: En HackerRank
1. Ir a https://www.hackerrank.com
2. Buscar el problema deseado:
   - "Linked Lists - Detect a Cycle"
   - "Largest Rectangle"
3. Pegar el contenido del archivo correspondiente
4. Hacer clic en "Run" o "Submit"

### Opción 2: Localmente
1. Tener Python 3 instalado
2. Clonar el repositorio:
   git clone https://github.com/jose-vanegas22/Taller2---Algoritmos-
3. Entrar a la carpeta:
   cd Taller2---Algoritmos-
4. Ejecutar el algoritmo deseado:
   python3 has_cycle.py
   python3 largest_rectangle.py

## Requisitos
- Python 3

## Archivos
- `has_cycle.py` → Linked List - Detect a Cycle
- `largest_rectangle.py` → Largest Rectangle

## Autores
Jose Vanegas 2060558
Wilson Gomez 2060535
