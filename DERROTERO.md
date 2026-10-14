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

## Pendiente (en este orden de prioridad lo que falta)
0. **Decidir qué hacer con la huella gráfica**: hoy es el mismo dibujo para todas las personas (no es biométrica). Opciones: dejarla rotulada como "constancia gráfica", quitarla, o reemplazarla por una evidencia real (código por WhatsApp/SMS, foto de la cédula y selfie, o firma electrónica certificada).
1. **Sección de exigencias del arrendador**: condiciones que no se negocian, separadas de las demás. (Por definir con el dueño del contrato.)
2. **Audio del contrato**: generarlo en NotebookLM (modo debate, con el prompt acordado) y publicarlo como `contrato-audio.mp3`.
3. Botón **Compartir PDF** (WhatsApp / correo) desde el celular.
4. Declaración "leí o escuché el contrato completo" antes de firmar (opcional, por decidir).
5. **PIN de acceso a la página — AL FINAL**, cuando el contrato esté completamente listo. Nota: un PIN escrito en una página pública no protege datos de verdad; la opción segura es cifrar el contrato con el PIN (ver conversación).
6. ~~Publicación para el arrendatario~~ Hecho con GitHub Pages sobre el repositorio `Contratos` (público).

## Notas
- Una firma y huella dibujadas en pantalla son firma electrónica simple y una constancia visual; no son validación biométrica. Para nivel bancario hace falta un servicio de firma electrónica certificada.
