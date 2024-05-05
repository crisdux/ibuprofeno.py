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

#### 11. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
frase = "    Hola mundo  "
print(frase.strip())
```

- A. `Hola mundo`
- B. `mundo Hola`
- C. `Hola`
- D. `mundo`


<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ A. `Hola mundo`

`strip()` en Python elimina los espacios sobrantes tanto de izquierda como de derecha de una cadena. Muy similar al método `trim()` de otros lenguajes de programación. 

</p>
</details>

---

#### 12. Explica el siguiente código Python

➡️ Dificultad: <mark> Intermedio </mark>

```py
def my_fn(precio):
  if(len(precio) == 1):
    return precio.zfill(2)
  if(len(precio) == 2):
    return precio.zfill(3)

print(my_fn("5"))
print(my_fn("50"))
```

- A. `5`, `50`
- B. `005`, `00050`
- C. `05`, `050`
- D. `50`, `50`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ C. `05`, `050`

El método `zfill` de Python es útil para completar con ceros una cadena dada. En el ejemplo verificamos la longitud del `precio` mandado como argumento, si su longitud es de `1` entonces completamos con ceros hasta que la longitud final sea de `2`; así mismo si la longitud del `precio` es `2` entonces completamos con ceros hasta que la longitud final sea de `3`. Eso es todo. ¿Muy fácil no?

</p>
</details>

---

#### 13. Explica el siguiente código Python

➡️ Dificultad: <mark> Intermedio </mark>

```py
print("-".join([str(i) for i in range(11,2,-2)]))
```

- A. `[11, 9, 7, 5, 3]`
- B. `11-9-7-5-3`
- C. `[3, 5, 7, 9, 11]`
- D. `3-5-7-9-11`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ B. `11-9-7-5-3`

El método `join` de las cadenas de Python es útil para convertir un iterable en un string en base a un separador.

Su sintaxis es la siguiente: `separador.join(iterable)`.

En nuestro ejemplo el `iterable` es una compresión de lista que va del `11` al `2` de uno en uno en secuencia decremental.

Y nuestro `separador` es un `-`, por ello el resultado final es `11-9-7-5-3` como string.

</p>
</details>

---

#### 14. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
print("hola mundo como estas".split(" "))
```

- A. `['hola', 'mundo', 'como', 'estas']`
- B. `['hola mundo como estas']`
- C. `hola mundo como estas`
- D. `Ninguna de las anteriores`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ A. `['hola', 'mundo', 'como', 'estas']`

`split` en Python es un método que se aplica sobre cadenas de texto, convierte a la cadena en una lista separando los items por el separador que pasamos por argumento a `split`. En este caso un espacio en blanco. 

</p>
</details>

---

#### 15. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
list = [1, 2, 3, 4]
list.append(10)
print(list)
```

- A. `[10]`
- B. `10`
- C. `[10, 1, 2, 3, 4]`
- D. `[1, 2, 3, 4, 10]`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ D. `[1, 2, 3, 4, 10]`

`append()` en Python es un método de listas que se usa para agregar al final de la lista un item nuevo. Si vienes por ejemplos de JavaScript es muy similar a lo que hace el método `push`.

</p>
</details>

---

#### 16. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
l = [1, 2]
l.extend([3, 4])
print(l) 
```

- A. `[1, 2, 3, 4]`
- B. `[3, 4, 1, 2]`
- C. `[1, 2]`, `[3, 4]`
- D. `Ninguna de las anteriores`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ A. `[1, 2, 3, 4]`

`extend()` en Python es un método de listas que nos sirve para concatenar dos listas para convertirlas en una sola. Es un método muy intuitivo y fácil de usar. 

</p>
</details>

---

