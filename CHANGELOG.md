# Changelog

Los cambios de cada versión de Kioskeo, tal como aparecen en "Novedades" dentro de la app. La fecha es la del día en que se armó la versión; las que no tienen fecha salieron entre abril y julio de 2026.

---

## [1.14.46] - 2026-10-03

- **El anuncio ya no se mueve:** El lugar del anuncio de abajo queda reservado desde que abrís la pantalla: ya no aparece de golpe justo donde ibas a tocar.

## [1.14.45] - 2026-09-25

- **Todo Kioskeo, gratis:** Ventas y clientes sin límite, cuenta corriente, cierres en PDF, empleados con PIN y respaldos automáticos: ahora todo es gratis para todos.
- **PRO ahora es sin publicidad:** Para mantener Kioskeo gratis sumamos un anuncio chico abajo, nunca en la pantalla de venta. Si tenés PRO, no ves ninguno.
- **Precios completos en el acceso rápido:** Los botones de productos en la pantalla de venta ya no cortan los precios largos: el importe entra siempre entero, en una sola línea.

## [1.14.44] - 2026-08-03

- **Listos para Android 16:** Kioskeo ya está preparada para la última versión de Android, así que sigue funcionando igual de bien en los equipos nuevos.

## [1.14.43] - 2026-07-22

- **Compras más seguras y al día:** Actualizamos el sistema de compras de Google Play a la última versión. No cambia nada de lo que ves, pero las suscripciones PRO quedan más seguras y al día con los requisitos de Google.

## [1.14.42] - 2026-07-22

- **Fotos: detección real de cambios:** Al reimportar un producto con la misma foto, ya no aparece como «Foto actualizada». Comparamos bytes contra la foto guardada — si es idéntica, no se toca.
- **Ayuda en la pantalla de importar:** Nuevo ícono ⓘ en la barra de Importar que explica los cuatro formatos (CSV, Excel, PDF, .kprod), cuándo conviene cada uno y cómo evita duplicados.

## [1.14.41]

- **Un solo botón de importación:** Antes había dos: uno arriba para CSV/Excel/PDF y otro en el menú para .kprod. Ahora es uno solo — la app se da cuenta sola del tipo de archivo que estás abriendo.
- **Resumen al terminar de importar:** Después de importar te mostramos un resumen: cuántos productos son nuevos, a cuántos se les actualizó el precio, a cuántos la foto, otros cambios y cuántos quedaron igual.

## [1.14.40]

- **Importar .kprod desde el menú: arreglado:** El selector de archivos no dejaba elegir el .kprod (lo mostraba en gris). Ahora se puede seleccionar normalmente. Si elegís un archivo que no sea .kprod, te avisamos.

## [1.14.37]

- **Ayuda en cada opción de Productos:** Las opciones del menú de tres puntos en Productos ahora tienen un ícono ⓘ al costado. Tocalo para ver una explicación corta de para qué sirve cada cosa, con un ejemplo. Pensado para quien recién arranca con Kioskeo.
- **Recomendá Kioskeo en un toque:** Nueva tarjeta destacada en Ajustes para compartir el link de descarga con otros kiosqueros por WhatsApp, Drive o Gmail. Antes estaba escondido dentro de «Acerca de».

## [1.14.36]

- **Importar .kprod desde el menú de Productos:** Si te compartieron un archivo .kprod podés importarlo directamente desde Productos → menú de tres puntos → «Importar productos compartidos». Queda separado del importador general (CSV/Excel/PDF) para que no se confundan.

## [1.14.35]

- **Compartir productos entre kioscos:** Desde Ajustes → Datos o el menú de Productos (también en selección múltiple) podés enviar tu catálogo (con fotos en miniatura) a otra sucursal o kiosquero por WhatsApp, Drive o Gmail.
- **Abrir productos con un toque:** Recibís un archivo .kprod por WhatsApp/Drive/Gmail y al tocarlo se abre Kioskeo y te pregunta si querés importarlo. Productos con el mismo código de barras (o el mismo nombre si no tienen código) se actualizan en vez de duplicarse.

## [1.14.33]

- **Botón para limpiar búsqueda en Productos:** En la pantalla de Productos, cuando escribís algo en el buscador ahora aparece un botón con una «X» para limpiar el filtro de una. Antes tenías que borrar letra por letra.

