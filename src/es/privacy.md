title: Política de privacidad
description: Cómo trata {{APP_NAME}} tus fotos y tus datos: qué se envía al servicio de IA, bases jurídicas, qué se guarda y durante cuánto tiempo, y tus derechos en todo el mundo.

# Política de privacidad

> Fecha de entrada en vigor: {{EFFECTIVE_DATE}}

{{APP_NAME}} (la «App») convierte tus fotos en retratos de monstruos de Halloween mediante un servicio de imágenes de IA de terceros. Esta política explica qué información trata la App, para qué y con qué base jurídica, quién la recibe, cuánto tiempo se conserva y qué derechos y opciones tienes, vivas donde vivas. La App la gestiona {{DEVELOPER_NAME}} («nosotros»), responsable del tratamiento de tus datos personales (la parte que decide cómo y para qué se tratan). Nuestros datos de contacto están en la sección 14.

## 1. Resumen

- Las fotos que eliges se envían a un servicio de IA externo (OpenAI) solo para crear el retrato que has pedido. Te pedimos tu permiso expreso antes de que ocurra por primera vez, y puedes retirarlo en cualquier momento.
- No conservamos las fotos que envías. Las reenviamos, en memoria, al servicio de IA y devolvemos el resultado a tu teléfono.
- Tus retratos terminados se guardan en tu teléfono. Para que un retrato no se pierda si se corta la conexión o se cierra la App mientras se crea, guardamos una copia de cada retrato recién generado, cifrada, en nuestro servidor durante 24 horas como máximo. Se usa solo para entregar el retrato a tu teléfono y se elimina en cuanto tu teléfono confirma que lo ha guardado, o a las 24 horas como muy tarde.
- No usamos tus fotos ni tu cara para entrenar modelos de IA, para publicidad ni para analítica. No identificamos ni reconocemos a las personas por su cara.
- No hay cuenta, ni SDK de publicidad o analítica en la App, ni rastreo entre apps y sitios web de otras empresas. Nuestro servidor comparte tu identificador anónimo y tus registros de compra (nunca fotos) con un proveedor de analítica de suscripciones (RevenueCat, sección 4).
- Puedes eliminar tus datos desde la App en cualquier momento (Perfil > Eliminar todos mis datos) y retirar tu consentimiento de IA (Perfil > Retirar consentimiento de IA).

## 2. Información que tratamos

**a. Fotos que eliges o haces.** Cuando eliges una foto de tu fototeca o haces una con la cámara y tocas para crear un retrato, la foto (un JPEG redimensionado) y el look que has seleccionado se envían a nuestro backend y de ahí al servicio de IA. Si eliges un look de grupo o de pareja con selfies separados, se envía cada selfi. Las fotos pueden mostrar la cara de otras personas además de la tuya. Solo accedemos a las fotos que eliges de forma expresa; la App no analiza tu fototeca.

**b. Comprobación de caras en tu dispositivo.** Antes de enviar una foto, la App usa el framework Vision de Apple en tu dispositivo para comprobar que hay un número adecuado de caras (por ejemplo, exactamente dos en un look de pareja). Esta comprobación se realiza por completo en tu teléfono. Detecta dónde hay caras y cuántas hay. No crea una plantilla facial ni ningún identificador biométrico, no identifica ni reconoce a nadie, y sus resultados no se guardan ni se envían a ningún sitio, salvo el número de caras, que se usa para redactar las instrucciones para el servicio de IA.

**c. Retratos generados.** El resultado del servicio de IA vuelve a la App y se guarda en tu teléfono. Una copia temporal de cada retrato generado se conserva cifrada en nuestro almacenamiento en la nube durante 24 horas como máximo, solo para entregarla a tu teléfono si falla la conexión; tus selfies y demás fotos de entrada no se guardan nunca.

