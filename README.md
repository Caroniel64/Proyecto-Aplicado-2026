Proyecto: **FactuCloud** – Entregable 1
> **Fecha de entrega:** 22/01/2026
---

## 1. Ficha del Equipo (Info Semana 1)

*Esta sección formaliza la constitución del grupo de trabajo.*

| Nombre del Estudiante  | Rol Principal| GitHub User   |
| ---------------------- | -------------| ------------- |
| Caroniel Reynoso       | Fullstack    | @Caroniel64   |
| Yoelvi Suarez Rondon   |  Fullstack   | @natha-bit    |
| Heidy Lissette         | Frontend     |               |

---

## 2. Definición del Negocio

### 🏢 La Empresa (Cliente)

* **Nombre:** Comercial La Central SRL (Empresa ficticia basada en procesos reales).
* **Sector:** Comercio y Ventas de Productos al Detalle.

### ⚠️ El Problema

Actualmente, **“Comercial La Central”** realiza su facturación de forma manual utilizando talonarios físicos y hojas de Excel. Esto genera varios problemas importantes:

1. **Errores en las facturas:** Cálculos incorrectos de totales, impuestos y descuentos.
2. **Falta de control de ventas:** No existe un reporte claro de ventas diarias, mensuales o por cliente.
3. **Dificultad en el cuadre de caja:** El cierre diario se hace manualmente, lo que provoca pérdidas de tiempo y errores frecuentes.
4. **Historial limitado:** Buscar facturas antiguas es lento y poco confiable.

### 💡 La Solución Propuesta

Desarrollar **“FactuSys”**, un **sistema web de facturación** que permita registrar clientes, productos y ventas, generar facturas automáticamente, llevar control de caja y emitir reportes claros para la administración del negocio.

---

## 3. Alcance del Proyecto (Scope)

### ✅ Dentro del Alcance (MVP – Producto Mínimo Viable)

*Funcionalidades críticas que estarán listas para la semana 11.*

1. **Gestión de Clientes:** Registro, edición y consulta de clientes.
2. **Gestión de Productos/Servicios:** Creación de productos con precio e impuestos.
3. **Facturación:** Generación de facturas con cálculo automático de subtotal, impuestos y total.
4. **Punto de Venta (POS) Básico:** Registro de ventas y método de pago (Efectivo / Transferencia).
5. **Cierre de Caja:** Reporte de ingresos diarios y resumen de ventas.

### 🚫 Fuera del Alcance

*Cosas que NO se desarrollarán en este curso por limitaciones de tiempo.*

1. **Facturación Electrónica Gubernamental:** No se integrará con la DGII ni emisión de comprobantes fiscales electrónicos.
2. **Pagos en Línea:** No se integrarán pasarelas de pago (tarjeta o PayPal).
3. **Control Avanzado de Inventario:** Solo se manejará el producto a nivel básico, sin alertas de stock.
4. **App Móvil Nativa:** Será una aplicación web responsiva, no una app para Play Store.

---

## 4. Stack Tecnológico

* **Lenguaje:** JavaScript / TypeScript
* **Frontend:** React.js + Tailwind CSS
* **Backend:** Node.js con Express
* **Base de Datos:** PostgreSQL (Base de datos relacional para manejo de ventas y facturas).
* **Herramientas Extra:** Vercel (Deploy), GitHub Projects (gestión del proyecto).

---

## 5. Requerimientos

### ⚙️ Requerimientos Funcionales (RF)

| ID    | Título                 | Descripción Breve                                                 | Prioridad      |
| ----- | ---------------------- | ----------------------------------------------------------------- | -------------- |
| RF-01 | Gestión de Clientes    | El sistema permitirá crear, editar y consultar clientes.          | Media          |
| RF-02 | Gestión de Productos   | El administrador podrá registrar productos con precio e impuesto. | Alta           |
| RF-03 | Generación de Facturas | El sistema calculará automáticamente subtotal, impuestos y total. | Alta (Crítico) |
| RF-04 | Registro de Pagos      | El usuario podrá registrar el método de pago de cada factura.     | Alta           |
| RF-05 | Reporte de Ventas      | Generación de reportes diarios de ventas y cierre de caja.        | Alta           |

### 🛡️ Requerimientos No Funcionales (RNF)

1. **Usabilidad:** La creación de una factura no debe tomar más de 5 pasos.
2. **Seguridad:** Solo usuarios autorizados podrán acceder al sistema.
3. **Rendimiento:** El sistema debe responder en menos de 2 segundos al generar una factura.
4. **Diseño Responsivo:** El sistema debe funcionar correctamente en computadoras, tablets y celulares.

---
... (Quedan 10 líneas)