## [1.14.30]

- **Reintentar suscripción ya no falla:** Si cancelaste una suscripción y querés volver a suscribirte, antes podía aparecer un error «producto no encontrado». Ahora la app refresca los planes contra Google Play justo antes de cobrar y la compra se concreta sin problemas.

## [1.14.29]

- **Botón de suscribirse no se queda colgado:** Si tocás un plan y cerrás la pantalla de Google Play sin pagar, el botón vuelve a estar disponible enseguida en lugar de quedarse pensando. Además, ahora solo gira el botón del plan que tocaste, no los dos a la vez.

## [1.14.27] - 2026-05-08

- **Cupones promocionales se activan con un toque:** Si canjeaste un código promocional de Kioskeo PRO en Google Play, ahora la app detecta el cupón y te muestra una tarjeta verde arriba con un botón directo para activar tu prueba gratuita extendida.

## [1.14.26] - 2026-05-08

- **Códigos promocionales y restaurar compra funcionan bien:** Si canjeás un código promocional de Google Play o tocás «Restaurar compra», ahora la app espera lo necesario para que Play confirme. Antes podía quedarse pensando o no activar PRO. Si no encuentra suscripción, te avisa con un mensaje claro.

## [1.14.25] - 2026-04-26

- **Adjuntar foto al producto ya no te saca la sesión:** Antes, abrir la cámara o la galería para agregarle foto a un producto disparaba el bloqueo automático y te mandaba al login al guardar. Ahora el bloqueo solo se activa si realmente estuviste afuera el tiempo configurado.

## [1.14.24] - 2026-04-22

- **Cumplimiento de política de fotos de Google Play:** Kioskeo dejó de declarar el permiso READ_MEDIA_IMAGES. Ahora usa el selector de fotos de Android cuando le agregás una imagen a un producto — menos permisos, misma comodidad.

## [1.14.23] - 2026-04-21

- **Catálogo argentino con 716 productos:** Si tu moneda es pesos argentinos, ahora podés arrancar con un catálogo de 716 productos reales de kiosco con código de barras. Está disponible tanto en el onboarding como en Ajustes → Datos → Cargar catálogo argentino. Los precios son de referencia — ajustalos antes de cobrar.

## [1.14.22]

- **PIN del dueño respeta la barra de navegación:** La hoja para ingresar el PIN ya no queda tapada por la barra del sistema. El botón «Cancelar» siempre se ve entero.
- **Borrado masivo respeta el historial de ventas:** Eliminar varios productos ya no falla si alguno tiene ventas asociadas. Los que tienen historial quedan intactos y el resto se borra. Te avisamos cuántos se saltaron.

## [1.14.20]

- **Buscar producto con lista completa:** Al tocar el buscador durante el cobro ahora ves el catálogo completo en orden alfabético con barra lateral A-Z para saltar a cualquier letra. Ideal cuando no te acordás el nombre exacto.
- **Productos más compactos + eliminación múltiple:** La solapa Productos ahora usa la misma lista alfabética con barra A-Z. Mantené apretado un producto para entrar en modo selección y borrar varios a la vez.
- **Auto-recuperación de base corrupta:** Si la app detecta que la base de datos quedó inconsistente (por ejemplo tras una restauración de copia de seguridad de Android) ahora se regenera sola al abrir, en vez de trabarse en un error.

## [1.14.19] - 2026-04-21

- **PRO respeta el período pagado:** Si cancelás la suscripción en Play, Kioskeo ahora mantiene las funciones PRO hasta que termine el período que ya pagaste. Antes te sacaba el acceso apenas cancelabas.

## [1.14.18] - 2026-04-21

- **Avatar del dueño en todos lados:** El menú «Más» y el selector de cambio de usuario ahora muestran tu emoji y color de avatar, en lugar de la inicial del nombre.
- **Backup incluye ajustes:** Los respaldos ahora guardan nombre del negocio, dirección, moneda, idioma, tema y avatar del dueño. Al restaurar en otro equipo recuperás toda la config.

## [1.14.17] - 2026-04-21

- **Avatars personalizados:** Elegí emoji y color para cada empleado y para tu tarjeta de dueño. Editás desde Empleados → tocá el avatar o desde Ajustes → Mi negocio → Tu avatar.

## [1.14.16] - 2026-04-21

