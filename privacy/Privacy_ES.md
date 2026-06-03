# AVISO DE PRIVACIDAD
### RelojSolarLunar — Aplicación de Escritorio

> **Notas de redacción (eliminar antes de la publicación).** Versión canónica en español, alineada con (i) la **nueva Ley Federal de Protección de Datos Personales en Posesión de los Particulares (LFPDPPP)** publicada en el DOF el **20 de marzo de 2025**, vigente desde el 21 de marzo de 2025, que abrogó la LFPDPPP de 2010; y (ii) la extinción del **INAI** y la transferencia de sus competencias en materia de protección de datos personales en posesión de los particulares a la **Secretaría Anticorrupción y Buen Gobierno (SABG)**, a través de su **Dirección General de Datos Personales en el Sector Privado**. Los elementos entre corchetes `[ ]` deben confirmarse antes de publicar.

---

**Fecha de entrada en vigor de esta versión:** [FECHA]
**Versión:** v1.0

---

## 1. Identidad del Responsable del Tratamiento

RelojSolarLunar es desarrollada y distribuida por **Carlos Benito Carpintero**, persona física con actividad empresarial, con residencia en la Ciudad de México, México (el "Responsable", "nosotros" o "nuestro").

- Correo electrónico (privacidad y solicitudes del titular): **legal@3doce56.com**
- Domicilio para efectos de derechos ARCO y notificaciones: **[dirección], Alcaldía Benito Juárez, Ciudad de México, C.P. 03020, México**
- Sitio web: **https://3doce56.com**

El nombre comercial **3doce56** se utiliza para identificación comercial; el responsable legal es la persona física antes identificada.

## 2. Datos que Recabamos

Cuando Usted adquiere y activa RelojSolarLunar, recabamos y tratamos los siguientes datos personales:

| Categoría | Datos | Fuente |
|---|---|---|
| Cuenta | Dirección de correo electrónico | Proporcionada por la plataforma de compra (Gumroad o Microsoft Store) |
| Activación | Clave de Activación; Identificador de Instalación (hash SHA-256 no reversible, derivado de la dirección MAC, número de serie del disco del sistema y nombre del equipo, recalculado en cada inicio sin persistencia local) | Generados en el primer arranque en su dispositivo |
| Dispositivo | Sistema operativo; versión de la aplicación | Recabados automáticamente en la activación |
| Ubicación | País (derivado de la dirección IP al momento de la activación) | Recabado automáticamente |
| Uso | Marcas temporales del *heartbeat* (señales periódicas de conectividad enviadas mientras la aplicación está en ejecución) | Recabadas automáticamente durante el uso |
| Transacción | Identificador de la transacción o pedido | Proporcionado por la plataforma de compra |

**No recabamos:** su nombre completo (salvo aquello que pudiera estar contenido en su dirección de correo electrónico), datos de su tarjeta de pago, número telefónico ni ubicación geográfica precisa.

**Nota sobre las plataformas de compra.** Gumroad y Microsoft Store tratan de forma independiente sus datos de pago y compra conforme a sus respectivos avisos de privacidad. Nosotros únicamente recibimos los datos mínimos necesarios para validar su licencia: su dirección de correo electrónico y un identificador de transacción.

**Necesidad de los datos.** Los datos arriba enumerados son **necesarios para la celebración y ejecución del contrato de licencia**. Si Usted no los proporciona — por ejemplo, negándose a activar el Software o bloqueando el tráfico de validación de licencia —, el Software no podrá activarse o, en caso de ya estar activado, operará en modo degradado (sin validación remota ni actualización remota de los datos astronómicos) hasta que la validación pueda reanudarse. El Responsable no recaba dato alguno más allá de lo enumerado en esta Sección.

## 3. Finalidades del Tratamiento

### Finalidades necesarias para la ejecución del contrato

1. **Validación de la licencia** — verificar que su copia se encuentra legítimamente licenciada y prevenir el uso no autorizado.
2. **Prestación del servicio** — proporcionar datos astronómicos en tiempo real (salida y puesta del sol, mediodía solar y fase lunar) para su ciudad activa.
3. **Continuidad de la sesión** — las señales de *heartbeat* permiten detectar instalaciones activas y gestionar el uso permitido por instalación.
4. **Seguridad y antipiratería** — detectar patrones anómalos de activación que indiquen uso compartido o fraudulento de licencias.
5. **Cumplimiento de obligaciones legales** — conservar los registros de aceptación del Aviso de Privacidad conforme lo exija la ley.

### Finalidad secundaria

