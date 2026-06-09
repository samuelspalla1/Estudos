
Fala sobre escalabilidade, e não necessariamente performance.

**Complexidade Temporal**
	Tempo de runtime
	Quantidade de análises que precisarão ser feitas
	
**Complexidade Espacial**
	Espaço na memória ADICIONAL a ser guardado

## Tipos de Escala

**O(1)  / Constante**

Tempo: 
Pegar o primeiro item de um array/input
O tempo será o mesmo independente do tamanho do array/input

Espaço:
Alocar os 15 maiores elementos de um array/input
O espaço será o mesmo (de 15 elementos) independente do tamanho do array/input

**O (LOG N)**

Busca Binária

Sempre que eu dobrar o tamanho do array/input, não necessariamente dobra o tempo de execução. Aumenta em 1, dependendo dos casos.

**O (N)**

Escala na exata mesma medida que o input aumenta.

Se o input dobrar, o tempo e espaço dobram também.

**O (N LOG N)**

- Sorting (Quicksort, mergesort)
- Divide and Conquer

Algoritmos que são O(N) horizontalmente, porque percorre todos os elementos, e O(LOG N) em sua profundidade, porque se divide os inputs ao meio. 
Então são algoritmos que percorre, divide, percorre recursivas vezes.

**O (N^2)**

Loop dentro de um loop.

Percorre o array para cada item do array.