#### 17. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
l = [1, 2]
l.insert(1,[1,2,3])
print(l)
```

- A. `[1, 2, [1, 2, 3]]`
- B. `[1, [1, 2, 3], 2]`
- C. `[1, 2, 1, 2, 3]`
- D. `[[1, 2, 3], 1, 2]`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅  B. `[1, [1, 2, 3], 2]`

`insert()` en Python es un método de listas que permite agregar un nuevo item a la lista, pero a diferencia de `append()` que lo agrega al final de la lista, `insert()` lo agrega en la posición de la lista que nosotros queramos. 

`insert()` recibe 2 parámetros: el índice donde queremos hacer la inserción y el objeto como tal que queremos insertar en la lista.

En nuestro ejemplo insertamos en la posición `1` una nueva lista `[1,2,3]` dando como resultado final una lista anidada: `[1, [1, 2, 3], 2]`.

Eso es todo.

</p>
</details>

---

#### 18. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
colors = ["red", "green", "pink"]
colors.pop()
colors.pop()
colors.pop()
colors.pop()
print(colors)
```

- A. `[]`
- B. `IndexError`
- C. `SintaxError`
- D. `[-1]`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ B. `IndexError`

La lista `colors` tiene solo 3 items y nosotros estamos intentando eliminar 4 items con `pop()`, esto no es correcto y por ello tenemos un `IndexError`.

</p>
</details>

---

#### 19. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
dias = "Lunes", "Martes", "Miercoles", "Jueves", "Viernes"
print(type(dias)) # 🤔
```

👉 **A.** `<class 'set'>`
👉 **B.** `<class 'list'>`
👉 **C.** `<class 'tuple'>`
👉 **D.** `<class 'str'>`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

👉 **C.** `<class 'tuple'>`

Las tuplas en Python son una estructura de datos muy similares a las listas pero con la característica de ser inmutables. 
Comúnmente su sintaxis se la puede reconocer con el uso de `()` encerrando todos los items, por ejemplo:

```py
dias = "Lunes", "Martes", "Miercoles", "Jueves", "Viernes"
dias2 = ("Lunes", "Martes", "Miercoles", "Jueves", "Viernes")
```

</p>
</details>

---

#### 20. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
list = [1,2,2,3,4,5,5,6]
set = set(list)
print(set)
```

- A. `{1, 2, 3, 4, 5, 6}`
- B. `{2, 2, 5, 5}`
- C. `{1, 3, 4, 6}`
- D. `{2, 5}`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ A. `{1, 2, 3, 4, 5, 6}`

`set` es una estructura de datos similar a las listas pero con algunas diferencias: los items en un `set` no están indexados por posición y los `set` no admiten elementos repetidos.

Esto último es super importante para comprender este reto, en el mismo usamos la función `set()` para convertir una lista a un `set`, como este no puede contener elementos repetidos, en dicha conversión se perderán algunos items: un `2` y un `5`.

El resultado final será un nuevo `set` sin dichos elementos repetidos. 


</p>
</details>

---

#### 21. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
s1 = {1, 2, 3}
s2 = {4, 2, 6}
s3 = {2, 5, 7}

print((s1 & s2) | s3) # 🤔
```

- A. `{1, 2, 3, 4, 6}`
- B. `{2}`
- C. `{1, 2, 3, 4, 5, 6, 7}`
- D. `{2, 5, 7}`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ D. `{2, 5, 7}`

Los `set` en Python soportan operaciones con conjuntos. 

En este ejemplo aplicamos la operación de `union` (`|`) y también la operación de `intersection` (`&`).

Vamos por pasos:
* Primeramente hacemos la `intersection` entre `s1` y `s2`

```py
s1 = {1, 2, 3}
s2 = {4, 2, 6}
## esto nos dará {2} puesto que solo necesitamos 
## los items que se repitan en ambos sets
```

* Ahora que tenemos `{2}` de la `intersection` es momento de hacer la `union` con el set `s3`

```py
print({2} | {2, 5, 7})
## acá nos toca seleccionar todos los elementos
## y los que se repiten solo los tomamos en cuenta una vez
```

Finalmente llegamos al resultado: `{2, 5, 7}`

</p>
</details>

---

#### 22. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
persona = {
  "nombre": "Cris",
  "apellido": "Villca",
  "edad": 27,
  "soltero": False,
  "direccion": {
    "calle": 17,
    "avenida": "Tomas Monje",
    "pasaje": "A"
  }
}

print(persona.get("direccion").get("avenida").upper())
```