**d. Identificador anónimo y créditos.** La App crea un identificador anónimo de Firebase para tu instalación. Lo usamos para mantener tu saldo de créditos y para registrar las compras y los movimientos de créditos (ID de transacción, producto, fecha). No te pedimos que crees una cuenta y no recogemos tu nombre, tu correo electrónico ni tu teléfono en la App. Cuando llamamos al servicio de IA incluimos un identificador seudónimo derivado de tu ID anónimo mediante un hash unidireccional con clave; no es tu identificador real y el servicio de IA no puede vincularlo contigo. Ayuda al servicio de IA a detectar abusos.

**e. Compras.** Las compras y suscripciones las procesa Apple. Nunca recibimos los datos de tu tarjeta de pago ni de tu cuenta de Apple. Recibimos la confirmación de una transacción (ID de transacción, producto, fechas, estado de renovación o reembolso) para poder conceder o retirar créditos. Si tocas Restaurar compras, la App envía a nuestro servidor los registros de compra firmados por Apple para que podamos verificarlos y volver a vincular tus compras y los créditos restantes a la App de este dispositivo. Estos registros contienen el producto, las fechas y el identificador de compra aleatorio por instalación que generamos nosotros; no contienen tu nombre, tu correo electrónico ni tus datos de pago. Si los registros coinciden con otra instalación de la App, los créditos restantes de esa instalación se mueven (no se copian) a esta. Restaurar no requiere iniciar sesión y no crea ningún tipo nuevo de dato personal. También enviamos estos registros de compra, junto con tu identificador anónimo, desde nuestro servidor a RevenueCat (sección 4) para poder ver estadísticas de suscripciones e ingresos; la propia App no contiene software de RevenueCat y no envía nada a RevenueCat.

**f. Integridad del dispositivo.** Para proteger el servicio frente a abusos, usamos App Attest de Apple (a través de Firebase App Check) para confirmar que las solicitudes proceden de una copia genuina de la App, y DeviceCheck de Apple para recordar, con un único ajuste de activado o desactivado que guarda Apple, que un dispositivo ya ha usado su primer retrato gratis. DeviceCheck no nos dice quién eres.

**g. Registros técnicos.** Nuestros servicios en la nube y el servicio de IA pueden registrar información técnica como la dirección IP, la hora de la solicitud y los códigos de error, por motivos de seguridad y para hacer funcionar el servicio. Nuestro propio código no escribe fotos, datos faciales ni datos personales en los registros. No usamos estos registros para elaborar perfiles sobre ti.

**h. Mensajes al servicio de soporte.** Si nos escribes un correo, recibimos tu dirección de correo electrónico y lo que escribas, y lo usamos únicamente para responderte.

**i. Ajustes en el dispositivo.** La App guarda preferencias sencillas en tu teléfono (por ejemplo, que has terminado la introducción y que has aceptado el aviso de IA).

No recogemos tu ubicación exacta, tus contactos, tus datos de salud ni tu historial de navegación.

## 3. Para qué los usamos y bases jurídicas

| Finalidad | Información | Base jurídica (RGPD y RGPD del Reino Unido; bases equivalentes en otras leyes) |
| --- | --- | --- |
| Crear el retrato que pides: enviar tus fotos y el look elegido al servicio de IA | Fotos, look seleccionado, número de caras, identificador seudónimo | Tu consentimiento (art. 6.1.a), otorgado en la App antes de la primera creación. Puedes retirarlo en cualquier momento; la retirada no afecta al tratamiento anterior. |
| Créditos, compras, suscripciones, Restaurar compras, devolución de créditos | Identificador anónimo, saldo de créditos, registros de compra | Ejecución de nuestro contrato contigo (art. 6.1.b); conservación de los registros que la ley nos obliga a conservar (art. 6.1.c) |
| Entender las suscripciones y los ingresos (analítica de suscripciones) | Identificador anónimo, registros de compra y renovación firmados por Apple | Nuestro interés legítimo en gestionar y mejorar un servicio de pago (art. 6.1.f). Puedes oponerte (sección 7). |
| Prevenir el fraude y los abusos, hacer cumplir el límite de un retrato gratis por dispositivo y mantener seguro el servicio (App Check, DeviceCheck, límites de uso, filtros de seguridad, registros) | Identificador anónimo, señales de integridad del dispositivo, registros técnicos | Nuestro interés legítimo en proteger el servicio, a otros usuarios y a nosotros mismos (art. 6.1.f). Puedes oponerte (sección 7). |
| Atender las solicitudes de soporte | Correo electrónico, mensaje, ID de soporte | Nuestro contrato contigo y nuestro interés legítimo en ayudarte |
| Cumplir la ley y gestionar reclamaciones legales | Registros descritos en la sección 6 | Obligación legal e interés legítimo |

