**Strutture dati**:

Una struttura dati è un’entità usata per organizzare un insieme di dati all’interno della memoria del computer.
La struttura dati prescinde dal suo contenuto.

Possono essere **statiche** o **dinamiche**:
 - **Statiche** quando il numero di elementi non può cambiare
 - **Dinamiche** quando il numero di elementi è variabile

**Categorie di strutture dati:**
 - **Array o vettore:** lista di elementi finiti, ordinati in base ad un indice
 - **Albero:** formato da degli elementi (chiamati nodi) legati tra loro (utilizzato per rappresentare strutture dati gerarchiche)
 - **Grafo:** insieme di elementi collegati tra loro senza un ordine preciso e può essere orientato o meno
 - **Pila o stack (LIFO):** lista in cui è possibile modificare gli elementi solo partendo dalla fine
 - **Coda (FIFO):** lista in cui è possibile modificare gli elementi solo partendo dall’inizio

**List comprehension:**
```py
lst = [i for i in range(1000) if i % 10 == 0]
```

**Funzioni:**

Una funzione è un **costrutto sintattico** che permette di raggruppare una serie di istruzioni.
```py
def a(arg1, arg2):
  print(arg1 + ' ' + arg2)
  return arg1 + ' ' + arg2
```
Se nessun valore di output è specificato, sarà automaticamente **None**