- A. `None`
- B. `TOMAS MONJE`
- C. `tomas monje`
- D. `ToMaS mOnJe`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ B. `TOMAS MONJE`

Los diccionarios en Python son estructuras de datos de pares clave valor que podemos usar para administrar data de una manera mas eficiente y legible.

En este caso tenemos el diccionario anidado de dos niveles `persona` al cual queremos acceder a su propiedad `avenida`.

Para acceder a propiedades de un diccionario podemos usar la notación de corchetes `[]` o también el método `get()` como en este caso.

Encadenamos 2 veces el método `get()` pasando como argumento el nombre de la propiedad a la que queremos acceder, finalmente le pasamos un `upper()` para convertir todos los caracteres a mayúsculas. 

</p>
</details>

---

#### 23. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
persona = {
  "nombre": "Cris",
  "apellido": "Villca",
  "edad": 27,
  "soltero": False,
  "direccion": {
    "calle": 17,
    "avenida": "Tomas Monje",
    "pasaje": "A"
  }
}

print(persona.get("peso", 50))
```

- A. `peso`
- B. `None`
- C. `50`
- D. `TypeError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ C. `50`

El método `get()` de los diccionarios recibe un segundo parámetro que es el valor por defecto que le daremos a una propiedad en caso de que esta no exista en el diccionario.

En este caso queremos acceder a la propiedad `peso` de `persona`, la misma no existe, entonces el valor por consola será nuestro valor por defecto que en este caso es `50`. 

</p>
</details>

---

#### 24. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
persona = {
  "nombre": "Cris",
  "apellido": "Villca",
  "edad": 27,
  "soltero": False,
}

print(persona.items())
```

- A. `['nombre', 'apellido', 'edad', 'soltero']`
- B. `[('nombre', 'Cris'), ('apellido', 'Villca'), ('edad', 27), ('soltero', False)]`
- C. `['Cris', 'Villca', 27, False]`
- D. `SintaxError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ B. `[('nombre', 'Cris'), ('apellido', 'Villca'), ('edad', 27), ('soltero', False)]`

`items()` es un metodo de los diccionarios en Python que regresa una lista de tuplas, organizando cada una de ellas en pares clave-valor. 


</p>
</details>

---

#### 25. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
def fn():
  a=1
print(fn())
```

- A. `TypeError`
- B. `None`
- C. `Null`
- D. `SyntaxError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ B. `None`

Cuando una función en Python no regresa nada y es invocada automáticamente el interprete hará que regrese `None`. 

</p>
</details>

---

#### 26. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
def fn(x=0, y=0):
  return x + y

print(fn(1,1))
print(fn())
```

- A. `2`, `0`
- B. `0`, `2`
- C. `0`, `0`
- D. `2`, `2`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ - A. `2`, `0`

En Python podemos usar valores por defecto para los parámetros de una una función. 

En este caso cuando llamamos a `fn()` con los argumentos `(1,1)` es fácil deducir que el resultado es `2`.

Cuando llamamos a `fn()` sin argumentos entonces entran en acción los parámetros por defecto `(0,0)` dando como resultado la suma `0`. 

Finalmente el resultado es `2,0`.

</p>
</details>

---

#### 27. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
def fn(x=0, y):
  return x - y

print(fn(1))
```

- A. `-1`
- B. `1`
- C. `SyntaxError`
- D. `0`


<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ C. `SyntaxError`

Cuando queremos usar parámetros por defecto en Python estos siempre tienen que ir al final de la lista de parámetros en la función, sino tendremos un `SyntaxError`.

Corrigiendo el ejemplo, tendríamos:

```py
def fn(y, x=0):
  return x - y

print(fn(1)) # -1
```

</p>
</details>

---

#### 28. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
def fn(*numbers):
    return type(numbers)

