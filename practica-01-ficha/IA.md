# Declaración de uso de IA

> Obligatoria en todas las prácticas. Si usaste un asistente, descríbelo aquí con
> precisión. Si NO usaste ninguno, escribe eso y explica cómo resolviste la parte
> más difícil por tu cuenta — también cuenta como declaración válida.
>
> Recuerda: código de IA sin declarar se califica en CERO y no admite reintento.
> Declararlo honestamente NO baja tu nota. Lo que se evalúa es tu capacidad de auditar.

## Herramientas que usé
<!-- Claude, para ayudarme a estructurar y escribir el HTML de la ficha de personaje. -->

## Qué le pedí
<!-- Después de definir juntos la estructura de estadísticas, habilidades e
historia, le pedí que escribiera el código HTML completo de la ficha,
siguiendo la restricción de la misión de no usar CSS. -->

```
```

## Qué me devolvió
<!-- ```html
<section id="estadisticas">
    <h2>Estadísticas</h2>
    <table>
        <caption>Atributos principales</caption>
        <thead>
            <tr>
                <th scope="col">Estadística</th>
                <th scope="col">Valor</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th scope="row">Fuerza</th>
                <td>8/10</td>
            </tr>
            ...
        </tbody>
    </table>
</section>
``` -->

```javascript
```

## Qué estaba mal
<!-- El código HTML en sí no tenía errores de sintaxis ni de estructura, pero
sí tuve un problema fuera del código: la imagen que descargué inicialmente
tenía extensión .jpg pero en realidad era un archivo en formato WEBP, así
que el navegador no la mostraba aunque el atributo src apuntaba al nombre
correcto. El error no estaba en lo que generó la IA, sino en un recurso
externo que yo mismo agregué después.

Verifiqué esto abriendo las propiedades del archivo en Windows, donde
aparecía "Tipo de archivo: Chrome HTML Document (.webp)" en vez de una
imagen JPEG real -->

## Qué corregí y por qué
<!-- Descargué una imagen distinta, confirmé en sus propiedades que el tipo de
archivo real fuera JPG antes de usarla, y la coloqué en la carpeta src con
el nombre exacto que el código esperaba en el atributo src, para que
coincidiera sin necesidad de tocar el HTML de nuevo -->

```javascript
```

## Qué escribí yo desde cero
<!-- Definí yo mismo qué personaje usar y cómo enfocar las estadísticas, cuando
me preguntaron si quería un estilo RPG, del juego real, o una mezcla,
elegí la mezcla. También resolví por mi cuenta todo el problema del formato
de la imagen, sin ayuda de la IA para esa parte -->

## Reflexión
<!-- Sí me ahorró tiempo en la parte de escribir la estructura semántica
completa de una sola vez, en vez de ir elemento por elemento. Lo que más
tiempo me tomó no fue el código sino diagnosticar por qué la imagen no
cargaba. Volvería a usarlo para plantear la estructura inicial, pero
aprendí que hay que revisar con cuidado los recursos externos como
imágenes antes de asumir que el problema está en el código -->
