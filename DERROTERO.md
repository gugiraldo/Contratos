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
- **Cláusula decimoctava, Entrega, visitas y devolución** (hecha a partir del borrador): inventario y observaciones en 3 días hábiles, visitas de revisión con 24 horas de aviso, recibos de servicios al terminar, constancia de la devolución y cobro de daños con el contrato (mérito ejecutivo). En la cláusula octava se agregó que la pena no exime de reparar los daños. "Domicilio y ejemplares" pasó a ser la decimonovena. PDF de 6 páginas (letra del PDF 11,5 pt).
- **Cláusula decimoséptima, Normas de la vivienda** (las exigencias del arrendador): personas, visitas, servicios, mascotas, cambios, instalación eléctrica, cuidado, daños, comunicación, aseo del frente con casillas de días, video del recorrido y devolución. Se redactó para que lo importante sea **avisar**; el incumplimiento se maneja con la cláusula sexta, letra e) (aviso por escrito y plazo para corregir). "Domicilio y ejemplares" pasó a ser la decimoctava. PDF de 6 páginas.
- Tiempos del contrato para elegir con un botón ▾: plazo (3, 6 o 12 meses, u otro escrito a mano) y día de pago (5 o 10, u otro). La prórroga sigue al plazo ("períodos iguales"). El preaviso queda fijo en el texto porque lo regula la ley.
- Pie en cada hoja del PDF: nombres de las partes y "Hoja X de N" (como en las escrituras), para que no se pierda ni se cambie una hoja.
- Fotos de la cédula (cara con la foto y cara con la huella) con la cámara; en el computador usa la cámara web. Se pueden girar, enderezar, acercar y encuadrar.
- Huella tomada de la foto de la cédula (se recorta con un recuadro); ya no hay huella dibujada.
- **Asistente de firma paso a paso** (botón "Iniciar proceso de firma"): elegir quién firma → leer/escuchar y "Sí, lo acepto" (queda fecha y hora en el contrato) → datos → referencias → fotos de la cédula → huella → firma → resumen y PDF final (descargar o compartir). Sin selfie: se decidió que es incómodo; la cédula es el documento de identificación.

- Por defecto el contrato viene con **referencias personales** marcadas y **codeudor** sin marcar. Cláusula cuarta: la prórroga puede ser de 6 o 12 meses si las partes lo acuerdan por escrito.
- **Audio público** generado en NotebookLM (debate, 13 min, enfocado en referencias, dice "doña María") y publicado como `contrato-audio.mp3`; el botón "Escuchar el contrato" ya funciona.
- **Decidido**: los datos de la arrendadora (nombre, cédula, dirección) quedan prellenados en la página pública; no hay PIN. Flujo: el interesado escucha el audio, habla con doña María y, si ambos están de acuerdo, se llenan los datos del inquilino y se firma en persona.

- **Asistente de firma completo** (incluye notas del inventario, un cuadro de varios renglones): ahora llena y marca todas las partes del contrato. Arrendador: condiciones (canon con su texto en letras automático, día de pago, plazo 3/6/12 u otro, fecha de inicio, ciudad y fecha de la firma, cláusula penal, preaviso), personas máximas (y su texto en letras) con nombres, días de aseo del frente, y Anexo 2 (fecha de entrega, agua/energía/gas con forma y lecturas, inventario digital/escrito y enlace). Arrendatario: ve un resumen para revisar. Firma del inventario (opcional, con "usar la misma firma"). Valores ya marcados por defecto (agua y energía aplican, agua por factura, energía recargable, gas pipeta, inventario digital, ciudad Carepa, canon 400.000, 4 personas); también vuelven al limpiar datos del inquilino.

- **Firma en papel** (casilla "Firma en papel (imprimir)" arriba, o en la pantalla de elegir quién firma): se llenan los datos en el asistente sin fotos ni firma en pantalla, se descarga el PDF, se imprime, cada parte firma y pone la huella a mano y pega la fotocopia de la cédula (recuadros con "lado de la foto" / "lado de la huella"). Lo digital sigue igual.
- **Modo "lo lleno yo con lo que me envió el cliente"**: la persona manda por WhatsApp las dos caras de la cédula, una foto de su firma hecha a mano en hoja blanca y un mensaje aceptando; en el asistente se registra "Aceptó por WhatsApp el [fecha]", se cargan las fotos desde la galería y la firma con "Usar foto de la firma" (queda en blanco y negro sobre fondo blanco).
- Por decidir: firma a distancia con "Enviar mi parte" / "Cargar la parte del cliente" (archivo por WhatsApp).

## Pendiente (en este orden de prioridad lo que falta)
0. ~~Firma remota con las dos partes~~ **Decidido**: sin firma a distancia. Al interesado solo se le comparte el audio (y el enlace para leer); si decide tomarlo, confirma por teléfono/WhatsApp y la firma se hace **presencial** al día siguiente, llenando todo en el celular de la arrendadora (así el PDF final lleva las dos partes). Quien llega lleva el dinero completo que diga el contrato.
1. ~~Sección de exigencias del arrendador~~ Hecha (cláusula decimoséptima). Falta revisar si se quiere ajustar algo.
2. ~~Audio del contrato~~ Hecho. (Antes: generarlo en NotebookLM (modo debate, con el prompt acordado, cambiando "de la primera a la decimoséptima" por "decimoctava") y publicarlo como `contrato-audio.mp3`. Antes, decidir si se agrega el borrador de entrega y restitución (`BORRADOR-garantias-y-entrega.md`), que cambiaría la numeración otra vez.)
3. ~~Botón Compartir PDF y declaración "leí o escuché el contrato"~~ Hechos dentro del asistente de firma.
4. Modo "solo leer y escuchar" para el enlace que se le envía al interesado (propuesto, por decidir).
5. ~~PIN de acceso a la página~~ **Descartado por ahora** (datos de la arrendadora prellenados a propósito). Nota original, cuando el contrato esté completamente listo. Nota: un PIN escrito en una página pública no protege datos de verdad; la opción segura es cifrar el contrato con el PIN (ver conversación).
6. ~~Publicación para el arrendatario~~ Hecho con GitHub Pages sobre el repositorio `Contratos` (público).

## Sobre el depósito (decidido)
- Se **quitó** de la cláusula séptima la frase "No se exige depósito en dinero". No es obligatoria, pero quitarla **no vuelve legal** el depósito: el art. 16 de la Ley 820 de 2003 lo prohíbe igual, y según las fuentes consultadas también prohíbe disfrazarlo (primer mes más caro con "descuento" después, cobro verbal, otro nombre).
- Cláusula séptima: con codeudor dice solo que el codeudor responde por las obligaciones; sin codeudor (con o sin referencias) dice una frase neutral de la ley: el arrendatario responde con todos sus bienes (art. 2488, Código Civil). Las referencias no agregan texto a esa cláusula.
- La cláusula segunda sigue diciendo que solo se paga por anticipado el primer mes de arriendo.
- Formas legales de protegerse: canon bien fijado (tope 1 % del valor comercial), codeudor, seguro de arrendamiento, cláusula penal, recibos de servicios al día al entregar, inventario con fotos, y buen estudio del arrendatario antes de firmar.
- Borrador de la sección "Condiciones de entrega, servicios públicos y restitución" en `BORRADOR-garantias-y-entrega.md` (todavía no está en el contrato; falta que se lea y se corrija).

## Notas
- Una firma y huella dibujadas en pantalla son firma electrónica simple y una constancia visual; no son validación biométrica. Para nivel bancario hace falta un servicio de firma electrónica certificada.
