# Práctica #2 – Codificación de Huffman en C++

## Descripción
Este proyecto implementa el algoritmo de **Huffman** para compresión de texto.  
Se incluyen dos variantes de códigos:
- **Huffman normal** (árbol de prefijos mínimo).
- **Huffman canónico** (códigos ordenados por longitud y alfabéticamente).
- Para un trabajo más completo se hizo uso de chatgpt , gemini y copilot

El programa:
1. Calcula las **frecuencias** de cada símbolo.
2. Construye el **árbol de Huffman** y lo muestra en forma de **tabla de nodos**.
3. Genera los **códigos Huffman normales** y sus **longitudes**.
4. Convierte los códigos en su versión **canónica**.
5. Comprime un texto y muestra:
   - Bits originales.
   - Bits comprimidos.
   - Ratio de compresión y porcentaje de reducción.
   - Cadena comprimida también en **hexadecimal**.
---

## Compilación y ejecución
El proyecto está configurado con **CMake** (usado en CLion).


