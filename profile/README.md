<div align="center">

# Tuio

### Tecnología para administrar, conectar y comprender negocios

Tuio integra la operación diaria de puntos de venta con servicios en la nube,
permitiendo que restaurantes, patios de comida y negocios con múltiples
sucursales trabajen con continuidad y mantengan su información centralizada.

</div>

## Nuestra visión

Construimos herramientas confiables para que cada negocio pueda concentrarse
en atender a sus clientes. La operación principal permanece disponible en el
local, mientras la plataforma cloud conecta sucursales, terminales y datos de
gestión de forma segura.

## El ecosistema Tuio

| Sistema | Función |
| --- | --- |
| **Tuio POS** | Aplicación de escritorio para pedidos, mesas, ventas, caja, productos, clientes e inventario. |
| **Tuio Cloud** | Plataforma central para organizaciones, sucursales, usuarios, terminales y consolidación de información. |
| **Tuio Sync** | Capa de sincronización que conecta cada instalación local con la nube sin convertir internet en un requisito para vender. |

```text
Operación local                 Sincronización segura                 Tuio Cloud

Pedidos y mesas  ─┐
Ventas y pagos   ─┼──> Cola local ──> Eventos verificables ──> Información centralizada
Caja e inventario─┘
```

## Diseñado para la operación real

- Continuidad de trabajo ante conexiones inestables o interrupciones de internet.
- Gestión de pedidos, mesas, ventas, pagos y movimientos de caja.
- Separación segura entre organizaciones, sucursales y terminales.
- Sincronización gradual y tolerante a fallos, sin bloquear la atención local.
- Trazabilidad de los eventos enviados desde cada punto de venta.
- Base preparada para consulta y supervisión centralizada del negocio.

## Principios del producto

**Operación primero.** Una venta local no debe depender de la disponibilidad de
un servicio externo.

**Seguridad por diseño.** El acceso se controla por organización, sucursal,
usuario y permisos. Cada terminal opera únicamente dentro de su contexto.

**Datos consistentes.** Los eventos se procesan de forma idempotente para evitar
duplicados y conservar la relación entre los registros locales y cloud.

**Crecimiento ordenado.** La plataforma está pensada para acompañar desde una
sola caja hasta operaciones con varias sucursales.

## Tecnología

El ecosistema combina una aplicación de escritorio para Windows con una
plataforma cloud basada en .NET, ASP.NET Core, PostgreSQL y contenedores Docker.
La comunicación entre ambos sistemas utiliza APIs autenticadas y contratos de
sincronización versionables.

## Repositorios

El software principal de Tuio se desarrolla en repositorios privados. Este
perfil público presenta el producto y podrá alojar en el futuro documentación,
herramientas y proyectos que la organización decida compartir con la comunidad.

## Contacto

Para información comercial, alianzas o soporte, utiliza los canales oficiales
publicados en el perfil de esta organización.

---

<div align="center">

**Tuio** · Operación local, información conectada.

</div>