- **Snackbar de update legible en oscuro:** El cartel de «Reiniciar» ahora usa los colores del tema: en modo oscuro el texto se ve claro sobre fondo oscuro en vez de blanco sobre crema.

## [1.14.15] - 2026-04-21

- **Tema claro por defecto:** Las instalaciones nuevas arrancan en modo claro sin seguir el tema del sistema. Podés cambiarlo cuando quieras desde Ajustes → Apariencia → Tema.

## [1.14.14] - 2026-04-21

- **Updates in-app alineado con Tita:** Reescribimos el chequeo de actualizaciones copiando la lógica probada de Tita: delay de 2 s para que Play Services esté listo, fallback a update inmediato cuando Play lo exige y snackbar de reinicio al finalizar.

## [1.14.13] - 2026-04-21

- **Restaurar respaldo desde el onboarding:** Cambiaste de teléfono? Al abrir Kioskeo por primera vez te preguntamos si querés restaurar un respaldo antes de configurar nada. Importás el archivo .kioskeo y seguís donde habías dejado.

## [1.14.12] - 2026-04-21

- **Aviso de updates arreglado:** El chequeo de actualizaciones ya no se marcaba como «descartado» antes de que aceptaras. Ahora cada update nueva te avisa hasta que pulses Reiniciar.

## [1.14.10] - 2026-04-21

- **Ajustes con colores por categoría:** Cada sección de Ajustes ahora tiene su propio color: teal para Mi negocio, azul para Región, rosa para Apariencia, violeta para Datos y naranja para Seguridad. Diferenciación sutil sin recargar.

## [1.14.9] - 2026-04-21

- **Ajustes más claros:** Reorganizamos la pantalla Ajustes: ahora cada sección (Mi negocio, Región, Apariencia) tiene su color distintivo y la tarjeta de Kioskeo PRO salta a la vista con un gradiente destacado.

## [1.14.8] - 2026-04-20

- **Pantalla PRO más llamativa:** El plan anual ahora se destaca con ribbon «Mejor opción», gradiente animado y precio en grande. Sumamos aclaración sobre los 7 días gratis para que no haya sorpresas.
- **Cancelación detectada sola:** Si cancelás la suscripción en Play, Kioskeo lo detecta automáticamente al volver a la app y saca el acceso PRO sin que tengas que hacer nada.

## [1.14.7] - 2026-04-20

- **Trial siempre visible:** La pantalla PRO ahora promociona los 7 días gratis de entrada, sin depender de que Google marque tu cuenta como elegible. Sacamos además el bloque de respaldos del tope para que quede más limpio.

## [1.14.6] - 2026-04-20

- **7 días gratis bien promovidos:** La pantalla PRO ahora muestra un banner de prueba gratis arriba y la tarjeta mensual arranca con los 7 días sin cargo, con texto claro de cómo cancelar antes de empezar a pagar.

## [1.14.5] - 2026-04-20

- **Planes PRO corregidos:** Ahora la prueba de 7 días, el plan mensual y el anual facturan lo correcto: la prueba es gratis los primeros 7 días y después pasa a mensual, el mensual cobra el mes y el anual cobra el año.

## [1.14.3]

- **Caja que se abre sola:** La caja ahora abre automáticamente con la primera venta del día. En la pestaña Cajas te explicamos cómo funciona por si querés cargar un efectivo inicial manualmente.

## [1.14.2]

- **Productos al alcance:** Mientras no tengas favoritos ni ventas históricas, la grilla del POS muestra tu catálogo en orden alfabético para que arranques a vender sin buscar.

## [1.14.1]

- **Tutorial más claro:** Ajustamos la guía para que el paso de sumar producto avance al toque y renombramos el botón de saltar para que se entienda que es todo el tutorial.

## [1.14.0]

- **Onboarding renovado:** Redujimos el alta inicial de 11 a 4 pasos. Ahora arrancás vendiendo en menos de un minuto.
- **Catálogo de ejemplo por región:** Podés cargar 15 productos típicos de tu mercado con precios sugeridos y modificarlos cuando quieras.
- **Tutorial de primera venta:** Si recién empezás, Kioskeo te guía paso a paso con tu primera venta real.

## [1.13.0]

