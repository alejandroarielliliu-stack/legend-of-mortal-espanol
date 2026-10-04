# Legend of Mortal — parche en español

**Traducción no oficial al español de Legend of Mortal (活俠傳 / Huoxia Zhuan), para PC.**

Este parche sustituye los textos del parche inglés por un **borrador traducido automáticamente al español**, con una pequeña muestra revisada. No es una traducción profesional ni está revisado todo el juego.

## Descargar

[**Descargar el parche español v0.1.0 (ZIP)**](https://github.com/alejandroarielliliu-stack/legend-of-mortal-espanol/releases/download/v0.1.0/Legend-of-Mortal-espanol-v0.1.0.zip)

[Ver versiones y notas de publicación](https://github.com/alejandroarielliliu-stack/legend-of-mortal-espanol/releases) · [Informar de un error](https://github.com/alejandroarielliliu-stack/legend-of-mortal-espanol/issues)

## Compatibilidad y contenido

| Elemento | Versión o alcance |
| --- | --- |
| Juego utilizado al preparar el parche | 1.0.5000.13 |
| Parche inglés de referencia | LegendOfMortalOverLlm 2026.09.29.21.13 |
| Archivos de traducción | 47 archivos CSV/YAML |
| Entradas procesadas | 72.830 |
| Historia | Los 17 capítulos incluidos en el parche inglés de referencia |
| Comprobación previa en el juego | Arranque y menús; no una partida completa |

No se garantiza compatibilidad con otras versiones. El ZIP contiene los textos editables y esta documentación; requiere el juego y el complemento de traducción inglés por separado. No incluye el juego, el cargador, ejecutables ni partidas guardadas.

## Instalación paso a paso

1. Instala el juego y el [parche inglés LegendOfMortalOverLlm](https://github.com/joshfreitas1984/LegendOfMortalOverLlm), siguiendo sus instrucciones. La referencia usada aquí es la versión **2026.09.29.21.13**; una versión posterior puede cambiar los textos o el funcionamiento.
2. Comprueba que el parche inglés funciona y **cierra el juego**.
3. Abre la carpeta del juego. En Steam: biblioteca → clic derecho en el juego → Administrar → Ver archivos locales. Localiza `Mortal.exe`.
4. Guarda una copia de seguridad de la carpeta `Mods/English` fuera de la carpeta del juego.
5. Descarga y descomprime `Legend-of-Mortal-espanol-v0.1.0.zip`.
6. Copia la carpeta `Mods` del ZIP junto a `Mortal.exe`. Acepta reemplazar los archivos de traducción existentes.
7. Abre el juego y comprueba que el menú muestra textos como «Nueva partida» y «Opciones».

La ruta final debe quedar así:

```text
Carpeta del juego/
├── Mortal.exe
└── Mods/
    └── English/
        ├── System_zh-cn.csv
        ├── Story_1.csv
        └── ...
```

**No cambies el nombre `English` por `Spanish` ni renombres los archivos:** el complemento utiliza esos nombres para localizar los textos.

## Problemas frecuentes

- **Sigue en chino:** comprueba primero que funciona el parche inglés y que no has creado accidentalmente `Mods/Mods/English`.
- **Vuelve al inglés después de actualizar:** una actualización del parche base puede reemplazar los textos. Guarda tu copia española y comprueba la compatibilidad antes de volver a aplicarla.
- **Textos extraños, nombres inconsistentes o frases cortadas:** el borrador procede del inglés y puede heredar sus errores, además de los de traducción automática y longitud de texto.
- **Hay textos sin traducir:** no se incluyen textos ausentes del parche inglés de referencia ni traducción de imágenes. Procesar todas las entradas disponibles no equivale a haber revisado todo el juego.

## Desinstalar

Cierra el juego y restaura la copia de seguridad de `Mods/English`. Para quitar también el complemento inglés, sigue las instrucciones de su proyecto original.

## Ayudar a mejorar la traducción

Abre un [issue](https://github.com/alejandroarielliliu-stack/legend-of-mortal-espanol/issues) con el capítulo o pantalla, el texto observado, una propuesta de corrección y las versiones del juego y del parche. Una captura ayuda; evita incluir datos personales. Los CSV y YAML editables están dentro del ZIP.

## Créditos y derechos

- Juego original: **Obb Studio** y sus titulares.
- Traducción inglesa y complemento: [joshfreitas1984/LegendOfMortalOverLlm](https://github.com/joshfreitas1984/LegendOfMortalOverLlm) y sus colaboradores.
- Borrador español: traducción automática mediante Google Translate, con una pequeña muestra revisada.
- Publicación y mantenimiento de esta distribución: [alejandroarielliliu-stack](https://github.com/alejandroarielliliu-stack).

Proyecto de fans, no oficial y no afiliado a los desarrolladores. Los textos derivan del juego y del parche inglés. No se atribuye aquí la autoría de esos materiales ni se concede una licencia sobre contenido de terceros. El repositorio base no declaraba una licencia al preparar esta copia.

## Verificación del paquete

Se han comprobado las claves, el orden y el número de registros CSV, así como variables y etiquetas de formato; en YAML se conservan los campos no traducibles. Esta validación estructural no certifica la calidad lingüística ni todas las escenas del juego. `SHA256SUMS.txt` permite comprobar la integridad del ZIP descargado.

## English summary

Unofficial **Spanish translation patch for Legend of Mortal (活俠傳 / Huoxia Zhuan)**. Machine-translated draft based on the English LegendOfMortalOverLlm patch. Requires the game and the English mod separately. Includes installation instructions, editable translation files and known limitations. Not a fully human-reviewed translation.