**Caras y fotos.** Las caras y las fotos de tus imágenes se usan únicamente para generar el retrato que has pedido. No se usan para entrenar ni mejorar ningún modelo de IA, ni para publicidad o marketing, ni para analítica o elaboración de perfiles, ni se venden ni se comparten con esos fines. No creamos una base de datos de caras ni analizamos las fotos para deducir características sensibles de nadie.

Si no aceptas enviar fotos al servicio de IA, puedes abrir la App igualmente, pero no podrá crear retratos.

## 4. Quién recibe la información

Solo compartimos información con los proveedores de servicios necesarios para hacer funcionar la App:

- **OpenAI** (generación de imágenes). Tus fotos y el look seleccionado se envían a la API de OpenAI para producir tu retrato. OpenAI actúa como nuestro encargado del tratamiento. Según la política de datos de la API que OpenAI tiene publicada, los datos enviados a la API no se usan para entrenar ni mejorar los modelos de OpenAI salvo que el cliente lo autorice (nosotros no lo hemos autorizado), y el contenido de la API puede conservarse en registros de supervisión de abusos hasta 30 días, o más si lo exige la ley o es necesario para proteger los servicios. Política de OpenAI: https://developers.openai.com/api/docs/guides/your-data . OpenAI también puede analizar las imágenes subidas para detectar material de abuso sexual infantil y conservar una imagen marcada para su revisión, según se describe en esa política.
- **Google (Firebase y Google Cloud)** (alojamiento del backend, identificador anónimo, registros de créditos y compras, comprobaciones de integridad de la app, almacenamiento temporal cifrado de los retratos generados). Google actúa como nuestro encargado del tratamiento conforme a sus condiciones de tratamiento de datos. Nuestro backend funciona en Estados Unidos (Iowa).
- **RevenueCat, Inc.** (Estados Unidos) (analítica de suscripciones y compras). Nuestro servidor envía a RevenueCat tu identificador anónimo y los registros de compra firmados por Apple de tus compras (producto, fechas, entorno, el identificador aleatorio de compra y los eventos de renovación, reembolso y cancelación). RevenueCat actúa como nuestro encargado del tratamiento. No se envían fotos, rostros, nombres, correos electrónicos ni identificadores de dispositivo, y la App no contiene software de RevenueCat. Cuando usas Eliminar todos mis datos, también pedimos a RevenueCat que elimine su registro de tu identificador anónimo.
- **Apple** (compras en App Store, App Attest, DeviceCheck y la opción de compartir tus retratos con la hoja para compartir de iOS, que inicias tú mismo). Apple actúa como responsable del tratamiento independiente de sus propios servicios.
- **Autoridades o sucesores**, cuando lo exija la ley o para proteger derechos y seguridad, o en el marco de una transmisión del negocio, con aviso cuando sea obligatorio.

No vendemos tu información personal ni la compartimos para publicidad conductual entre contextos.

Cuando compartes un retrato con otra app (por ejemplo, desde la hoja para compartir), a lo que compartas se le aplica la política de privacidad de esa app.

## 5. Transferencias internacionales

Estamos establecidos en Turquía, y nuestros proveedores tratan datos en Estados Unidos y posiblemente en otros países donde operan. Por tanto, si usas la App en el Espacio Económico Europeo, el Reino Unido, Suiza, Turquía, Brasil, Corea del Sur, Japón o en cualquier otro lugar, tu información se transfiere a otros países, incluidos países cuya legislación de protección de datos puede diferir de la tuya.