6. **Estadísticas agregadas.** El Responsable obtiene estadísticas no identificables, anonimizadas y agregadas a partir de sus datos (por ejemplo, distribución por país, cuota por sistema operativo), **previa** eliminación de todo elemento identificador. Una vez anonimizados, los agregados resultantes no constituyen datos personales y no están sujetos a sus derechos individuales.

Si Usted desea **oponerse al tratamiento de sus datos personales con anterioridad a la anonimización** (y, por tanto, a que sus datos sean incluidos como insumo en el proceso de estadísticas agregadas), envíe un correo a **legal@3doce56.com**.

## 4. Bases Jurídicas del Tratamiento

| Finalidad | Base jurídica (México — LFPDPPP) | Base jurídica (UE — RGPD) |
|---|---|---|
| Validación de la licencia | Ejecución del contrato | Art. 6(1)(b) — Ejecución del contrato |
| Prestación del servicio | Ejecución del contrato | Art. 6(1)(b) — Ejecución del contrato |
| Continuidad de la sesión | Ejecución del contrato | Art. 6(1)(b) — Ejecución del contrato |
| Seguridad / antipiratería | Interés legítimo | Art. 6(1)(f) — Interés legítimo |
| Cumplimiento de obligaciones legales | Obligación legal | Art. 6(1)(c) — Obligación legal |
| Estadísticas agregadas | Interés legítimo (datos anonimizados con anterioridad al uso) | Art. 6(1)(f) — Interés legítimo |
| Detección automatizada de clonación de licencia (véase la Sección 11) | Ejecución del contrato | Art. 22(2)(a) — Necesaria para la ejecución de un contrato |

Las referencias a la "LFPDPPP" se entienden hechas a la **Ley Federal de Protección de Datos Personales en Posesión de los Particulares** publicada en el DOF el 20 de marzo de 2025, vigente desde el 21 de marzo de 2025.

## 5. Plazos de Conservación

| Datos | Conservación |
|---|---|
| Registros brutos de activación y *heartbeat* | Ventana móvil de 90 días; los registros anteriores se eliminan automáticamente |
| Estadísticas agregadas, no identificables y anonimizadas | Conservación indefinida (ya no constituyen datos personales) |
| Registro de aceptación del Aviso de Privacidad | Durante la vigencia de la licencia, más el plazo mínimo exigido por la legislación aplicable |
| Respaldos operativos (del lado del desarrollador) | Máximo **24 meses** en rotación; posteriormente se sobrescriben |

## 6. Destinatarios de sus Datos

- **Resend** (Resend Inc., Estados Unidos) — correo electrónico transaccional; se utiliza exclusivamente para enviar mensajes de confirmación de activación. Política de privacidad: `resend.com/legal/privacy-policy`.
- **Proveedor de infraestructura en la nube** — nuestra base de datos backend está alojada en una máquina virtual en la nube. A la fecha de entrada en vigor, el proveedor es **[Oracle Cloud Infrastructure — región México Central (Querétaro)]**.

**Gumroad y Microsoft Store no son destinatarios bajo el presente Aviso.** Son responsables independientes del tratamiento respecto de los datos de compra y pago.

## 7. Transferencias Internacionales de Datos

El Responsable está establecido en México. Esto significa que, **cuando un Usuario ubicado en la Unión Europea, el Espacio Económico Europeo, u otra jurisdicción fuera de México, adquiere o activa el Software**, sus datos personales son transferidos a México para su tratamiento.

### 7.1 Transferencia desde la UE/EEE a México

La Comisión Europea no ha emitido decisión de adecuación respecto de México conforme al artículo 45 del RGPD. La transferencia de sus datos personales desde la UE/EEE al Responsable en México se realiza con base en el siguiente fundamento jurídico:

**Artículo 49(1)(b) del RGPD — Transferencia necesaria para la ejecución de un contrato.** La transferencia es necesaria para la ejecución del contrato de licencia celebrado entre Usted y el Responsable, perfeccionado mediante la compra y activación del Software. Sin la transferencia de los datos mínimos descritos en la Sección 2 al backend del Responsable en México, la licencia no puede validarse y el Software no puede operar.

Al aceptar el presente Aviso y activar el Software, Usted queda informado de esta transferencia y la reconoce.

### 7.2 Transferencia ulterior a Estados Unidos (correo electrónico transaccional)

Su dirección de correo electrónico se transfiere a **Resend** (Resend Inc., Estados Unidos) únicamente para enviarle mensajes de confirmación de activación. Esta transferencia ulterior está protegida por la participación de Resend en el **Marco de Privacidad de Datos UE–EE.UU. (DPF, por sus siglas en inglés)** y/o por **Cláusulas Contractuales Tipo (SCC, por sus siglas en inglés)** aprobadas por la Comisión Europea.

