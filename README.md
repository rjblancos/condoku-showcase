# Condoku · Administración de condominios

> Cuotas, cobranza, contabilidad de partida doble, portería con código QR y
> soporte técnico, en un solo sistema pensado para el teléfono. Para
> Hispanoamérica, empezando por Venezuela — y listo para adaptarse a otros
> países sin inconvenientes.

**Estado:** en construcción activa, disponible para demostración guiada ·
**Sistema propietario** de Kusarive Solutions LLC ·
[English version](README.en.md) ·
[Página de presentación](https://rjblancos.github.io/condoku-showcase/) ·
**[Descargar la presentación en PDF](presentacion/Condoku-presentacion.pdf)** (18 diapositivas)

---

![Pagos](capturas/pagos.jpg)

*El administrador aprueba o anula un pago en segundos. Ensayo con datos
inventados.*

## Qué resuelve

Administrar un condominio hoy es un rompecabezas: hojas de cálculo que solo
entiende quien las hizo, comprobantes de pago que se pierden en un chat de
WhatsApp, una tasa del dólar que cambia todos los días y nadie anota, y un
cuaderno de portería que nadie puede consultar desde su casa. El resultado son
propietarios que no saben cuánto deben y una junta que no confía en unas
cuentas que solo el administrador puede revisar.

Condoku reúne cobranza, contabilidad, comunicación y portería en una sola
plataforma: cada acción queda registrada, cada cifra se puede auditar, y cada
persona ve exactamente lo que le corresponde.

## Qué hace

- **Cobranza con comprobante o en línea.** El propietario sube su comprobante
  (efectivo, transferencia, Pago Móvil o una transferencia en dólares) y el administrador lo aprueba
  con un clic. El pago se aplica automáticamente a los recibos más antiguos
  con saldo (FIFO), el saldo se actualiza solo, y hay un aviso en cada paso.
- **Contabilidad de partida doble real.** Libro diario, mayor y balance de
  comprobación, con un asiento contable detrás de cada pago, gasto y recibo —
  nunca una hoja de cálculo disfrazada. Un asiento ya aprobado se corrige con
  un asiento de reverso, nunca editando el original: el historial queda
  completo. Los gastos (nómina, servicios, mantenimiento) se registran en
  borrador y se aprueban antes de afectar la cuota de nadie.
- **Dólares y bolívares en cada recibo.** La tasa del día queda guardada en el
  instante de cada movimiento, así que un recibo de hace meses sigue siendo
  exacto, sin recalcular nada. El mismo mecanismo se adapta a la moneda y la
  fuente oficial de cada país.
- **Portería con código QR.** Un pase de visita se genera desde el teléfono
  del propietario y se valida en portería escaneando el código o tecleando un
  código corto de respaldo; queda registrada la entrada y la salida, con una
  ventana de tiempo válida. Si llega alguien sin pase, el residente recibe un
  aviso para aprobar o rechazar la visita.
- **Reclamos y novedades con seguimiento.** Tickets con categoría, prioridad y
  estado para que un residente reporte un problema y lo siga hasta resuelto, y
  un libro de novedades para conserjería y vigilancia, con aviso automático
  cuando la severidad es alta.
- **Documentos y comunicados con visibilidad jerárquica.** Reglamento, actas
  de asamblea, balances y avisos del condominio en un solo lugar, cada uno
  visible solo para administración, junta, propietarios o todos los
  residentes según corresponda — nunca un documento de la junta visible para
  cualquiera por error. Un comunicado nuevo notifica a quien puede verlo, sin
  que nadie tenga que entrar a revisar si hay algo nuevo.
- **Torres, unidades y residentes siempre al día.** Apartamentos, locales y
  estacionamientos por torre, con alícuota calculada proporcional al área —
  nunca 1/N. Un inquilino que se mudó deja de aparecer solo; mientras dure el
  alquiler, es el inquilino quien ve el estado de cuenta y paga.
- **Una cartera de condominios, una sola cuenta.** Una administradora con
  varios condominios da de alta a su equipo desde un solo lugar y cambia de
  condominio sin cerrar sesión. Los roles que manejan dinero o datos de varios
  condominios exigen una segunda clave de un solo uso.
- **Soporte técnico con compromiso de tiempo.** Cuatro niveles de severidad,
  desde una hora de primera respuesta para lo más urgente hasta 24 horas para
  lo que puede esperar, con el reloj pausado mientras se espera información
  del cliente — nunca «en algún momento».
- **Un rol para cada persona.** Administrador, contador, junta, propietario,
  inquilino, conserje, vigilante y más: cada uno entra con su cuenta y ve solo
  los datos de su condominio.

## Capturas

| Cobranza | Estado de cuenta |
|---|---|
| ![Pagos](capturas/pagos.jpg) | ![Estado de cuenta](capturas/estado_cuenta.jpg) |

| Balance de comprobación | Morosidad por antigüedad |
|---|---|
| ![Balance](capturas/balance.jpg) | ![Morosidad](capturas/morosidad.jpg) |

| Tasa de cambio | Portería |
|---|---|
| ![Tasas](capturas/tasas.jpg) | ![Portería](capturas/porteria.jpg) |

| Pases de visita | Tickets |
|---|---|
| ![Pases](capturas/pases.jpg) | ![Tickets](capturas/tickets.jpg) |

| Novedades | Unidades |
|---|---|
| ![Novedades](capturas/novedades.jpg) | ![Unidades](capturas/unidades.jpg) |

| Directorio | Usuarios de la administradora |
|---|---|
| ![Directorio](capturas/directorio.jpg) | ![Usuarios](capturas/usuarios.jpg) |

| Documentos | Comunicados |
|---|---|
| ![Documentos](capturas/documentos.jpg) | ![Comunicados](capturas/comunicados.jpg) |

Ensayo con condominios, torres, unidades y residentes inventados.

## Roles

| Rol | Qué hace |
|---|---|
| Administrador | Condominio, cobranza, contabilidad, usuarios y comunicados. |
| Contador | Libro diario, mayor, balance de comprobación y gastos. |
| Junta | Consulta las cuentas y las novedades de su condominio, sin editar. |
| Administradora (cartera) | Gestiona varios condominios desde una sola cuenta. |
| Superadministrador de plataforma | Tasas de cambio y configuración general. |
| Soporte de la plataforma | Atiende los casos de todos los clientes desde una bandeja centralizada. |
| Propietario | Su estado de cuenta, sus pagos y sus pases de visita. |
| Inquilino | El estado de cuenta de su unidad mientras dure el alquiler. |
| Conserje | El libro de novedades de su turno. |
| Vigilante | Valida pases de visita y ve quién está dentro ahora. |

Cada persona entra con su propia cuenta y ve solo los datos de su condominio.

## Garantías técnicas

| Área | Qué garantiza el sistema |
|---|---|
| **Aislamiento multi-condominio** | Una administradora con varios condominios los gestiona desde una cuenta, pero los datos de uno nunca se mezclan con los de otro. |
| **Doble autenticación** | Quien administra dinero o datos de varios condominios necesita una segunda clave de un solo uso para entrar, además de su contraseña. |
| **Bitácora que nadie puede borrar** | Cada acción importante (un pago aprobado, un gasto registrado, un cambio de permisos) queda en una tabla de solo inserción: ni un administrador puede editarla después. |
| **Contabilidad que no se reescribe** | Un asiento ya contabilizado se corrige con un asiento de reverso, nunca editando el original. |
| **Permisos granulares** | 54 permisos independientes: cada pantalla exige el suyo, no un simple «administrador ve todo». |
| **Calidad** | 2.487 pruebas automatizadas verifican el aislamiento, los permisos y los cálculos contables antes de que un cambio llegue a producción. |

## Construido con

| Lenguaje | Dónde |
|---|---|
| **PHP** | Lógica: cobranza, contabilidad, portería, permisos y aislamiento multi-condominio |
| **PHP (plantillas)** | Las pantallas, pensadas primero para el teléfono |
| **SQL** | Almacenamiento multi-condominio |

La barra de lenguajes de GitHub mide solo los ficheros de este repositorio, que
es documentación.

## En cifras

- **2.487 pruebas automatizadas**, sin fallos.
- **14 épicas** del roadmap construidas y auditadas.
- **11 roles** de usuario, cada uno con pantalla propia.
- **54 permisos** granulares.

## ¿Listo para ponerle orden a las cuentas de su condominio?

Le mostramos el sistema en vivo, con un condominio de prueba armado para su
caso: cuántos condominios administra y qué le pesa más hoy, cobranza,
contabilidad o portería.

- Web: [condoku.com](https://condoku.com)
- Correo: [info@condoku.com](mailto:info@condoku.com)
- Presentación: [PDF de 18 diapositivas](presentacion/Condoku-presentacion.pdf)

## Novedades

- **30-oct-2026** · Documentos y comunicados con visibilidad jerárquica por rol (reglamento, actas, balances y avisos).
- **29-oct-2026** · Publicación de la vitrina, con su presentación en PDF descargable.

Registro completo: [CHANGELOG.md](CHANGELOG.md).

© 2026 Kusarive Solutions LLC. Ver [LICENSE](LICENSE).
