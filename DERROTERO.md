# Derrotero del contrato de arrendamiento

Archivo principal: `contrato.html` (página web editable; se descarga como PDF).

## Hecho
- Casillas que se marcan con un clic (inventario Digital / Escrito).
- Servicios que aplican o no (agua, energía, gas por red / pipeta / no aplica).
- Fechas con calendario propio, escritas en letras.
- Codeudor y referencias personales (2 personas) opcionales: se muestran u ocultan partes del contrato.
- Menú superior de ancho completo.
- Texto escrito en mayúsculas (menos correo y enlace de la carpeta).
- Firma y huella digitales, con el espacio en blanco como respaldo manual al imprimir.
- Diseño para celular sin desbordamiento; PDF igual desde cualquier pantalla.
- Botón para escuchar el audio del contrato (espera el archivo `contrato-audio.mp3`).
- Botón para borrar o restaurar los datos del arrendador (nombre, cédula, dirección).
- PDF en 4 páginas (5 si lleva codeudor y referencias a la vez), igual desde cualquier pantalla.
- Página pública con GitHub Pages: https://gugiraldo.github.io/Contratos/
- Menú del celular desplegable, con botones grandes.
- Fotos de la cédula (cara con la foto y cara con la huella) con la cámara; en el computador usa la cámara web. Se pueden girar, enderezar, acercar y encuadrar.
- Huella tomada de la foto de la cédula (se recorta con un recuadro); ya no hay huella dibujada.
- **Asistente de firma paso a paso** (botón "Iniciar proceso de firma"): elegir quién firma → leer/escuchar y "Sí, lo acepto" (queda fecha y hora en el contrato) → datos → referencias → fotos de la cédula → huella → firma → resumen y PDF final (descargar o compartir). Sin selfie: se decidió que es incómodo; la cédula es el documento de identificación.

## Pendiente (en este orden de prioridad lo que falta)
0. ~~Firma remota con las dos partes~~ **Decidido**: sin firma a distancia. Al interesado solo se le comparte el audio (y el enlace para leer); si decide tomarlo, confirma por teléfono/WhatsApp y la firma se hace **presencial** al día siguiente, llenando todo en el celular de la arrendadora (así el PDF final lleva las dos partes). Quien llega lleva el dinero completo que diga el contrato.
1. **Sección de exigencias del arrendador**: condiciones que no se negocian, separadas de las demás. (Por definir con el dueño del contrato.)
2. **Audio del contrato**: generarlo en NotebookLM (modo debate, con el prompt acordado) y publicarlo como `contrato-audio.mp3`.
3. ~~Botón Compartir PDF y declaración "leí o escuché el contrato"~~ Hechos dentro del asistente de firma.
4. Modo "solo leer y escuchar" para el enlace que se le envía al interesado (propuesto, por decidir).
5. **PIN de acceso a la página — AL FINAL**, cuando el contrato esté completamente listo. Nota: un PIN escrito en una página pública no protege datos de verdad; la opción segura es cifrar el contrato con el PIN (ver conversación).
6. ~~Publicación para el arrendatario~~ Hecho con GitHub Pages sobre el repositorio `Contratos` (público).

## Por revisar con un abogado
- El contrato dice (cláusulas segunda y séptima) que **no se exige depósito** (art. 16, Ley 820 de 2003) y que solo se paga por anticipado el primer mes. Si en la práctica se piensa cobrar "depósito + mes de arriendo", hay contradicción con el propio contrato.

## Notas
- Una firma y huella dibujadas en pantalla son firma electrónica simple y una constancia visual; no son validación biométrica. Para nivel bancario hace falta un servicio de firma electrónica certificada.
