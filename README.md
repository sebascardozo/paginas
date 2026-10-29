# Páginas

Páginas web publicadas con GitHub Pages. Cada carpeta es una página independiente con su propio link.

| Carpeta | Link | Qué es |
|---|---|---|
| `campo-las-heras` | https://sebascardozo.github.io/paginas/campo-las-heras/ | Campo de 38.034 ha en Las Heras, Mendoza: mapa, fichas y plano |

## Cómo agregar una página nueva

1. Prepará la página como una carpeta con un archivo `index.html` adentro (más imágenes u otros archivos si hacen falta).
2. Usá un nombre de carpeta corto, en minúsculas, sin espacios ni tildes (ej.: `propuesta-capote-box`). Ese nombre queda en el link, así que evitá nombres de personas o datos privados.
3. En GitHub, dentro de este repositorio: **Add file > Upload files** y arrastrá la carpeta completa. Confirmá con **Commit changes**.
4. En uno o dos minutos la página queda en `https://sebascardozo.github.io/paginas/NOMBRE-DE-LA-CARPETA/`.
5. Sumala a la tabla de arriba.

## Cómo actualizar una página

Entrá a la carpeta, tocá **Add file > Upload files** y subí el `index.html` nuevo con el mismo nombre. Reemplaza al anterior y el link no cambia.

## Para tener en cuenta

- El repositorio es público: cualquiera puede ver estos archivos. No subas datos sensibles de clientes.
- El archivo `.nojekyll` evita que GitHub procese las páginas. No lo borres.
- Si un cliente quiere su propio dominio (ej.: `www.sucampo.com.ar`), se puede conectar más adelante.

## Notas por página

### campo-las-heras
- Fuente: plano de mensura escaneado (2003, visado 2005). Las fracciones se reconstruyeron con rumbos y distancias y se anclaron a las coordenadas POSGAR 94 del plano.
- Para mostrar el bloque de contacto, editá `CONFIG` dentro de `index.html` (WhatsApp y/o mail). Vacío, el bloque no aparece.
- La página no muestra el nombre del titular ni de los linderos.
