# 02 · Del cerebro al código

[Volver al índice](../../README.md)

## ¿Qué es programar?
Dar instrucciones claras y ordenadas a un dispositivo para realizar una tarea.

## Algoritmo
Un plan de pasos para resolver un problema. Ejemplo: preparar una tostada:
1. Coger una rebanada de pan.
2. Introducirla en la tostadora.
3. Esperar a que salga.
4. Añadir tomate o aceite.

## Instrucción
Una orden individual del programa. En Python:

```python
print("¡Hola, clase!")
```

## Algoritmo y código
**Algoritmo**: qué pasos debemos realizar. **Código**: cómo escribimos esos pasos en un lenguaje de programación.

```python
nombre = "Ana"
print("Hola", nombre)
```

## Lenguajes y extensiones
- **Python**, archivos `.py`: `print("Hola")`.
- **C**, archivos `.c`: `printf("Hola");` (necesita cabeceras y compilación para un programa completo).
- **JavaScript**, archivos `.js`: `console.log("Hola")`.
- **Texto**, archivos `.txt`: texto sin indicar un lenguaje ejecutable concreto.

## Editor frente a intérprete
- **Nano y KWrite**: editores con los que escribimos y guardamos código.
- **python3**: intérprete que ejecuta el archivo de código Python.

## Con Nano en Linux
1. Abre el terminal.
2. Ejecuta `nano saludo.py`.
3. Escribe `print("Hola, clase")`.
4. Guarda con **Ctrl+O** y **Enter**; sal con **Ctrl+X**.
5. Ejecuta `python3 saludo.py`.

## Con KWrite
1. Abre KWrite desde el menú del escritorio (o usa `kwrite saludo.py` si está instalado).
2. Escribe `print("¡Hola!")`.
3. Guarda el archivo como `saludo.py`.
4. Abre el terminal en la carpeta donde lo has guardado.
5. Ejecuta `python3 saludo.py`.

## Variables
```python
nombre = "Alex"
print("Hola", nombre)
print("¡Estoy programando!")
```

## Errores frecuentes
- Python distingue mayúsculas: `Print` no equivale a `print`.
- Los mensajes literales deben llevar comillas: `print("Hola")`.
- Revisa que el archivo se llame `saludo.py`, no `saludo.py.txt`.

## Reto final
Crea el archivo `miprograma.py` con tres instrucciones `print()`. Guárdalo, ejecútalo, cambia una frase y vuelve a probar.

## Repaso
1. ¿Qué es un algoritmo?
2. ¿Para qué sirven Nano y KWrite?
3. ¿Qué significa la extensión `.py`?
4. ¿Cómo se ejecuta `saludo.py` en Linux?

> **Nota:** esta iniciación a la programación se propone como actividad de ampliación de TRDR.