- **Português do Brasil:** Kioskeo ahora habla portugués. Elegí tu idioma desde Ajustes → Idioma o cambiá la bandera 🇧🇷 desde el selector.
- **Bienvenido Brasil:** Nuevo mercado disponible. La app se adapta a términos locales (PIX, fiado, PDV) para que tus clientes BR se sientan en casa.
- **Inglés y portugués completos:** Traducimos toda la app: ajustes, caja, reportes, historial, avisos y mensajes de error. Cero textos sueltos en español para los idiomas nuevos.

## [1.12.7]

- **ARS por defecto (de verdad):** Migración que pisa la moneda guardada por autodetección vieja. Si ya habías elegido otra moneda a mano, se respeta.

## [1.12.6]

- **ARS por defecto:** Kioskeo arranca con pesos argentinos. Cambialo desde el onboarding o Ajustes si usás otra moneda.

## [1.12.5]

- **Onboarding con botón atrás:** Podés volver a pantallas anteriores sin que la app se cierre. Respeta los pasos que saltaste.
- **Bandera argentina en idioma:** El selector de idioma muestra 🇦🇷 para Español, más claro para el uso local.

## [1.12.4]

- **Restauración ahora reinicia bien:** Encontramos la causa real del error "malformed database schema": el reinicio post-restore no mataba el proceso viejo. Ahora sí. No se va a repetir.
- **Onboarding visible de nuevo:** Si ya habías pasado el onboarding viejo, te mostramos el nuevo una vez para que veas todo lo que agregamos.

## [1.12.3]

- **Restauración blindada:** Antes de reemplazar tus datos, validamos que el respaldo no esté dañado. Si el .kbk tiene errores, lo cancelamos y no perdés lo que tenías.
- **Onboarding completo:** Nuevas pantallas explicando cómo cargar productos, manejar caja, usar registros, elegir tema y qué incluye PRO vs la versión gratis.

## [1.12.2]

- **Elegí idioma y moneda al empezar:** Nueva pantalla en el onboarding para elegir idioma y moneda apenas abrís la app. Evita arrancar con USD por default.
- **Textos actualizados: 10 respaldos:** Corregimos los textos de Ajustes, PRO y onboarding que todavía decían "5 respaldos". Ahora coinciden con el límite real de 10.

## [1.12.1]

- **WhatsApp abre .kbk con Kioskeo:** Agregamos filtros para WhatsApp, Gmail y Drive que mandan el archivo como binario. Ahora aparecemos en el selector de apps.

## [1.12.0]

- **Abrir .kbk desde cualquier lado:** Ahora Android ofrece Kioskeo como opción al tocar un archivo .kbk (WhatsApp, Gmail, Drive). Confirmás y se restaura.
- **Registro de actividad explicado:** Agregamos un cartel arriba de Registro de actividad explicando qué guarda y por qué puede estar vacío.
- **Onboarding actualizado:** Nueva pantalla de respaldos en la bienvenida + mención del registro de actividad en la guía de cierre.

## [1.11.7]

- **Selector de idioma mejorado:** Ahora el selector de idioma usa el mismo estilo del selector de moneda: bottom sheet con banderas y marca de selección.

## [1.11.6]

- **Cambiar usuario siempre visible:** Empleados ahora también ven "Cambiar usuario" en el menú "Más" sin tener que cerrar la app.

## [1.11.5]

- **Login no queda pegado tras restaurar:** Si seguridad estaba desactivada pero el PIN seguía en base, el login aparecía igual al restaurar. Ahora el lock respeta el flag de seguridad activa.

## [1.11.4]

- **Restaurar sin respaldo extra:** Al restaurar ya no se crea un respaldo "pre-restauración" que llenaba la lista. La restauración es directa.

## [1.11.3]

- **Más respaldos guardados:** Ahora guardamos los últimos 10 respaldos automáticos (antes 5) para que tengas más margen para volver atrás.

## [1.11.2]

- **Restaurar respaldos viejos, arreglado:** Si intentabas restaurar el respaldo más antiguo, a veces salía "Selected file not found". La rotación borraba tu archivo antes de leerlo. Ahora lo copiamos aparte antes de rotar.

## [1.11.1]

- **Fechas de respaldos correctas:** Arreglamos un caso donde la fecha del respaldo aparecía como "1 ene 1970". Ahora la leemos del nombre del archivo.
- **Fin del solapado con la barra de navegación:** Agregamos margen inferior en Seguridad y Respaldos automáticos para que el contenido no quede tapado por los gestos de Android.

