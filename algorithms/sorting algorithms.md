# Divide et impera
>

#### Algoritmi basati sul confronto:
- [selection sort](https://github.com/Biggiogero/Algorithms-and-data-structures/blob/main/algorithms/sorting%20algorithms.md#selection-sort)
- insertion sort
- bubble sort
- merge sort
- quick sort
- heap sort

#### Algoritmi **non** basati sul confronto:
- integer sort
- bucket sort
- radix sort

## Selection sort
Il selection sort ordina un array trovando ripetutamente l'elemento minimo dalla parte non ordinata e inserendolo all'inizio di questa. 

$$for k=0 to n-2 do$$
 	m = k+1
 	for j=k+2 to n do
 	     if (A[j] < A[m]) then m=j
       scambia A[m] con A[k+1]	
