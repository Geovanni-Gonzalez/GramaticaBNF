# Gramática BNF para Configuración de Microchips 🚀
> **Curso:** Compiladores e Intérpretes  
> **Institución:** Tecnológico de Costa Rica (TEC)  
> **Estudiante:** Geovanni González Aguilar
> **Profesor:** Allan Rodríguez  

## 📌 Descripción del Proyecto
Este repositorio contiene la definición formal de la gramática **BNF (Backus-Naur Form)** para un lenguaje de programación de paradigma imperativo. El lenguaje ha sido diseñado específicamente para la configuración de dispositivos electrónicos (chips), priorizando un tipado fuerte, una sintaxis ligera y el manejo preciso de operaciones aritméticas y estructuras bidimensionales.

## 🛠 Características del Lenguaje
- **Tipado Explicito:** Uso obligatorio de tipos (`int`, `float`, `bool`, `char`, `string`).
- **Sintaxis de Chip:** Delimitadores de bloque únicos (`|:` y `:|`) y separadores de instrucción (`~`).
- **Operaciones Avanzadas:** Soporte nativo para notación exponencial (`100e10`) y fraccionarios (`5/6`).
- **Seguridad:** Operadores relacionales implementados como funciones (`equal`, `less_t`, etc.) para evitar ambigüedades.
- **Estructura:** Punto de entrada obligatorio mediante `empty ~ __main__ <| |>`.

## 📂 Estructura del Repositorio
- `gramatica.bnf`: Archivo principal con las reglas de producción.
- `ejemplos/`: Carpeta con scripts de prueba (casos difíciles, switch-case, arreglos).
- `README.md`: Documentación general del proyecto.

## 🚀 Cómo Probar la Gramática
Para validar la sintaxis de este lenguaje, se recomienda utilizar **BNF Playground**:

1. Copia el contenido de `gramatica.bnf`.
2. Ve a [BNF Playground](https://bnfplayground.pauliankline.com/).
3. Pega el código en el área de la gramática.
4. En el cuadro de prueba, ingresa el siguiente código "Hola Mundo" del lenguaje:

```cpp
empty ~ __main__ <| |> 
|:
    cout <| "Sistema Iniciado" |> !
:|