## [1.11.0]

- **PIN de dueño al crear empleado:** Cuando creás el primer empleado y no tenés PIN de dueño, la app te lo pide automáticamente para que la pantalla de login funcione.
- **Cambiar usuario rápido:** Nuevo atajo "Cambiar usuario" en el menú "Más" para alternar entre dueño y empleados sin minimizar la app.

## [1.10.3]

- **Seguridad explicada:** Agregamos un cartel arriba de la pantalla de Seguridad explicando cómo funciona cada opción, qué protege y qué conviene activar.
- **Sin duplicados:** Sacamos Empleados y Registro de actividad de Seguridad (ya viven en "Mi negocio").

## [1.10.2]

- **Fix: opciones destacadas no aparecían:** Corrigió un bug de layout que hacía desaparecer el contenido de los grupos destacados en Ajustes.

## [1.10.1]

- **Destacado más prolijo:** Cambiamos el estilo de los grupos destacados en Ajustes: ahora usan una barra lateral violeta en vez de un fondo tintado.

## [1.10.0]

- **Ajustes más claros:** Reorganizamos Ajustes: Empleados y Registro de actividad ahora están en "Mi negocio". Datos y Seguridad se destacan visualmente por su importancia.
- **Ajustes destacado en Más:** En el menú "Más" ahora Ajustes aparece separado de las funcionalidades, con un estilo distinto para encontrarlo rápido.

## [1.9.7]

- **Lista de respaldos prolija:** Arreglamos el layout de los chips en la lista de respaldos (se rompía cuando el nombre del archivo era largo).

## [1.9.6]

- **Respaldos más claros:** Ahora verás chips indicando cuál es el respaldo más reciente y cuáles son copias de pre-restauración (los que se crean automáticamente antes de restaurar).

## [1.9.5]

- **Fotos de productos en favoritos:** Arreglamos un bug que hacía que las fotos de los productos no aparezcan en el acceso rápido del POS.

## [1.9.4]

- **Backups siempre al día:** La base de datos ahora sincroniza sus escrituras con el disco cada ~40KB y al pausar la app. Los respaldos nunca más quedan incompletos.
- **Borrar todos los respaldos:** Nuevo botón para limpiar todos los backups de una sola vez y arrancar desde cero.

## [1.9.3]

- **Respaldar ahora:** Nuevo botón para forzar un respaldo en el momento, sin esperar las 24 horas del auto backup.
- **Respaldo de seguridad al restaurar:** Antes de restaurar un respaldo guardamos una copia del estado actual. Si te arrepentís, podés volver atrás.
- **Aviso claro al restaurar:** Al restaurar te mostramos exactamente qué fecha traés y qué se perdería, para que no haya sorpresas.

## [1.9.2]

- **Restore a prueba de balas:** Corregimos un crash que aparecía al restaurar respaldos viejos ("duplicate column"). Ahora tolera cualquier backup, sin importar de qué versión venga.
- **Backups consistentes:** Antes de guardar un respaldo hacemos checkpoint del WAL. Así el archivo queda 100% sincronizado con el estado real de la app.

## [1.9.1]

- **Restaurar backups ahora funciona:** Al restaurar un respaldo la app se reinicia sola para que quede exactamente como ese día. Sin más "reinicia manual" ni datos mezclados.
- **Snapshot 100% limpio:** Corregimos un detalle técnico (WAL leftover) que podía dejar productos o clientes nuevos después de restaurar. Ahora el respaldo pisa todo como corresponde.

## [1.9.0] - 2026-04-18

- **English support:** Kioskeo ahora habla inglés. Cambiá el idioma desde Ajustes → Región → Idioma.
- **Elegí tu moneda:** Seleccioná tu moneda local con bandera y código ISO. ARS, USD, EUR, CLP, PEN, UYU, COP y más.
- **Formato localizado:** Los precios se muestran con el separador y símbolo correcto para tu moneda e idioma.
- **Detección automática:** Al abrir la app por primera vez detectamos tu región y proponemos la moneda local.

## [1.8.0] - 2026-04-18

