<div align="center">
  <img height="60" src="https://www.shutterstock.com/image-vector/vector-illustration-icon-python-programming-600nw-1397241389.jpg">
  <h1>Ibuprofeno.py</h1>
  <h2>Preguntas tipo quiz para aprender Python</h2>

---

<span>Me encanta Python, pero en pleno 2024 me parece una necesidad aprender Python tarde o temprano, este repo en un intento para lograr eso. Última vez actualizado: <a href=#20240404><b>04 Abril 2024</b></a>

Los retos consisten en preguntas de selección múltiple en tres niveles: <mark> Fácil </mark>, <mark>Intermedio</mark> y <mark>Avanzado</mark>. Las respuestas estarán collapsadas para no spoilearnos, el objetivo es aprender, así que trata de solucionar el reto sin ver la solución ni ejecutar el código.

Sigueme en mis redes para más! 😊 <br />
<a href="https://www.instagram.com/cris_cuetillo/">Instagram</a> || <a href="https://twitter.com/cris_cuetillo">Twitter</a> || <a href="https://www.linkedin.com/in/crisfer-dux/">LinkedIn</a> || <a href="https://dev.to/duxtech">Dev.to</a>

</div>

![img](https://github.com/crisdux/img-dev-to/blob/master/Black%20Photographic%20Technological%20Products%20YouTube%20Thumbail.png?raw=true)

| Diviertete! |
| ----------- |

---

#### 1. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
x,y,z = 1,2,3
print(x,y,z)
```

- A. `123`
- B. `1 2 3`
- C. `ValueError`
- D. `SyntaxError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ B. `1 2 3`

En Python es posible declarar múltiples variables en una sola lineal separándolas por comas, las asignaciones de valores a las variables se hace de manera simétrica: `x=1`, `y=2` y `y=3`.

</p>
</details>

---

#### 2. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
if True:
print("True")
```

- A. `True`
- B. `1`
- C. `IndentationError`
- D. `TypeError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ C. `IndentationError`

A diferencia de otros lenguajes de programación, para anidar código en Python no se usan llaves `{}`, sino que usamos indentaciones. En el ejemplo es como si tuviéramos el cuerpo del `if` completamente vacío justamente por que no tenemos la indentación bien escrita.

Para solucionar esto solo tenemos que indentar bien nuestro código:

```py
if True:
    print("True") # True
```

La recomendación es usar siempre **4 espacios** de identación.

</p>
</details>

---

#### 3. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
for i in range(1,10,2):
    print(i)
```

- A. `1 3 5 7 9`
- B. `0 2 4 6 8 10`
- C. `1 3 5 7 9 10`
- D. `2 4 6 8 10`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ A. `1 3 5 7 9`

La función `range` en Python es útil para crear intervalos. Recibe 3 parámetros: `range(inicio, final y salto)` donde:

- `inicio` (opcional), es el punto de partida del intervalo, si se omite por defecto toma el valor de `0`.
- `final` (requerido), es el punto final del intervalo, es obligatorio ponerlo.
- `salto` (opcional), equivale a decir "de cuanto en cuanto" saltará el intervalo, si se omite por defecto el salto es `1`, ósea recorre el intervalo de uno en uno.

Dicho esto, `range(1, 10, 2)` inicia en `1` y termina en `10`: `1, 2, 3, 4, 5, 6, 7, 8, 9` (en Python el final es siempre `final - 1`) por eso solo se crea el intervalo hasta el `9`.

Pero el salto es `2`, entonces tendríamos: `1, 3, 5, 7, 9`.

</p>
</details>

---

#### 4. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
for i in range(7):
    print(i)
```

- A. `1 2 3 4 5 6 7`
- B. `0 1 2 3 4 5 6 7`
- C. `0 1 2 3 4 5 6`
- D. `Ninguna de las anteriores`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ C. `0 1 2 3 4 5 6`

La función `range` en Python solo acepta como parámetro obligatorio el final del intervalo que queremos crear, en este caso: `inicio = 0`, `final = 7`, `salto = 1`, en otras palabras tendremos un intervalo entre `0` y `7-1` que vaya de uno en uno.

La salida tiene que ser: `0, 1, 2, 3, 4, 5, 6`

</p>
</details>

---

#### 5. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
for i in range (5, 0, -1):
    print(i)
```

- A. `0 1 2 3 4`
- B. `5 4 3 2 1`
- C. `-5 -4 -3 -2 -1`
- D. `Ninguna de las anteriores`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ B. `5 4 3 2 1`

En Python es posible crear intervalos de mayor a menor con la función `range`. En este caso el intervalo se verá así: `inicio=5`, `final=0`, `salto=-1`; o en otras palabras el intervalo empezara en `5`, terminara en `0+1` y los saltos iran en decremento: `5 4 3 2 1`

</p>
</details>

---

#### 6. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
numbers = [12, 5, 8, 13, 4]
num = numbers[::2]
print(num)
```

- A. `[12, 8, 4]`
- B. `[5, 13]`
- C. `[4, 8, 12]`
- D. `[4, 13, 8, 5, 12]`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ A. `[12, 8, 4]`

Al momento de parcelar la lista omitimos los parámetros de inicio y final por lo que operaremos sobre toda la lista haciendo saltos de 2 en 2: `[12, 8, 4]`

</p>
</details>

---

#### 7. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
primos = [2,3,5,7,11]
for indice, primo in enumerate(primos):
  print(f"{indice} -> {primo}")
```

- A.

```py
0 -> 2
1 -> 3
2 -> 5
3 -> 7
4 -> 11
```

- B.

```py
1 -> 2
2 -> 3
3 -> 5
4 -> 7
5 -> 11
```

- C.

```py
2 -> 0
3 -> 1
5 -> 3
7 -> 3
11 -> 4
```

- D. `SyntaxError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ A.

```py
0 -> 2
1 -> 3
2 -> 5
3 -> 7
4 -> 11
```

La función `enumerate()` en Python es muy útil cuando no solo necesitamos recorrer y acceder a los items de una lista, sino también a los índices de la misma. Por defecto los índices comienzan en `0` y van hasta el final de la lista. 

</p>
</details>

---

#### 8. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
list = [ x*5 for x in range(1,5)]
print(list)
```

- A. `[1, 2, 3, 4, 5]`
- B. `[5, 10, 15, 20]`
- C. `[5, 5, 5, 5, 5]`
- D. `SyntaxError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ - B. `[5, 10, 15, 20]`

Python posee una característica bien interesante denominada **list comprehension** o **compresión de listas** en español.
Es una sintaxis para poder escribir patrones de listas de una manera sencilla y fácil de comprender.

La sintaxis es la siguiente:

```py
lista = [expresión for elemento in iterable]
```

Donde: 
* `expresión`: es la variante de item que queremos mostrar en cada interacción.
* `for elemento in iterable`: es el `for` típico de Python para recorrer iterables (listas, diccionarios, tuplas, sets, cadenas, etc)

En nuestro ejemplo `for x in range(1,5)` genera un rango entre 1 y 4 que lo guardamos en la variable `x`, y con nuestra expresión `x*5` multiplicamos este valor por 5 en cada vuelta del bucle.

Por ello nuestro resultado es `[5, 10, 15, 20]`.

</p>
</details>

---

#### 9. Explica el siguiente código Python

➡️ Dificultad: <mark> Intermedio </mark>

```py
frase = "Feliz Año nuevo 2024"
salida = [ letra for letra in frase if(letra == "e") ]
print(len(salida))
```

- A. `3`
- B. `0`
- C. `2`
- D. `SyntaxisError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ C. `2`

En nuestro último reto vimos las **list comprehension** de Python, una manera super útil de poder crear listas en una sola línea de código. Olvide mencionarte que sintaxis también puede tener condicionales en su sintaxis 👀

La sintaxis final quedaría así:

```py
lista = [expresión for elemento in iterable condicional]
```

Entonces en nuestro reto con `for letra in frase` iteramos cada letra de la cadena `frase`, luego con `if(letra == "e")` verificamos en cada iteración que la letra sea `e`, si esto se cumple almacenamos la letra en la expresión `letra`.

La cadena `Feliz Año nuevo 2024` tiene un par de letras `e` por lo que quedaría `["e", "e"]` pero en la impresión final aplicamos `len` al resultado, en conclusión mostramos `2` por consola. 

</p>
</details>

---

#### 10. Explica el siguiente código Python

➡️ Dificultad: <mark> Intermedio </mark>

```py
print(bool([])) # 🤔
print(bool(0)) # 🤔
print(bool("")) # 🤔
```

- A. `False`, `False`, `True`
- B. `True`, `False`, `False`
- C. `True`, `True`, `False`
- D. `False`, `False`, `False`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ D. `False`, `False`, `False`

Python considera tanto las listas vacías, el número `0` y las cadenas vacías como `False`. 

</p>
</details>

---

<!-- #### 11. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py

```

- A. ``
- B. ``
- C. ``
- D. ``

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅

</p>
</details>

---

#### 12. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py

```

- A. ``
- B. ``
- C. ``
- D. ``

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅

</p>
</details>

---

#### 13. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py

```

- A. ``
- B. ``
- C. ``
- D. ``

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅

</p>
</details>

---

#### 14. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py

```

- A. ``
- B. ``
- C. ``
- D. ``

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅

</p>
</details>

---

#### 15. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py

```

- A. ``
- B. ``
- C. ``
- D. ``

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅

</p>
</details>

---
 -->