Aplicamos las garantías que exige tu legislación para estas transferencias, cuando procedan: una decisión de adecuación (por ejemplo, el Marco de Privacidad de Datos UE-EE. UU., cuando el destinatario participa), cláusulas contractuales tipo (UE y adenda del Reino Unido) en las condiciones de tratamiento de datos de nuestros proveedores, otros mecanismos lícitos reconocidos por la legislación local (véase la sección 8) y tu consentimiento cuando la ley lo permite. También limitamos lo que se envía a lo necesario, usamos conexiones cifradas y no enviamos al servicio de IA tu nombre, tu correo electrónico ni un identificador real de cuenta. Puedes pedirnos información sobre las garantías (sección 14).

## 6. Cuánto tiempo conservamos la información

| Información | Conservación |
| --- | --- |
| Fotos enviadas para una creación | No las conservamos. Solo permanecen en memoria mientras se procesa la solicitud. El servicio de IA puede conservarlas hasta 30 días en registros de supervisión de abusos (véase la sección 4). |
| Retratos generados | En tu teléfono hasta que los elimines o uses Eliminar todos mis datos. Una copia temporal de entrega se conserva cifrada en nuestro servidor durante 24 horas como máximo (se elimina cuando tu teléfono confirma el guardado, y con Eliminar todos mis datos). |
| Identificador anónimo, saldo de créditos, movimientos de créditos, registros de compra (incluidos los que usa Restaurar compras) | Hasta que elimines tus datos en la App. Los registros con saldo cero, sin suscripción activa y sin uso de la App durante 24 meses se eliminan automáticamente (comprobación diaria), junto con el registro de inicio de sesión anónimo. |
| Registro en RevenueCat (identificador anónimo, registros de compra y renovación) | Hasta que elimines tus datos en la App o el registro se elimine automáticamente tras 24 meses de inactividad (véase arriba); entonces pedimos a RevenueCat que lo elimine. Las condiciones propias de RevenueCat rigen las copias de seguridad. |
| Registros de transacciones de compra después de eliminar tus datos en la App o tras la eliminación automática | El ID de transacción, el producto y las fechas se conservan sin ningún vínculo con tu identificador anónimo, para procesar reembolsos, evitar conceder créditos dos veces y cuando la ley lo exija (por ejemplo, por motivos contables). |
| Marca de eliminación | Después de que elimines tus datos, conservamos tu antiguo identificador anónimo aleatorio y la hora de la eliminación, para que el registro eliminado no pueda volver a crearse. No contiene ninguna otra información. |
| Registros técnicos | Un periodo limitado necesario para la seguridad y el funcionamiento (por ejemplo, Firebase Authentication registra las direcciones IP durante unas semanas). |
| Correos al servicio de soporte | El tiempo necesario para ayudarte; después se eliminan. |

## 7. Tus derechos y opciones

Según dónde vivas, tienes algunos o todos estos derechos: saber si tratamos tus datos y obtener una copia (acceso); rectificarlos; suprimirlos; limitar el tratamiento; recibir tus datos en un formato portable; oponerte al tratamiento basado en intereses legítimos; retirar el consentimiento en cualquier momento; no ser objeto de decisiones basadas únicamente en el tratamiento automatizado con efectos jurídicos o similares significativos (nosotros no tomamos ninguna); y presentar una reclamación ante una autoridad de control de protección de datos.

Cómo ejercerlos:

