# Bimestre 2 

### Taller 
Un algoritmo voraz es un tipo de estrategia algorítmica que construye una solución paso a paso, eligiendo en cada paso la opción que parece ser la mejor en ese momento, sin reconsiderar decisiones anteriores.
-Es decir, toma decisiones locales óptimas esperando que conduzcan a una solución global óptima.
S(suma Actual	x	s + x	S(conjunto )
0	25	25	{25}
25	25	50	{25,25}
50	10	60	{25,25,10}

![image](https://github.com/user-attachments/assets/dab2dfb2-2218-4ebd-b9f3-1385203c3750)

### Taller 
![image](https://github.com/user-attachments/assets/36b0ec14-cf41-4aeb-8631-d73407c62943)

## Medidas de Tiempo en Análisis de Algoritmos
✦ Tiempo Promedio (Average-case Time Complexity):
Aplica a algoritmos deterministas.

Se refiere al tiempo medio de ejecución sobre todas las entradas de un tamaño dado, bajo una distribución de probabilidad asumida sobre las entradas.

Útil cuando se conoce el perfil estadístico de los datos de entrada.

✦ Tiempo Esperado (Expected Time Complexity):
Aplica a algoritmos probabilísticos o aleatorizados.

Se refiere al tiempo promedio de ejecución sobre una entrada fija, calculado en función de las elecciones aleatorias realizadas por el algoritmo durante su ejecución.

✦ Tiempo Esperado en el Peor Caso (Expected Time in Worst Case):
Considera el tiempo promedio esperado de ejecución sobre todas las posibles ejecuciones aleatorias, para la peor entrada posible.

Es una medida más conservadora y útil para establecer cotas superiores de rendimiento.



## Números Pseudoaleatorios
Los números pseudoaleatorios son secuencias de valores generadas mediante algoritmos deterministas, conocidos como generadores de números pseudoaleatorios (PRNG, por sus siglas en inglés), que emulan el comportamiento estadístico de una fuente aleatoria real.

Aunque estos números se producen mediante funciones matemáticas totalmente determinísticas, están diseñados para presentar propiedades estadísticas equivalentes a las de secuencias aleatorias verdaderas, tales como uniformidad, independencia y distribución predecible, dentro de ciertos límites.

Debido a estas propiedades, los PRNG son ampliamente utilizados en algoritmos probabilísticos, métodos de Monte Carlo, simulación estocástica, criptoanálisis no crítico, y pruebas estadísticas, donde se requiere un comportamiento que aparente aleatoriedad sin necesidad de una fuente de entropía física.

<img width="602" height="262" alt="image" src="https://github.com/user-attachments/assets/2f97e22d-31b8-4c9c-8a1a-4369ef2ef9c4" />

<img width="477" height="258" alt="image" src="https://github.com/user-attachments/assets/57f8c9e6-167a-4cf5-bed5-e7ecdef40ee5" />

<img width="432" height="265" alt="image" src="https://github.com/user-attachments/assets/666900ee-4db2-4825-8948-3ca96b004393" />

<img width="593" height="266" alt="image" src="https://github.com/user-attachments/assets/d537e488-8c24-423f-af47-0a210834f483" />

<img width="557" height="298" alt="image" src="https://github.com/user-attachments/assets/b53e6cb4-34a9-43fe-a14a-ea51989a4ced" />

# Ordenación rápida (Quicksort)
<img width="619" height="170" alt="image" src="https://github.com/user-attachments/assets/3af48be1-6804-4368-8d20-073a2f1b0b70" />

<img width="1288" height="724" alt="image" src="https://github.com/user-attachments/assets/aafc2d9a-370f-4ef9-85f6-b9fe73034aaf" />

<img width="1130" height="568" alt="image" src="https://github.com/user-attachments/assets/f2c4b9d9-6b16-4c9d-afbb-df45ad1c2cbd" />

<img width="1500" height="484" alt="image" src="https://github.com/user-attachments/assets/7631f79d-1ac8-4b64-a3c0-b5bddc525de9" />

<img width="1460" height="690" alt="image" src="https://github.com/user-attachments/assets/15e66486-e25b-41e4-bb1c-2a359518c8d0" />

<img width="616" height="248" alt="image" src="https://github.com/user-attachments/assets/da1889df-0148-4bc2-9300-29187c58a58e" />

<img width="645" height="254" alt="image" src="https://github.com/user-attachments/assets/7efa5baf-fa4d-4ca8-8c46-ab0547b55b3e" />

<img width="595" height="105" alt="image" src="https://github.com/user-attachments/assets/ecb436db-aba5-4632-b467-0e415bdb408e" />

<img width="950" height="699" alt="image" src="https://github.com/user-attachments/assets/73b5b8b4-bc64-4cc0-b0b2-06effaad3608" />

<img width="1086" height="463" alt="image" src="https://github.com/user-attachments/assets/84c15645-a6ed-41a6-8ada-6a6f6ebec037" />

<img width="509" height="224" alt="image" src="https://github.com/user-attachments/assets/2c35acbe-08c2-4670-aac8-cc255d8a7f0c" />

<img width="1631" height="657" alt="image" src="https://github.com/user-attachments/assets/24a97ec7-cbfc-41a0-b7b2-dd0615d71f6d" />


# 	Algoritmos voraces

Poseen una implementación ágil y de baja complejidad computacional.
Son adecuados para abordar problemas de optimización combinatoria.
No aseguran la obtención de una solución globalmente óptima en todos los casos.
Operan siguiendo un enfoque heurístico basado en decisiones localmente óptimas en cada iteración, con el objetivo de aproximarse a una solución óptima global
<img width="718" height="392" alt="image" src="https://github.com/user-attachments/assets/7bc05b3a-72c4-4007-a159-d625a75cc3b9" />
## Ejemplo de Aplicación:
Realizar un pago a un cliente utilizando la menor cantidad posible de monedas disponibles.
## Ventajas
-Requieren una implementación sencilla y de bajo costo computacional.
-Producen soluciones eficientes en tiempo y recursos para muchos casos 
 prácticos.
-En determinadas situaciones, pueden llegar a obtener la solución     
 globalmente óptima.

## Desventajas
No todos los problemas de optimización son resolubles mediante enfoques voraces (greedy algorithms).
La elección de soluciones localmente óptimas no garantiza alcanzar una solución globalmente óptima.
Puede ser complejo definir una función de selección que asegure decisiones óptimas en cada paso del algoritmo.

# 	Grafos

Árbol de Recubrimiento Mínimo (Minimum Spanning Tree - MST)
Un árbol de expansión (o recubrimiento) de un grafo no dirigido y conectado  𝐺=(𝑉,𝐸)
G=(V,E), con pesos asociados a sus aristas, es un subgrafo acíclico que incluye todos los vértices del grafo y cuya estructura forma un árbol.

El costo total de dicho árbol se define como la suma de los pesos de las aristas que lo componen.

El problema consiste en encontrar el árbol de expansión con el costo mínimo posible, es decir, el árbol de expansión mínima del grafo 
𝐺
G.
Este tipo de problema es ampliamente utilizado en el diseño óptimo de redes de comunicación, distribución de servicios, y estructuras de conectividad con mínima inversión de recursos.

Definición técnica de grafo:
Un grafo es una estructura matemática representada como 
𝐺=(𝑉,𝐸)
G=(V,E), donde: 𝑉
V es un conjunto finito de vértices (también llamados nodos), y 𝐸
E es un conjunto de pares de vértices, conocidos como aristas (o enlaces), que pueden ser dirigidas o no dirigidas.
Dependiendo del contexto, las aristas pueden tener pesos asociados, que representan costos, distancias o capacidades.

<img width="1049" height="603" alt="image" src="https://github.com/user-attachments/assets/85e92f81-4dad-4db6-a355-e4e419f94356" />

<img width="1031" height="716" alt="image" src="https://github.com/user-attachments/assets/2763a060-3227-4a06-8c58-33f2573f07e5" />

<img width="1168" height="701" alt="image" src="https://github.com/user-attachments/assets/3ae31388-c878-48bd-8958-ffc5c3325021" />

<img width="907" height="684" alt="image" src="https://github.com/user-attachments/assets/feb5a5d4-e74e-421a-8b45-1974fa024600" />

<img width="1091" height="718" alt="image" src="https://github.com/user-attachments/assets/6ff615cf-a787-4c96-b076-263b13f7905b" />

<img width="982" height="709" alt="image" src="https://github.com/user-attachments/assets/e5a0a93a-244e-4796-bd58-d5c6dc97e734" />

## Árbol de recubrimiento mínimo

<img width="954" height="607" alt="image" src="https://github.com/user-attachments/assets/5cbf7d1b-e7e8-411f-92b4-0f97492e29d1" />

<img width="1040" height="674" alt="image" src="https://github.com/user-attachments/assets/3ccf6c14-2125-4dcf-af36-8f14d4329c16" />

## Algoritmo de Kruskall

<img width="1414" height="459" alt="image" src="https://github.com/user-attachments/assets/e8505ff2-0d7b-4c61-a967-adfb2cdea069" />

<img width="1561" height="649" alt="image" src="https://github.com/user-attachments/assets/3f70e25f-00ae-4bbf-a256-b5163e13d24d" />

<img width="1651" height="670" alt="image" src="https://github.com/user-attachments/assets/8ff3b53f-ca79-4ad5-af0f-e31c17252790" />

<img width="1275" height="492" alt="image" src="https://github.com/user-attachments/assets/e691b819-d2b8-413c-841a-c7df2c4146de" />

# Algoritmos y Probabilidades 
Existe un tesoro con una cantidad desconocida pero fija de 
𝑥
x lingotes de oro, ubicado en el punto A o B, pero no se conoce su ubicación exacta.

Desplazarse desde el punto actual (O) hacia A o B toma 5 días, y cada noche un dragón sustrae 𝑦
y lingotes de oro del tesoro.

Si permaneces 4 días adicionales en el punto de partida (O), podrás determinar con certeza la ubicación del tesoro mediante análisis computacional.

Un elfo ofrece revelar de inmediato la ubicación del tesoro a cambio de una cantidad equivalente a lo que el dragón tomaría en 3 noches, es decir, 3𝑦 3y lingotes de oro.

<img width="228" height="308" alt="image" src="https://github.com/user-attachments/assets/8fe0885f-2bb8-4169-a706-de6a043982e5" />

## ¿Cuál es?
Se puede aplicar un algoritmo probabilístico, específicamente una estrategia de decisión aleatoria, como sigue:

Utilizar una moneda (simulación de una variable aleatoria uniforme) para decidir aleatoriamente a cuál de los dos posibles destinos (A o B) ir primero, dado que ambos tienen la misma probabilidad a priori de contener el tesoro.

## Análisis de Resultados Posibles:
Caso favorable (50% de probabilidad):
Se acierta en la primera elección → el tesoro es hallado inmediatamente.
→ Se pierden 5 días de viaje → el dragón sustrae 5𝑦 5y lingotes.Ganancia: 𝑥−5𝑦 x−5y

## Caso desfavorable (50% de probabilidad):
Se erra en la primera elección → se requiere viajar al segundo destino.
→ Se pierden 10 días en total (5 de ida al lugar incorrecto + 5 al correcto).
→ El dragón sustrae 
10𝑦10y lingotes.Ganancia: 𝑥−10𝑦x−10y
Valor Esperado del Beneficio (Esperanza Matemática):
𝐸[𝐺𝑎𝑛𝑎𝑛𝑐𝑖𝑎]=0.5(𝑥−5𝑦)+0.5(𝑥−10𝑦)=𝑥−7.5𝑦
E[Ganancia]=0.5(x−5y)+0.5(x−10y)=x−7.5y

# Contextualización Algorítmica:
Este enfoque pertenece al ámbito de los algoritmos probabilísticos o estrategias basadas en valor esperado, donde se toman decisiones bajo incertidumbre evaluando el riesgo y beneficio esperado de cada acción.

-Se trata de una heurística estocástica, útil cuando:
-El costo de obtener información adicional es alto (como esperar 4 días o  pagar al elfo).
-Y cuando el resultado de una acción tiene distribución probabilística conocida.

## Terminación y Corrección
Un algoritmo determinista debe garantizar:

Terminación en tiempo finito para cualquier entrada válida (no puede entrar en bucles infinitos ni provocar errores como divisiones por cero).

Corrección total, es decir, debe generar siempre una solución correcta para cualquier entrada dentro del dominio del problema.

Un algoritmo probabilístico (o aleatorizado) puede:

No garantizar la terminación en todos los casos, siempre que la probabilidad de fallo sea suficientemente baja.

En tales casos, el algoritmo puede abortar la ejecución y reintentarse con la misma entrada.

Permitir cierto margen de error en la solución, siempre y cuando la probabilidad de error sea acotada por un valor suficientemente pequeño.

Mediante repetición independiente del algoritmo sobre la misma entrada, se puede reducir la probabilidad de error hasta niveles arbitrariamente pequeños (por ejemplo, usando amplificación de probabilidad).

## Determinismo vs Aleatoriedad en la Solución
Un algoritmo determinista genera siempre la misma salida para una entrada dada (a menos que esté diseñado específicamente para producir múltiples soluciones).

Un algoritmo probabilístico puede producir resultados distintos en diferentes ejecuciones con la misma entrada, debido al uso de elecciones aleatorias internas.

## Análisis de Eficiencia
El análisis de complejidad temporal de algoritmos deterministas puede ser complicado, pero es generalmente más estructurado, ya que el comportamiento del algoritmo es predecible.

En contraste, los algoritmos probabilísticos suelen requerir análisis más sofisticados, pues implican calcular esperanzas matemáticas, probabilidades de error, o tiempos esperados de ejecución, que dependen tanto de la entrada como de las distribuciones de probabilidad asociadas a las elecciones aleatorias internas del algoritmo.



## Método del generador lineal congruencial:
✦ Es el método más utilizado y se basa en la siguiente fórmula recursiva:
𝑋!"# =  𝑎𝑋!+𝑐 𝑚𝑜𝑑𝑚 ✦ Dónde:
𝑋! Es la semilla inicial
	𝑎, 𝑐, 𝑚	son constantes eteras elegidas cuidadosamente
•	Ejemplo
<img width="777" height="305" alt="image" src="https://github.com/user-attachments/assets/e6c3b66c-e21d-4a3f-8b31-328dae207fe5" />


# 	Divide y vencerás
wx + yz
981×1234 =  10!𝑤+𝑥 × 10!𝑦+𝑧
= 10"𝑤𝑦+ 10! 𝑤𝑧+𝑥𝑦+𝑥𝑧
¿Es posible obtener wz + xy a costa de una sola multiplicación?
Considere el producto
𝑟 =  𝑤+𝑥 × 𝑦+𝑧  = 𝑤𝑦+  𝑤𝑧+𝑥𝑦  +𝑥𝑧
𝑝 = 𝑤𝑦 = 09∗12 = 108
𝑞 = 𝑥𝑧 = 81*34 = 2754
𝑟 = (𝑤+𝑥)(𝑦+𝑧) = 90*46 = 4140
Finalmente
= 10"𝑤𝑦+ 10! 𝑤𝑧+𝑥𝑦+𝑥𝑧
981×1234 = 10"𝑝+ 10! 𝑟−𝑝−𝑞+𝑞
981×1234 = 10"(108)+ 10! 4140−108−2754  +2754
= 1210554
<img width="651" height="238" alt="image" src="https://github.com/user-attachments/assets/b2f18b90-60a0-4b8d-9aa9-e519b2b8e91f" />

# Busqueda Binaria 
<img width="1110" height="577" alt="image" src="https://github.com/user-attachments/assets/596a3c6e-cff0-48e7-b28f-b208d948120a" />

<img width="534" height="256" alt="image" src="https://github.com/user-attachments/assets/d98fe840-5265-45c4-b87e-3c711caba631" />

<img width="482" height="265" alt="image" src="https://github.com/user-attachments/assets/652bde4d-b20a-4f5c-b83a-81e0aaace90e" />

# Ordenacion 
<img width="768" height="188" alt="image" src="https://github.com/user-attachments/assets/566fec95-624b-44ab-86e4-d84d1f808e5c" />

<img width="756" height="288" alt="image" src="https://github.com/user-attachments/assets/84ada2ac-8568-4557-b676-85c4438324bd" />

<img width="646" height="296" alt="image" src="https://github.com/user-attachments/assets/bcfbcb5c-5aba-4bed-a2fc-81ea4c1a6daf" />

<img width="644" height="322" alt="image" src="https://github.com/user-attachments/assets/fc1fecf3-2d1c-4c7e-9ee2-dd6025f39af1" />