print(fn())
```

- A. `<class 'list'>`
- B. `<class 'int'>`
- C. `<class 'tuple'>`
- D. `<class 'dict'>`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ C. `<class 'tuple'>`

En la lista de parámetros de una función escrita con Python, si vemos uno que empieza con un asterisco, en este ejemplo `*numbers` significa que dicho parámetro por defecto para el interprete de Python será considerado como una tupla.

Si vienes de JavaScript esto es muy similar a los parámetros REST.

Non confundir la sintaxis de asterisco con punteros de lenguajes como C, no tiene nada que ver. 

</p>
</details>

---

#### 29. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
def maximo(ls):
  return max(ls)

print(maximo(["a", "b", "c"]))
```

- A. `a`
- B. `b`
- C. `c`
- D. `None`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ - C. `c`

La función `max()` de Python como su nombre lo indica regresa el valor máximo de un iterable que le pasemos como argumento. 

En este caso debemos encontrar el máximo de una lista de strings, entonces lo que hace Python es convertir de manera implícita los strings a su respectivo código ASCII: 

Entonces tenemos algo como esto:

```py
def maximo(ls):
  return max(ls)

print(maximo([97, 98, 99])) # a->97, b->98, c->99
```

Ahora si es mucho más fácil saber por que la respuesta es `c`.

</p>
</details>

---

#### 30. Explica el siguiente código Python

➡️ Dificultad: <mark> Intermedio </mark>

```py
x = 10
def fn(entrada):
    entrada = 0
    return entrada

print(x)
print(fn(x))
```

- A. `10`, `10`
- B. `0`, `0`
- C. `10`, `0`
- D. `0`, `10`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ - C. `10`, `0`

La variable `x` esta fuera de la función `fn` por ende el valor de esta no se ve alterado mostrando primero por consola `10`.

Cuando mandamos `x` como argumento a `fn(entrada)` cambiamos su valor de `10` a `0` en el cuerpo de la función y luego lo regresamos mostrando posteriormente por consola dicho valor alterado, osea `0`.

En síntesis, el parametro `entrada` que pasamos a la función es recibido **por valor**, entonces fuera del scope de la función no sufre cambios, pero dentro de la función si.

</p>
</details>

---

#### 40. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
frutas = ["manzana", "pera", "fresa"]
frutas2 = frutas
frutas2.append("banana")
print(frutas)
```

- A. `['manzana', 'pera', 'fresa']`
- B. `['manzana', 'pera', 'fresa', 'banana']`
- C. `['banana', 'manzana', 'pera', 'fresa']`
- D. `Ninguna de las anteriores`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ B. `['manzana', 'pera', 'fresa', 'banana']`

En Python las listas se asignan por referencia, esto significa que su valor queda ligado a una dirección de memoria dentro de nuestro ordenador, por ende cuando hacemos `frutas2 = frutas` lo que copiamos en la variable `frutas2` no es el valor de toda la lista `frutas`, sino que copiamos la referencia en memoria de la lista `frutas`.

En Python y a diferencia de otros lenguajes podemos verificar esto haciendo uso de la función `id()` que justamente nos regresa la dirección de memoria donde esta almacenada nuestra variable:

```py
print(id(frutas)) # 140428447337024
print(id(frutas2)) # 140428447337024
``` 
Vemos que la dirección en memoria de ambas variables es la misma y es por este motivo que al alterar la lista de frutas de la variable `frutas2` los cambios también se ven reflejados en la variable original `frutas`. 


</p>
</details>

---

#### 41. Explica el siguiente código Python

➡️ Dificultad: <mark> Intermedio </mark>

```py
frutas = ["manzana", "pera", "fresa"]
frutas2 = frutas.copy()
frutas2.append("banana")
print(frutas)
```

- A. `['manzana', 'pera', 'fresa']`
- B. `['manzana', 'pera', 'fresa', 'banana']`
- C. `['banana', 'manzana', 'pera', 'fresa']`
- D. `Ninguna de las anteriores`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ - A. `['manzana', 'pera', 'fresa']`

El método `copy()` sirve para poder realizar copias completamente independientes de listas. En nuestro ejemplo al usar este método solo afectamos a `frutas2`, dejando a `frutas` intacto. 

</p>
</details>

---

#### 42. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
print(list())
```