- **Eliminar todos mis datos (en la App).** Perfil > Eliminar todos mis datos borra los retratos, las miniaturas de selfies y el consentimiento de IA guardados en tu teléfono, y nos pide que eliminemos el registro del servidor vinculado a tu identificador anónimo (saldo de créditos y registros de compra) y pide a RevenueCat que elimine su registro de ese identificador. Los créditos no usados se pierden al hacerlo. Eliminar solo la App no elimina el registro del servidor.
- **Retirar consentimiento de IA.** Perfil > Retirar consentimiento de IA. No se volverán a enviar fotos hasta que vuelvas a aceptarlo.
- **Acceso, portabilidad, rectificación, limitación, oposición.** Escribe a {{SUPPORT_EMAIL}} e incluye el ID de soporte que aparece en la pestaña Perfil, para que podamos localizar tu registro. Sin él no podemos buscar tus datos, porque la App es anónima. Te enviaremos el registro vinculado a tu ID de soporte (saldo de créditos, movimientos de créditos y registros de compra) en un formato común y legible por máquina. Tus retratos ya están en tu teléfono.
- **Acceso a las fotos.** Puedes cambiar los permisos de la cámara y de las fotos en los Ajustes de iOS. La App usa el selector de fotos del sistema, que le da acceso solo a las fotos que seleccionas, y guarda en tu fototeca únicamente cuando tocas Guardar.
- **Las suscripciones** se gestionan o se cancelan en los ajustes de tu cuenta de Apple (consulta nuestros Términos de uso).