### 7.3 Ubicación de los datos

La infraestructura backend del Responsable se aloja en **[Oracle Cloud Infrastructure — región México Central (Querétaro)]**. Los datos operativos y de validación de licencia residen, por tanto, en México, con la excepción de la transferencia de la dirección de correo electrónico a Resend (Estados Unidos) descrita en el inciso anterior.

## 8. Sus Derechos

Como titular, Usted ostenta los siguientes derechos, conocidos en México como **derechos ARCO** (Acceso, Rectificación, Cancelación, Oposición), complementados con derechos adicionales bajo el RGPD cuando este resulte aplicable:

| Derecho | Descripción |
|---|---|
| Acceso | Obtener confirmación de que tratamos sus datos y recibir copia de los mismos |
| Rectificación | Solicitar la corrección de datos inexactos o incompletos |
| Cancelación / Supresión | Solicitar la supresión de sus datos, sujeto a las obligaciones legales de conservación |
| Oposición | Oponerse al tratamiento basado en interés legítimo o a finalidades a las que no desee someterse |
| Revocación del consentimiento | Cuando el tratamiento se base en consentimiento, revocarlo en cualquier momento sin efecto retroactivo |
| Portabilidad de los datos (RGPD) | Recibir sus datos en formato estructurado, de uso común y lectura mecánica |
| Limitación (RGPD) | Solicitar la limitación del tratamiento en determinadas circunstancias |

**Forma de ejercicio de los derechos.** Envíe su solicitud a **legal@3doce56.com** incluyendo: (i) su nombre y un medio de contacto; (ii) documentación que acredite razonablemente su identidad (o, tratándose de un representante, su identidad y la representación con la que actúa); (iii) descripción clara y precisa de los datos a los que se refiere y del derecho que ejerce; (iv) cualquier otro elemento que facilite la localización de sus datos (por ejemplo, su Identificador de Instalación o el correo electrónico utilizado en la compra). Las solicitudes relativas a sus datos personales se aceptan y atienden en **cualquier idioma**; la limitación general al inglés y al español para el soporte y las comunicaciones comerciales no aplica al ejercicio de estos derechos.

**Plazo de respuesta.** Responderemos dentro de los **veinte (20) días hábiles** siguientes a la recepción de una solicitud completa, conforme a la LFPDPPP. En caso de procedencia, daremos efectividad a la solicitud en los **quince (15) días hábiles** adicionales. Si la solicitud está incompleta, se lo notificaremos dentro de los cinco (5) días hábiles siguientes para que la complete dentro de los diez (10) días hábiles posteriores. Cuando concurran circunstancias justificadas, el plazo de respuesta podrá ampliarse por una sola vez en los términos que la LFPDPPP permita, previa notificación a Usted.

**Supresión y anonimización.** Cuando la legislación aplicable nos obligue a conservar ciertos registros, **anonimizaremos** los datos en lugar de eliminarlos — reemplazando los identificadores personales por valores criptográficos irreversibles — de modo que el registro técnico persista sin seguir constituyendo dato personal.

**Recurso.** Si Usted considera que nuestra respuesta resulta inadecuada o que hemos tratado sus datos de forma ilícita, podrá presentar reclamación ante la autoridad de control indicada en la Sección 14.

## 9. Almacenamiento Local en su Dispositivo

RelojSolarLunar almacena datos localmente en su dispositivo, en una base de datos SQLite y en un archivo de configuración, que contienen: los datos astronómicos de su ciudad activa (ventana móvil de 8 días), su ciudad seleccionada y sus preferencias de visualización, y el estado de su instalación.

Estos datos permanecen en su dispositivo y bajo su control. Usted puede eliminarlos en cualquier momento desinstalando la aplicación. El almacenamiento local no incluye *cookies* de rastreo ni identificadores publicitarios.

## 10. Medidas de Seguridad

El Responsable ha adoptado **medidas administrativas, técnicas y físicas de seguridad** razonables atendiendo a la naturaleza y al volumen de los datos tratados, incluyendo: cifrado en tránsito (TLS) para todas las comunicaciones entre la aplicación y el backend; acceso restringido a los sistemas backend con base en autenticación y en el principio de mínimo privilegio; registros operativos que no incluyen datos personales innecesarios; y revisión periódica del estado de seguridad.

Ninguna medida de seguridad puede garantizar protección absoluta frente a todos los riesgos. El Responsable responderá ante cualquier incidente de seguridad de los datos conforme a la legislación aplicable y notificará a los titulares afectados cuando así proceda.