- A. `[]`
- B. `IndexError`
- C. `TypeError`
- D. `SyntaxError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ A. `[]`

Podemos crear listas en Python usando la función `list()` y no pasarle ningún parámetro. La manera más _pythonica_ de hacerlo es solamente usando la sintaxis de corches vacíos: `[]`. 

</p>
</details>

---

#### 43. Explica el siguiente código Python

➡️ Dificultad: <mark> Intermedio </mark>

```py
lista_compras = ["huevos", "pan", "tomates", "leche"]
print(lista_compras[100:200:50])
```

- A. `IndexError`
- B. `SyntaxError`
- C. `TypeError`
- D. `[]`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ D. `[]`

Cuando intentamos acceder a una porción que no existe en una lista quizá pienses que deberíamos ver un error por consola, pero la verdad es que solo veremos un arreglo vacío haciendo referencia a que dicha porción de la lista justamente esta vacía. 


</p>
</details>

---

#### 44. Explica el siguiente código Python

➡️ Dificultad: <mark> Intermedio </mark>

```py
lista_compras = ["huevos", "pan", "tomates", "leche"]
print(lista_compras[100:200:50]) # 🤔
```

👉 A. `IndexError`
👉 B. `SyntaxError`
👉 C. `["huevos", "pan", "tomates", "leche"]`
👉 D. `[]`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ D. `[]`

En nuestro ejemplo queremos acceder a la porción de la lista que empieza en el índice `100` y que termina en el índice `200` dando saltos de `50` en `50`. 

Como podemos ver esto no es posible por que nuestra lista es muy pequeña, Python no nos lanzará ningún error pero si nos mostrará lo que considera correcto que es una lista vacía. 

Si lo pensamos tiene sentido puesto que el rango de la lista al que queremos acceder está vacío. 

</p>
</details>

---

#### 45. Explica el siguiente código Python

➡️ Dificultad: <mark> Intermedio </mark>

```py
lista_compras = ["huevos", "pan", "tomates", "leche"]
lista_compras.insert(100, "peras")
lista_compras.insert(-100, "manzanas")

print(lista_compras) 
```

👉 **A.** `["huevos", "pan", "tomates", "leche"]`
👉 **B.** `['manzanas', 'huevos', 'pan', 'tomates', 'leche', 'peras']`
👉 **C.** `['peras', 'huevos', 'pan', 'tomates', 'leche', 'manzanas']`
👉 **D.** `IndexError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **B.** `['manzanas', 'huevos', 'pan', 'tomates', 'leche', 'peras']`

Al intentar hacer `lista_compras.insert(100, "peras")` en nuestra lista `lista_compras` buscamos insertar el item `peras` en el index `100` de nuestra lista cuya longitud es solo de `4` items. 
Al ser `100` un index extremadamente lejano para nuestra pequeña lista esto debería dar un error, pero no. El interprete de Python lo pondrá en este caso hasta el final; por eso nuestra lista termina con el item `peras`.

Del mismo modo al tratar con index negativos empezamos a asignar dichos index de derecha a izquierda, siendo `peras` el index `-1`, `leche` el index `-2` y así sucesivamente. El index `-100` nuevamente esta muy lejano pero Python lo asignará hasta el principio de la lista y por ello empieza con `manzanas`. 

</p>
</details>

---

#### 46. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
lista_compras = ["huevos", "pan"]
print(lista_compras * int(3.5))
```

👉 **A.** `['huevos', 'pan', 'huevos', 'pan', 'huevos', 'pan']`
👉 **B.** `['huevos', 'pan', 'huevos', 'pan']`
👉 **C.** `["huevos", "pan"]`
👉 **D.** `TypeError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **A.** `['huevos', 'pan', 'huevos', 'pan', 'huevos', 'pan']`

`int(3.5)` nos dará `3` perdiendo así la parte flotante del número y `lista_compras * 3` repetirá nuestra lista por si misma tres veces y en su mismo orden. 


