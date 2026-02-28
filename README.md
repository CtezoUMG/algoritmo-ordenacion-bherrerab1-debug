# 🛡️ Laboratorio: Auditoría de Algoritmos (Bubble Sort)

Este laboratorio tiene como objetivo comprender la eficiencia de los algoritmos de ordenamiento mediante la implementación de **Bubble Sort** (Ordenamiento por Burbuja) y su ejecución sobre un set de **10,000 números**.

## 📝 ¿Qué es el Ordenamiento por Burbuja?

Es un algoritmo sencillo que funciona revisando cada elemento de la lista que va a ser ordenada con el siguiente, intercambiándolos de posición si están en el orden equivocado. Es necesario revisar toda la lista varias veces hasta que no se necesiten más intercambios, lo cual significa que la lista está ordenada.



### El Algoritmo (Pseudocódigo)
Para completar este reto, deberás implementar la siguiente lógica en C#:

```text
procedimiento bubbleSort(arreglo)
    n = longitud(arreglo)
    para i desde 0 hasta n-1:
        para j desde 0 hasta n-i-1:
            si arreglo[j] > arreglo[j+1] entonces:
                // Intercambio (Swap)
                temporal = arreglo[j]
                arreglo[j] = arreglo[j+1]
                arreglo[j+1] = temporal
            fin si
        fin para
    fin para
fin procedimiento
