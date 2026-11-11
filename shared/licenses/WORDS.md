# Diccionario español para frases de acceso

Fuente: RLA-ES, versión 2.9, diccionario es_ES.dic instalado con LibreOffice. Autores: Santiago Bosio y colaboradores enumerados en RLA-ES-README.txt. Proyecto original: https://github.com/sbosio/rla-es .

Se elige MPL 1.1 o posterior entre las tres opciones ofrecidas. Se conserva el aviso original en RLA-ES-LICENSE.md y la licencia íntegra MPL-1.1.txt. El archivo spanish-words.js conserva atribución y es el código fuente preferido de la lista modificada; debe incluirse con la distribución y permanecer disponible bajo esa licencia. El generador y el verificador no son modificaciones del diccionario.

Modificación ARCO (2026-10-23): extraer lemas antes de '/', conservar minúsculas ASCII de 4 a 9 letras, con al menos dos vocales, aplicar las exclusiones editoriales documentadas en WORDS-FILTER.json y retirar formas imperativas pronominales y elegir 2048 entradas ordenadas en posiciones floor(i*N/2048), sin repetición. SHA-256 del es_ES.dic original: 6975dddec3d5d2c676069537bc67b4b5f786c65c5d4cf6703a82acf779ac9ec1. No se importan afijos ni sinónimos. No se afirma que sean las palabras más frecuentes; el vocabulario requiere revisión de facilidad de uso con el piloto.

Ocho elecciones independientes uniformes aportan 88 bits de espacio combinatorio (2048^8); no implican protección frente a compartir claves ni a un dispositivo comprometido.