</p>
</details>

---

#### 47. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
lista_bebidas = ["agua", "jugo"]
lista_bebidas[::-1]
print(lista_bebidas)
```

👉 **A.** `["jugo", "agua"]`
👉 **B.** `["jugo"]`
👉 **C.** `["agua", "jugo"]`
👉 **D.** `["agua"]`


<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **C.** `["agua", "jugo"]`

Una manera muy pythonesca de dar la vuelta una lista es usar la sintaxis `lista_bebidas[::-1]`, lo importante acá es saber que esta sintaxis es inmutable, ósea que no modifica la lista original.

Efectivamente logramos dar la vuelta los items de la lista pero sin afectar a la lista original:

```py
lista_bebidas = ["agua", "jugo"]
print(lista_bebidas[::-1]) # ['jugo', 'agua']
print(lista_bebidas) # ['agua', 'jugo']
```

</p>
</details>

---

#### 48. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
lista_1 = ["item1", "item2"]
lista_2 = []
lista_3 = ["item3", "item4"]

print(lista_1 + lista_2 + lista_3)
```

👉 **A.** `['item1', 'item2', [], 'item3', 'item4']`
👉 **B.** `['item1', 'item2', [''], 'item3', 'item4']`
👉 **C.** `['item1', 'item2', 'item3', 'item4']`
👉 **D.** `['item1', 'item2', '', 'item3', 'item4']`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **C.** `['item1', 'item2', 'item3', 'item4']`

En Python es posible usar el operador `+` para "sumar" o mejor dicho concatenar listas. Su funcionamiento es muy simple e intuitivo, es como una suma de toda la vida pero con listas.

En ese caso `lista_2` al contener una lista vacía es omitida y por ello no aparece en el resultado final. 

</p>
</details>

---

#### 49. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
frutas= ["manzana", "pera", "fresa"]
frutas.extend("uva")
print(frutas)
```

👉 A. ['uva', 'manzana', 'pera', 'fresa']
👉 B. ['manzana', 'pera', 'fresa', ['uva']]
👉 C. ['manzana', 'pera', 'fresa', 'uva']
👉 D. ['manzana', 'pera', 'fresa', 'u', 'v', 'a']

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **D.** `['manzana', 'pera', 'fresa', 'u', 'v', 'a']`

El método `extend` en Python lo usamos para unir listas, pero ¿qué pasa cuando intentamos unir una lista con, por ejemplo, una cadena de texto?

`extend` va recorriendo item por item toda la lista, al llegar a `uva` se da cuenta que es un iterable de tipo cadena, entonces empieza a recorrer carácter por carácter todo el string y por ello el resultado es el mostrado. 

</p>
</details>

---

#### 50. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
numeros = [1,1,1,1,1,1]
numeros[2:5] = [0,0,0]
print(numeros)
```

👉 **A.** `[1, 1, 0, 0, 0, 1]`
👉 **B.** `[1, 1, 0, 0, 0, 0]`
👉 **C.** `[1, 0, 0, 0, 0, 0]`
👉 **D.** `Ninguna de las anteriores`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **A.** `[1, 1, 0, 0, 0, 1]`

En Python es posible asignar valores a trozos de un arreglo. En este caso cortamos el fragmento `[2, 5]` de la lista y en vez de `[1, 1, 1]` ponemos `[0, 0, 0]`. 

</p>
</details>

---

#### 51. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
numeros = [1,1,1,1,1,1]
print(numeros.find(1))
```

👉 **A.** `1`
👉 **B.** `AttributeError`
👉 **C.** `SyntaxError`
👉 **D.** `IndexError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **B.** `AttributeError`

Si bien el método `find()` existe para las cadenas, las listas no cuentan con este método. Es por eso que obtenemos un `AttributeError`, esto significa que dicha propiedad no pertenece a un tipo o estructura de datos. 

</p>
</details>

---

#### 52. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
productos = ["helado", "pan", "queso"]
precios = [15.5, 5, 29.99]

for producto, precio in zip(productos, precios):
  print(producto, precio)