## 11. Decisiones Automatizadas

El sistema de validación de licencias opera **detección automatizada de clonación o uso fraudulento de una clave de licencia** en múltiples dispositivos. Cuando se detecta tal uso fraudulento, el sistema podrá revocar los Identificadores de Instalación afectados y, en una segunda detección que afecte al mismo Usuario, **terminar automáticamente la licencia** conforme a la Sección 8.1 del Contrato de Licencia de Usuario Final.

**Lógica de la decisión.** La detección se basa en señales objetivas del Servicio de Validación de Licencias: en particular, el uso simultáneo de una misma clave de licencia por Identificadores de Instalación que el sistema identifica como dispositivos distintos, en un patrón incompatible con el derecho a dos Espacios de Instalación otorgado por la licencia.

**Trascendencia y consecuencias.** La primera detección da lugar a la revocación de los Identificadores de Instalación afectados y a la emisión de una nueva clave de licencia como remediación por única vez; el derecho subyacente del Usuario se preserva. Una detección posterior da lugar a la terminación definitiva de la licencia.

**Base jurídica.** La decisión automatizada es necesaria para la ejecución del contrato de licencia celebrado entre el Usuario y el Responsable (artículo 22(2)(a) del RGPD).

**Sus salvaguardas.** Usted tiene derecho a: (i) **obtener intervención humana** por parte del Responsable respecto de la decisión; (ii) **expresar su punto de vista** sobre la detección; y (iii) **impugnar la decisión**. Para ejercer estos derechos, envíe un correo a **legal@3doce56.com** dentro de los **treinta (30) días naturales** siguientes a la fecha en que se le hubiera notificado la decisión. El Responsable revisará el caso de manera sustantiva y responderá dentro de los veinte (20) días hábiles siguientes a la recepción de su solicitud.

## 12. Menores

RelojSolarLunar está destinada al uso por **personas adultas (mayores de 18 años)**. La naturaleza y el volumen de los datos personales descritos en la Sección 2 son mínimos y no permiten identificar a menores. El Responsable **no** verifica la edad de los Usuarios al momento de la compra o activación y **no** recaba conscientemente datos personales de menores.

Si un padre o tutor legal considera que un menor ha activado la aplicación, le rogamos contactar a **legal@3doce56.com**. Tras la verificación correspondiente, suprimiremos los datos asociados y, en la medida de lo posible, la instalación correspondiente será desactivada.

## 13. Cambios al Presente Aviso

El Responsable podrá actualizar el presente Aviso de Privacidad periódicamente. El número de versión y la fecha de entrada en vigor se actualizarán con cada cambio.

- **Cambios sustanciales** (modificaciones que afecten las categorías de datos recabados, las finalidades del tratamiento, los destinatarios o sus derechos) se notificarán a los Usuarios existentes **dentro de la aplicación al siguiente inicio y/o por correo electrónico**, y surtirán efecto en la fecha de entrada en vigor indicada.
- **Cambios no sustanciales** (aclaraciones, correcciones, referencias a autoridades legales, datos de contacto) se publicarán en el sitio web sin notificación individual.

Los nuevos Usuarios siempre aceptan la versión vigente al momento de la activación. El Responsable mantiene internamente un registro de versiones, disponible a solicitud.

## 14. Autoridad de Control

- **México (LFPDPPP):** **Secretaría Anticorrupción y Buen Gobierno**, **Dirección General de Datos Personales en el Sector Privado** — sucesora del INAI en materia de protección de datos personales en posesión de los particulares, conforme a la reforma constitucional del 20 de diciembre de 2024 y a la nueva LFPDPPP del 20 de marzo de 2025. Portal del Gobierno federal: **gob.mx**.
- **Unión Europea / EEE:** la autoridad de protección de datos del país de residencia del titular.

## 15. Legislación Aplicable y Jurisdicción

El presente Aviso se rige por las leyes de México, específicamente por la LFPDPPP (DOF 20/03/2025) y, cuando resulte aplicable, por el RGPD de la Unión Europea. Las controversias no sujetas a la jurisdicción imperativa de protección al consumidor o de protección de datos serán resueltas por los tribunales competentes de la Ciudad de México.

## 16. Fecha de Entrada en Vigor

El presente Aviso de Privacidad entra en vigor el **[FECHA]**, versión **1.0**.

---

## Contacto

**Carlos Benito Carpintero** (nombre comercial **3doce56**)
Legal: **legal@3doce56.com** · **3doce56.com**