Respondemos en un plazo de un mes (RGPD y RGPD del Reino Unido; en solicitudes complejas podemos ampliarlo hasta dos meses más y te lo comunicaremos), o en el plazo que fije la ley que te sea aplicable. Podemos pedirte que confirmes que la solicitud procede del titular del ID de soporte. También puedes presentar una reclamación ante tu autoridad de control de protección de datos local (en el EEE, la autoridad del país donde vives o trabajas, por ejemplo la Agencia Española de Protección de Datos (AEPD) en España; en el Reino Unido, la Information Commissioner's Office; en Turquía, la Junta de Protección de Datos Personales; en Brasil, la ANPD; en Corea del Sur, la PIPC; en Japón, la PPC). Agradeceríamos la oportunidad de resolver antes tu inquietud.

## 8. Información para regiones concretas

### 8.1 Espacio Económico Europeo, Reino Unido y Suiza

{{DEVELOPER_NAME}} es el responsable del tratamiento. Las bases jurídicas están en la sección 3, las transferencias en la sección 5, la conservación en la sección 6 y tus derechos en la sección 7, incluidos los derechos de oposición y de retirada del consentimiento. No hemos designado un delegado de protección de datos; las preguntas sobre privacidad se dirigen a la dirección de la sección 14. Si la ley de tu país fija para consentir el tratamiento de datos personales una edad superior a 13 años (por ejemplo, de 14 a 16 años en varios países europeos), consulta la sección 9.

### 8.2 Turquía (Ley n.º 6698, KVKK)

{{DEVELOPER_NAME}} es el responsable del tratamiento de los datos. Tratamos datos personales para las finalidades de la sección 3, sobre la base de tu consentimiento expreso (envío de fotos al servicio de IA), la celebración y ejecución de un contrato, nuestros intereses legítimos (prevención del fraude y seguridad) y las obligaciones legales. Conforme al artículo 11 de la Ley n.º 6698, puedes preguntar si se tratan tus datos, solicitar información, conocer la finalidad del tratamiento y si se usan conforme a ella, conocer los terceros a quienes se transfieren en Turquía o en el extranjero, solicitar su rectificación o supresión, solicitar que estas operaciones se notifiquen a los terceros, oponerte a los resultados perjudiciales para ti y reclamar una indemnización por los daños sufridos. Dirígete a nosotros en la dirección de la sección 14, con tu ID de soporte; respondemos en treinta días como máximo. Si no estás conforme, puedes presentar una reclamación ante la Junta de Protección de Datos Personales (Kişisel Verileri Koruma Kurulu, KVKK). Los datos se transfieren al extranjero (sección 5) en las condiciones del artículo 9 de la Ley n.º 6698.

### 8.3 Brasil (LGPD)

{{DEVELOPER_NAME}} es el responsable del tratamiento y el contacto para los titulares de los datos es la dirección de la sección 14. Nuestras bases jurídicas, conforme al artículo 7 de la Ley n.º 13.709/2018 (Lei Geral de Proteção de Dados, LGPD), son el consentimiento, la ejecución de un contrato, el ejercicio regular de derechos y los intereses legítimos. Tienes los derechos del artículo 18 (confirmación del tratamiento, acceso, rectificación, anonimización, bloqueo o supresión, portabilidad, información sobre el intercambio de datos, información sobre las consecuencias de negar el consentimiento y revocación del consentimiento) y puedes presentar una petición ante la Autoridad Nacional de Protección de Datos (ANPD). Las transferencias internacionales se realizan como se indica en la sección 5 y en el artículo 33 de la LGPD.

### 8.4 Corea del Sur (PIPA)

Tratamos la información personal de la sección 2 únicamente para las finalidades de la sección 3 y la conservamos durante los plazos de la sección 6. No facilitamos información personal a terceros salvo en lo descrito en la sección 4. Encomendamos el tratamiento descrito en la sección 4 a OpenAI, a Google y a RevenueCat, y los supervisamos mediante cláusulas contractuales. Tus fotos y la información relacionada se transfieren al extranjero como se indica a continuación, con el consentimiento que das en la App:

| Destinatario y país | Datos | Finalidad | Cuándo y cómo | Conservación |
| --- | --- | --- | --- | --- |
| OpenAI, Estados Unidos | Fotos, look seleccionado, identificador seudónimo | Generar el retrato | Cada vez que creas un retrato, a través de una red cifrada | Hasta 30 días en registros de supervisión de abusos |
| Google (Firebase y Google Cloud), Estados Unidos | Identificador anónimo, registros de créditos y compras, copia temporal del retrato generado | Alojamiento, libro de créditos, entrega del retrato | Cada vez que usas la App, a través de una red cifrada | Como se indica en la sección 6 |
| RevenueCat, Estados Unidos | Identificador anónimo, registros de compra y suscripción | Analítica de suscripciones | Cada vez que se procesa una compra, renovación o reembolso, a través de una red cifrada | Como se indica en la sección 6 |

Puedes ejercer tus derechos de acceso, rectificación, supresión, suspensión del tratamiento y retirada del consentimiento conforme a la Ley de Protección de la Información Personal de Corea del Sur (개인정보 보호법, PIPA) escribiéndonos a la dirección de la sección 14; puedes negar el consentimiento, pero entonces la App no podrá crear retratos. La persona responsable de la privacidad es {{DEVELOPER_NAME}} ({{SUPPORT_EMAIL}}). También puedes pedir ayuda a la Comisión de Protección de la Información Personal (개인정보보호위원회) o al Centro de Privacidad de KISA (118).

### 8.5 Japón (APPI)

{{DEVELOPER_NAME}} es el operador comercial que maneja la información personal. Usamos la información personal únicamente para las finalidades de la sección 3. Cuando das tu consentimiento en la App, tus fotos y la información relacionada se facilitan a empresas de un país extranjero: OpenAI y Google, en Estados Unidos y en otros países donde operan. Tu identificador anónimo y tus registros de compra también se facilitan a RevenueCat, en Estados Unidos. Estados Unidos no tiene una ley general de protección de la información personal única como la Ley de Protección de la Información Personal de Japón (個人情報の保護に関する法律, APPI); nuestros proveedores tratan los datos conforme a sus propios compromisos y condiciones contractuales descritos en la sección 4 (sin entrenamiento con datos de la API, conservación limitada, cifrado). Puedes solicitar la divulgación, la rectificación, la supresión y el cese del uso de los datos personales conservados, así como un registro de las comunicaciones a terceros, escribiéndonos a la dirección de la sección 14.

### 8.6 Estados Unidos

Según dónde vivas (por ejemplo, California, Colorado, Connecticut, Virginia, Texas, Oregón y otros estados con leyes de privacidad del consumidor), puedes tener derecho a saber qué información personal conservamos, a acceder a ella, a rectificarla, a eliminarla, a recibir una copia portable y a recurrir nuestra decisión. No vendemos información personal, no la compartimos para publicidad dirigida y no la usamos para elaborar perfiles con efectos jurídicos o similares significativos. No tratamos las fotos para identificar de forma única a una persona. Para ejercer estos derechos, usa Eliminar todos mis datos en la App o escribe a {{SUPPORT_EMAIL}}; responderemos en 45 días (podemos ampliar el plazo una vez cuando la ley lo permita) y no te discriminaremos por ejercer tus derechos. Puedes valerte de un representante autorizado; podemos pedirte el ID de soporte para verificar la solicitud. Si denegamos una solicitud, puedes recurrir respondiendo a nuestro correo, y puedes dirigirte al fiscal general de tu estado.

Las solicitudes de California «Shine the Light» y de Nevada pueden enviarse a la misma dirección. No respondemos a las señales «Do Not Track» (No rastrear) porque no te rastreamos.

### 8.7 Otros países

Si la ley de tu país te concede derechos adicionales sobre tus datos personales, los respetaremos en la medida en que nos sean aplicables. Escribe a la dirección de la sección 14.

## 9. Menores

La App no está dirigida a menores y no recogemos a sabiendas información personal de menores de 13 años. No uses la App ni subas fotos de menores de 13 años. Si la ley de tu país fija una edad mínima superior para consentir el tratamiento de datos personales (por ejemplo, 14 años en Corea del Sur, y de 14 a 16 años en varios países europeos), debes tener al menos esa edad, o contar con el consentimiento de uno de tus progenitores o de tu tutor, para usar la App. Si crees que se nos han enviado datos de un menor, escribe a {{SUPPORT_EMAIL}} y los eliminaremos.

## 10. Tratamiento automatizado y datos biométricos

Los retratos los crea un modelo de IA a partir de tu foto y de un look elegido por nosotros. No tomamos ninguna decisión sobre ti con efectos jurídicos o similares significativos y no elaboramos perfiles sobre ti. Las únicas comprobaciones automatizadas son los controles contra el fraude y los abusos (por ejemplo, límites por dispositivo y filtros de seguridad de contenido); si se rechaza una creación, puedes intentarlo de nuevo con otra foto o ponerte en contacto con nosotros.

No usamos identificación biométrica. La detección de caras se ejecuta solo en tu dispositivo para comprobar que hay una cara y contar las caras. No creamos ni guardamos plantillas faciales, no comparamos caras y no usamos las caras para identificar a nadie.

## 11. Fotos de otras personas

Añade solo fotos de personas que hayan dado su consentimiento. Las fotos de otras personas se envían al servicio de IA igual que las tuyas. Eres responsable de contar con su permiso.

## 12. Seguridad

Los datos viajan entre la App, nuestro backend y el servicio de IA mediante conexiones cifradas (HTTPS/TLS). Nuestros proveedores de nube cifran los datos almacenados. La clave de la API de OpenAI se guarda en nuestro servidor y nunca está dentro de la App. Ningún sistema es perfectamente seguro, así que no podemos garantizar una seguridad absoluta. Si una brecha de seguridad afecta a tus datos personales, te lo notificaremos a ti y a las autoridades como exija la ley.

## 13. Cambios y este sitio web

Si modificamos esta política de forma significativa, actualizaremos la fecha de arriba y, si el cambio afecta a lo que se envía al servicio de IA, volveremos a pedirte tu permiso en la App. Si esta política se muestra en tu idioma, la traducción se ofrece a título informativo; si las versiones difieren, prevalece la versión en inglés.

Este sitio web es estático. No instala cookies ni usa analítica ni recursos externos. Está alojado en GitHub Pages, y GitHub puede tratar datos técnicos como tu dirección IP cuando tu navegador carga una página.

## 14. Contacto

{{DEVELOPER_NAME}}
{{SUPPORT_EMAIL}}
{{SITE_URL}}/privacy.html
