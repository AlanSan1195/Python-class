# Aprendiendo Python

Este repositorio contiene ejercicios básicos en Python diseñados para aprender y practicar conceptos fundamentales del lenguaje, como variables, tipos de datos, operaciones básicas, y más.

## Contenido

### Tarea 1: Imprimir mensajes
**Descripción:**
- Escribe un programa que imprima tu nombre y tu ciudad en líneas separadas.

**Código:**
```python
print("Ejercicio #1")
name: str = 'Alan.'
city, country = 'Gdl', 'México'

print(f"Hola {name}")
print(f"veo que eres de {city} en {country}\n")
```

---

### Tarea 2: Tipos de datos
**Descripción:**
- Usa el comando `type()` para determinar el tipo de datos de varias variables.

**Código:**
```python
print("Ejercicio #2")
a = 15
b = 3.14159
c = "Hola mundo"
d = True
e = None

print(type(a))
print(type(b))
print("string:")
print(type("Hola mundo"))
print("boolean:")
print(type(d))
print(type(e))
print("\n")
```

---

### Tarea 3: Casting de tipos
**Descripción:**
- Convierte una cadena a entero y luego a float.
- Convierte un float a entero y observa el resultado.

**Código:**
```python
print("Ejercicio 3: Casting de tipos")
print("Convierte la cadena \"12345\" a un entero y luego a un float.")
print("Convierte el float 3.99 a un entero. ¿Qué ocurre?\n")

cadena_de_texto = "12345"
print(type(cadena_de_texto))
print(int(cadena_de_texto))
print(float(cadena_de_texto))
mi_float = 3.99
print(type(mi_float))
print(int(mi_float))
print("\n")
```

---

### Tarea 4: Variables
**Descripción:**
- Crea variables para tu nombre, edad y altura.
- Usa f-strings para imprimir una presentación.

**Código:**
```python
print("Ejercicio 4: Variables")
print("Crea variables para tu nombre, edad y altura.")
print("Usa f-strings para imprimir una presentación.\n")

mi_nombre: str = "Alan San"
mi_edad: int = 29
mi_estatura: float = 1.67

print(f"Hola me llamo {mi_nombre}, tengo {mi_edad} años de edad y mido {mi_estatura} aproximadamente. xD xD")
```

---

### Tarea 5: Números
**Descripción:**
- Realiza operaciones con números:
  1. Define una variable con el valor de PI.
  2. Redondea el número.
  3. Divide el número redondeado entre 2 usando división entera.
  4. Comprueba el resultado.

**Código:**
```python
print("Ejercicio 5: Números")
print("1. Crea una variable con el número PI (sin asignar una variable)")
print("2. Redondea el número con round()")
print("3. Haz la división entera entre el número que te salió y el número 2")
print("4. El resultado debería ser 1")

number = 3.1416
print(round(number) // 2)
```

---

## Cómo ejecutar los ejercicios
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/aprendiendo-python.git
   ```
2. Navega al directorio del repositorio:
   ```bash
   cd aprendiendo-python
   ```
3. Ejecuta cada archivo en tu entorno de Python:
   ```bash
   python tarea1.py
   ```

---

## Autor
**Miguel Angel Durán**

---


