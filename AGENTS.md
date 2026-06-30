# Generador de propuestas TaskIQ

## Activación

Cuando el usuario envíe un texto corto que contenga un cliente, un servicio y un precio, por ejemplo:

> Hotel Botánico, gestión de redes sociales, 800 al mes

ejecuta de inmediato el flujo completo descrito aquí.

- No pidas confirmación.
- No hagas preguntas.
- Si falta algún detalle menor, realiza una inferencia razonable y profesional.
- No crees ramas alternativas.
- No crees pull requests.
- Trabaja y publica directamente en la rama `main`.

## Entregable

Crea una propuesta comercial en un único archivo HTML:

- bonita, profesional, elegante y fácil de leer;
- responsive para móvil y ordenador;
- sin librerías externas;
- sin imágenes inexistentes;
- sin datos privados;
- con todo el CSS incluido dentro del mismo archivo.

La propuesta debe incluir:

1. Nombre del cliente.
2. Servicio propuesto.
3. Problema que resuelve.
4. Qué incluye.
5. Precio.
6. Por qué trabajar con TaskIQ.
7. Próximo paso para empezar.

Redacta el problema, los entregables y los beneficios a partir del servicio proporcionado. Sé concreto, comercial y creíble. No inventes cifras, resultados garantizados, testimonios ni datos del cliente.

## Marca y contacto

- Marca: TaskIQ.
- Posicionamiento: inteligencia artificial, automatización, formación y creación de sistemas para negocios.
- Contacto y llamada a la acción: `https://wa.me/543416090152`.

## Dirección visual

- Fondo negro o muy oscuro.
- Texto blanco.
- Detalles y acentos en violeta.
- Estilo limpio, premium, moderno y claro.
- Mucho aire visual.
- Jerarquía tipográfica nítida.
- Excelente lectura en pantallas pequeñas.
- Botón visible de contacto por WhatsApp.
- HTML semántico y accesible, con contraste suficiente y estados de foco visibles.

## Nombre del archivo

Usa este formato:

`propuesta-[nombre-del-cliente]-[sufijo].html`

Reglas:

- todo en minúsculas;
- sin espacios;
- sin acentos;
- sin símbolos extraños;
- conserva como máximo las primeras 4 o 5 palabras del cliente;
- concatena las palabras del cliente sin espacios;
- usa un sufijo único de exactamente 4 letras minúsculas o números;
- evita sobrescribir archivos existentes.

Ejemplo:

`propuesta-hotelbotanico-a7k2.html`

## Publicación

El repositorio es:

`https://github.com/danteyercovich-spec/generador-de-propuestas`

La rama de publicación es `main`.

Después de crear y revisar el HTML:

1. Comprueba que no haya recursos externos ni contenido de marcador de posición.
2. Confirma que estás en `main`.
3. Incorpora únicamente el archivo de la propuesta y cualquier cambio estrictamente necesario para este flujo.
4. Crea un commit descriptivo.
5. Sube el commit directamente a `origin/main`.
6. No abras un pull request.

La URL pública final debe ser:

`https://danteyercovich-spec.github.io/generador-de-propuestas/NOMBRE-DEL-ARCHIVO.html`

Si el envío a GitHub falla, informa con claridad el error y el permiso o configuración que falta. No afirmes que la propuesta está publicada si el `push` no se completó.

## Notificación por Gmail

Solo después de que el `push` se complete correctamente, envía directamente un correo mediante Gmail a:

`taskiq.ia@gmail.com`

No crees un borrador.

Asunto:

`Propuesta lista para [cliente]`

Cuerpo:

```text
Propuesta de [cliente] lista:
[URL pública final]

Mensaje para reenviar por WhatsApp:
"Hola, te comparto la propuesta que preparé para ustedes: [URL pública final]"
```

Después del envío, informa al usuario el nombre del archivo, la URL pública, el commit publicado y que el correo fue enviado.