```

👉 **A.** 
```py
helado 15.5
pan 5
queso 29.99
```
👉 **B.** 
```py
15.5 helado
5 pan 
29.99 queso 
```
👉 **C.** `AttributeError `
👉 **D.** `NameError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **A.** 

```py
helado 15.5
pan 5
queso 29.99
```

`zip` en Python sirve para trabajar con listas en paralelo, en nuestro ejemplo cada producto en index `x` será emparejado con su respectivo precio en index `x` también y terminamos por recorrer ambas listas en un solo `for`. 

</p>
</details>

---

#### 53. Explica el siguiente código Python

➡️ Dificultad: <mark> Intermedio </mark>

```py
print([0,0,0] > [2,0,10])
```

👉 **A.** `True`
👉 **B.** `False`
👉 **C.** `None`
👉 **D.** `SyntaxError`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **B.** `False`

En Python podemos usar signos de comparación entre listas donde haremos dicha comparación item a item (por index), veamos esto paso por paso.

Python hará las siguientes comparaciones en orden hasta que una sea falsa:

* `0` > `2`
* `0` > `0`
* `0` > `10`

La primera comparación de entrada es falsa, entonces el interprete de Python se detiene y regresa `False`.

Para que regrese `True` todas y cada una de las comparaciones deben ser verdaderas. 

</p>
</details>

---

#### 54. Explica el siguiente código Python

➡️ Dificultad: <mark> Intermedio </mark>

```py
my_string = "52,69,10,47,230,5,415,233"
mi_list = [ int(value) for value in my_string.split(",") if len(value) == 3]
print(mi_list)
```

👉 **A.** `[52, 69, 10, 47]`
👉 **B.** `['230', '415', '233']`
👉 **C.** `[230, 415, 233]`
👉 **D.** `['230415233']`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **C.** `[230, 415, 233]`

Las listas comprimidas son una característica brutal de Python. Permite al programador escribir listas complejas de una manera sencilla y en una sola línea de código.

Para entender mejor como es que funcionan las listas comprimidas sugiero aprender primero su sintaxis:

```py
mi_list = [ VALUE LOOP CONDITION] 
```  
Donde:
* `value`: es el valor que tendrá cada item en la lista.
* `loop`: es el ciclo que usaremos para generar la lista.
* `condition`: es la condición opcional que podemos usar para filtrar el resultado final de nuestra lista.

Volviendo al ejemplo:

* `value`: 
`int(value)` indica que cada item de la lista resultante sera convertida a entero.

* `loop`:
`for value in my_string.split(",")` indica que iteraremos sobre la cadena `my_string` convirtiendola a una lista usando el método `split()` y almacenando cada item en una variable `value`.

* `condition`:
`if len(value) == 3` indica que solo tomaremos en cuenta a los items cuya longitud sea igual a `3` o en otras palabras, números de `3` digitos.

Finalmente pasado todos los filtros el resultado final queda: `[230, 415, 233]`.

</p>
</details>

---

#### 56. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
my_tuple = ('a', 'b', 'c')
my_tuple[0] = 'A'
print(my_tuple)
```

👉 **A.** `('A', 'b', 'c')`
👉 **B.** `('a', 'A', 'c')`
👉 **C.** `ReferenceError`
👉 **D.** `TypeError`


<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **D.** `TypeError`

Recordemos que las tuplas son estructuras de datos parecidas a las listas pero inmutables, dicho de otra manera, no podemos cambiar sus valores. 

En este ejemplo intentamos cambiar el primer item de la tupla lo que es una violación clara a la naturaleza funcional de las tuplas, por ello obtenemos un `TypeError`.

</p>
</details>

---

#### 57. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
my_tuple = (123, 456, 789, 0)
a, *b, c = my_tuple
print(a, b, c)
```

👉 **A.** `123 [456, 789] 0`
👉 **B.** `123 0 456 789`
👉 **C.** `123 456 789`
👉 **D.** `Ninguna de las anteriores`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **A.** `123 [456, 789] 0`