- **Ajuste masivo de precios:** Subí o bajá precios por porcentaje, monto o redondeo. Aplicá a todo el catálogo, una categoría o productos elegidos (ej. solo Coca-Cola).
- **Preview antes de aplicar:** Ves precio viejo → nuevo por producto y la diferencia total antes de confirmar. Bloquea si algún producto quedaría en $0.
- **Historial + revertir:** Cada ajuste queda guardado con snapshot por producto. Podés revertir desde el historial si te arrepentís.
- **Solo el dueño:** El ajuste masivo está disponible solo para el dueño. Los empleados no ven la opción.

## [1.7.3] - 2026-04-17

- **Color por empleado:** Asigná un color a cada empleado. Se aplica en la tarjeta de login y en la barra del POS.

## [1.7.2]

- **Beep + vibración al tocar producto:** Confirmación sonora y táctil cada vez que agregás un producto al carrito.
- **Back vuelve al POS:** Con el buscador abierto, el botón atrás cierra el buscador en vez de salir de la app.

## [1.7.1]

- **Acceso rápido más prolijo:** POS muestra 10 productos de acceso rápido. Al tocar el buscador se expande a 30.

## [1.7.0]

- **Máximo 10 favoritos:** Los favoritos ahora tienen tope de 10 para que sigan siendo de acceso rápido.

## [1.6.9]

- **Favoritos sin tapones:** El botón QR ya no tapa el último favorito. Espacio reservado al pie de la grilla.

## [1.6.8]

- **Beep más confiable:** El sonido del scanner ahora suena desde el primer código. Modo baja latencia + precarga.

## [1.6.7] - 2026-04-17

- **Seguridad con PIN + huella:** Protegé acciones sensibles (anular venta, cerrar caja, backup) con PIN del dueño o biometría.
- **Empleados con permisos (PRO):** Usuarios con PIN propio, roles Cajero/Encargado o permisos a medida. Cada uno ve solo las solapas que puede usar.
- **Auto-bloqueo por inactividad:** La app se bloquea sola después del tiempo que elijas (30s, 1min, 5min, 30min o nunca).
- **Pantalla de bloqueo con marca:** Ahora muestra el logo de Kioskeo y el nombre de tu kiosco cuando la app se bloquea.
- **Registros por empleado:** Solapa visible solo para el dueño: facturación, ventas, tiempo activo y acciones de cada empleado.
- **Sesiones auto-tracked:** Cada login, bloqueo y cambio de usuario queda registrado con duración automática.
- **Auditoría de acciones:** Cada acción sensible queda registrada: quién la hizo, cuándo y con qué permiso.
- **Barra de navegación ordenada:** Hasta 3 solapas principales + "Más" con el resto, sin superposiciones.
- **Beep al escanear:** Sonido clásico tipo caja de supermercado cada vez que leés un código.
- **Onboarding ampliado:** Nueva guía inicial con PIN, empleados, registros y tips del scanner.
- **Novedades en cada versión:** Después de cada actualización vas a ver un resumen de lo que cambió.

## [1.6.4]

- **Novedades en cada versión:** Después de cada actualización vas a ver un resumen de lo que cambió.
- **Onboarding ampliado:** Nueva guía inicial con seguimiento por empleado y tips del scanner.

## [1.6.3]

- **Beep al escanear:** Sonido clásico tipo caja de supermercado cada vez que leés un código.

## [1.6.1]

- **Barra de navegación ordenada:** Hasta 3 solapas principales + "Más" con el resto, sin superposiciones.

## [1.6.0]

- **Registros por empleado:** Nueva solapa visible solo para el dueño: facturación, ventas, tiempo activo y acciones de cada empleado.
- **Sesiones auto-tracked:** Cada login, bloqueo y cambio de usuario queda registrado con duración automática.

## [1.5.2]

- **Solapas por permisos:** El empleado ahora solo ve las solapas donde tiene permiso (ej. un cajero no ve Caja ni Ajustes).

## [1.5.0]

- **Seguridad con PIN + huella:** Protegé acciones sensibles (anular venta, cerrar caja, backup) con PIN del dueño o biometría.
- **Empleados con permisos (PRO):** Creá usuarios con PIN propio y permisos a medida. Cajero, Encargado o totalmente personalizado.
- **Auto-bloqueo:** La app se bloquea sola después del tiempo que elijas (30s, 1min, 5min, 30min o nunca).
- **Registro de actividad:** Cada acción sensible queda auditada: quién la hizo, cuándo y con qué permiso.