Las tuplas poseen una característica denominada desempaquetado, esto significa que podemos acceder a sus valores en variables independientes.

En este caso `a` vale `123`, `*b` al tener el asterisco valdrá todo lo que este en medio entre `a` y `c` y lo regresa como una lista, por ello `b` vale `[456, 789]` y finalmente `c` vale el último valor de nuestra tupla, ósea `0`.

</p>
</details>

---

#### 58. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
print(dict(["a1", "b2", "c3"]))
```

👉 **A.** `{'0': 'a1', '1': 'a2', '2': 'a3'}`
👉 **B.** `{'a': '1', 'b': '2', 'c': '3'}`
👉 **C.** `{'1': 'a', '2': 'b', '3': 'c'}`
👉 **D.** `Ninguno de los anteriores`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **B.** `{'a': '1', 'b': '2', 'c': '3'}`

La función `dict` de Python permite convertir variables a diccionarios, en este caso pasamos una lista que que sea convertida a diccionario. Python divide cada item y regresa para este ejemplo el primer carácter como llave y el segundo carácter como valor.

</p>
</details>

---

#### 59. Explica el siguiente código Python

➡️ Dificultad: <mark> Intermedio </mark>

```py
my_dict = dict(["a1", "b2", "c3"])

print(my_dict.get("d"))
print(my_dict["d"])
```

👉 **A.** `0`, `0`
👉 **B.** `KeyError`, `KeyError`
👉 **C.** `None`, `KeyError`
👉 **D.** `None`, `None`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **C.** `None`, `KeyError`

En Python podemos acceder a los valores de un diccionario de 2 maneras diferentes:
* Usando el método `get()`: regresa `None` en caso de que el par clave-valor no exista en el diccionario.
* Usando la notación de corchetes: regresa el error `KeyError` y detiene la ejecución del programa.

Ambas maneras sirven para lo mismo pero la diferencia radica en cuando no encontramos la propiedad en el diccionario. Esta característica es muy peculiar de Python y esta bueno saberlo. 

</p>
</details>

---

#### 60. Explica el siguiente código Python

➡️ Dificultad: <mark> Fácil </mark>

```py
my_dict = {"nombre": "John", "edad": 30, "ciudad": "New York"}

my_dict["isSoltero"] = True
my_dict["edad"] = 25

print(my_dict)
```

👉 **A.** `{'nombre': 'John', 'edad': 30, 'ciudad': 'New York', 'isSoltero': True}`
👉 **B.** `{'nombre': 'John', 'edad': 25, 'ciudad': 'New York', 'isSoltero': True}`
👉 **C.** `{'nombre': 'John', 'edad': 25, 'ciudad': 'New York'}`
👉 **D.** `{"nombre": "John", "edad": 30, "ciudad": "New York"}`

<details><summary><b>Respuesta</b></summary>
<p>

#### **Respuesta**:

✅ **B.** `{'nombre': 'John', 'edad': 25, 'ciudad': 'New York', 'isSoltero': True}`

Al trabajar con Python y los diccionarios hay maneras de manipularlos, por ejemplo al usar la sintaxis de corchetes **con una llave que no existe** en nuestro diccionario como pasa con `my_dict["isSoltero"] = True`, Python procede a **agregar** un nuevo campo al diccionario con la `key` y `value` nuevos.

Ahora bien, al usar la sintaxis de corches con una **llave que ya existe** en el diccionario, como es el caso de `my_dict["edad"] = 25` entonces procedemos a **modificar** la `value` de dicho campo, para el ejemplo cambiamos `edad` de `30` a `25`.

El diccionario original era:
```py
my_dict = {"nombre": "John", "edad": 30, "ciudad": "New York"}
```
Pero agregamos el campo `isSoltero` con el valor de `True` y modificamos el campo `edad` de `30` a `25`: 
```py
my_dict = {'nombre': 'John', 'edad': 25, 'ciudad': 'New York', 'isSoltero': True}
```

</p>
</details>

<!-- ---

#### 61. Explica el siguiente código Python

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

--- -->

