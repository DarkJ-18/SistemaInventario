# Sistema de Gestión de Ventas e Inventario

## 1. Resumen Ejecutivo

Esta plataforma es una solución integral diseñada para optimizar las operaciones comerciales diarias, simplificando la administración de inventarios, ventas y facturación mediante una interfaz moderna e intuitiva.

**Estado actual del proyecto:**  
- ✅ Funcional y listo para despliegue.  
- ✅ Completamente localizado al español.  
- ✅ Diseño responsivo (adaptable a diferentes dispositivos).

---

## 2. Funcionalidades Principales para el Negocio

### 📦 Gestión de Inventario (Módulo Store)

El corazón del sistema permite un control total sobre el stock mediante:  

- **Dashboard Interactivo:** Visualización rápida de métricas clave y gráficos de rendimiento en tiempo real para apoyar la toma de decisiones.

![Panel de Control - Métricas y Gráficos](capturas/Panel_de_Control_Metricas_y_Graficos.jpg)

- **Catálogo de Productos y Categorías:** Creación, edición y categorización eficiente de productos para mantener el inventario organizado.

![Listado de Productos](capturas/Products.jpg)

![Gestión de Categorías](capturas/Categories.jpg)

- **Alertas de Stock:** Monitoreo visual para prevenir desabastecimientos y anticipar compras.

### 💰 Gestión de Transacciones

Control financiero detallado de las operaciones de compra y venta:  

- **Registro de Ventas:** Flujo rápido para registrar salidas de mercancía, calculando automáticamente totales e impuestos.

![Historial de Ventas](capturas/Sales.jpg)

- **Registro de Compras:** Control de entradas de proveedores y costos para mantener el inventario actualizado.

![Registro de Compras](capturas/Purchases.jpg)

- **Historial de Movimientos:** Trazabilidad completa de cada movimiento de mercancía y sus documentos asociados.

### 📄 Documentación y Cuentas (Bills & Invoice)

Gestión interna de documentación comercial:

- **Generación de Documentos de Venta:** Creación de documentos internos para control de ventas con cálculo automático de precios, totales e impuestos.

![Creación de Documentos](capturas/Invoices.jpg)

> ⚠️ **IMPORTANTE - Aclaración Legal:**  
> Los documentos generados por este sistema son **únicamente para control interno y visualización**. NO constituyen facturas electrónicas legales ni cumplen con los requisitos de facturación fiscal establecidos por la DIAN u otras autoridades tributarias.  
> 
> Para facturación electrónica legal, el cliente debe continuar utilizando su proveedor autorizado de facturación electrónica o contratar uno aparte. Este sistema puede complementar ese proceso registrando las ventas de manera paralela para control de inventario y gestión interna.

- **Gestión de Cuentas:** Seguimiento interno de cuentas por cobrar y pagar.

### 👥 Gestión de Usuarios, Clientes y Personal (Accounts)

Seguridad y organización de los actores del sistema:  

- **Gestión de Personal:** Administración de empleados con diferentes roles y niveles de acceso.

![Gestión de Personal](capturas/profiles.jpg)

- **Base de Datos de Clientes y Proveedores:** Registro centralizado de información de contacto y relaciones comerciales.

![Listado de Clientes](capturas/customers.jpg)

![Gestión de Proveedores](capturas/vendors.jpg)


---

## 3. Ventajas Competitivas

1. **Tecnología robusta:** Construido sobre Django (Python), framework de nivel empresarial reconocido por su seguridad y escalabilidad.  
2. **Diseño moderno:** Utiliza Bootstrap para asegurar una experiencia limpia y fácil de navegar, reduciendo la curva de aprendizaje.  
3. **Flexibilidad de instalación:** Desplegable en servidores tradicionales (Linux/Windows) o mediante contenedores Docker.
4. **Enfoque en control interno:** Optimizado para la gestión operativa sin las complejidades de cumplimiento fiscal, permitiendo que se integre con su sistema de facturación legal existente.

---

## 4. Requisitos Técnicos Mínimos

Para implementar el sistema en instalaciones del cliente o en la nube:

- **Servidor:** Compatible con Python 3.12 o superior.  
- **Contenedores (opcional):** Soporte para Docker si se prefiere instalación contenerizada.  
- **Base de datos:** Configurable (SQLite en desarrollo, PostgreSQL/MySQL para producción).

---

## 5. Alcance y Limitaciones

### ✅ Lo que el Sistema INCLUYE:

- Control completo de inventario en tiempo real
- Registro de compras y ventas con cálculos automáticos
- Generación de documentos internos de venta
- Gestión de clientes, proveedores y personal
- Dashboard con métricas y reportes
- Control de cuentas por cobrar y pagar (interno)
- Alertas de stock y seguimiento de movimientos

### ❌ Lo que el Sistema NO INCLUYE:

- **Facturación electrónica legal** (no emite facturas válidas ante la DIAN)
- **Integración con plataformas de facturación electrónica** (puede agregarse como desarrollo adicional)
- **Conexión con sistemas contables externos** (ERP, software contable)
- **Conexión con pasarelas de pago** (puede agregarse como desarrollo adicional)
- **Reportes fiscales automatizados** para declaración de impuestos

> 💡 **Nota:** Cualquier funcionalidad no incluida puede cotizarse como desarrollo evolutivo adicional.

---

## 6. Modelo de Inversión y Servicio Gestionado

Esta propuesta combina una inversión inicial accesible con una cuota mensual que garantiza operación continua, hosting profesional y acompañamiento técnico. El objetivo es claridad total sobre qué está pagando y qué valor recibe en cada componente.

### 6.1 Inversión Única de Puesta en Marcha – $500.000 COP

La **Inversión Única de Puesta en Marcha** cubre:

✅ Licencia de uso del sistema  
✅ Configuración inicial personalizada  
✅ Parametrización según procesos del negocio  
✅ Carga de datos iniciales (productos, categorías, clientes)  
✅ Capacitación básica del personal  

Este monto representa un **precio de entrada bajo** comparado con ERPs genéricos que requieren licenciamientos costosos y parametrizaciones complejas.

### 6.2 Cuota Mensual de Servicio Gestionado – $200.000 COP

La **Cuota Mensual** garantiza que la aplicación esté disponible, segura y correctamente mantenida, sin que el cliente tenga que encargarse de temas técnicos.

**Incluye:**

🌐 **Hosting Premium en Railway**  
Plataforma moderna de nube con infraestructura escalable y alta disponibilidad, permitiendo que el sistema crezca automáticamente ante aumentos de demanda.

🛠️ **Soporte Prioritario**  
Atención prioritaria de incidentes, corrección rápida de errores y respuesta ante fallas operativas sin cobros adicionales.

🔄 **Mantenimiento Preventivo y Actualizaciones**  
Actualizaciones de seguridad, ajustes de código y mantenimiento para mantener la aplicación robusta y alineada con buenas prácticas.

📊 **Monitoreo Continuo**  
Supervisión del rendimiento y disponibilidad del sistema para prevenir problemas antes de que afecten la operación.

### 6.3 Cláusula de Uso Justo y Escalabilidad

Los **$200.000 COP mensuales** cubren el **uso normal esperado** del sistema según el tamaño y operación actual del negocio.  

Si el sistema experimenta un **crecimiento significativo** que incremente el uso de recursos en más del **50% sostenido por 2 meses consecutivos**, se aplicará una política de **"Uso Justo y Escalabilidad"**.

En ese escenario:
- ✅ Se notificará con **30 días de anticipación**
- ✅ Se presentará un análisis del nuevo nivel de demanda
- ✅ Se propondrá un ajuste de tarifa transparente para ampliar recursos
- ✅ Se garantizará que el rendimiento óptimo se mantenga

---

## 7. Plan de Implementación

Adopción ordenada con bajo riesgo y mínima interrupción de la operación diaria.

**Fase 1 – Validación de Alcance** (Semana 1)  
Revisión conjunta de procesos y definición de datos iniciales a cargar.

**Fase 2 – Configuración y Despliegue** (Semana 2)  
Instalación en Railway, configuración de parámetros generales (impuestos, moneda, usuarios).

**Fase 3 – Carga de Datos** (Semana 3)  
Carga de información validada para visualización previa a producción.

**Fase 4 – Capacitación y Pruebas** (Semana 4)  
Sesión de capacitación y ejecución de pruebas con usuarios clave.

**Fase 5 – Salida a Producción** (Semana 5)  
Puesta en marcha con datos reales y acompañamiento cercano durante las primeras semanas.

---

## 8. Soporte y Acompañamiento

**Canales de Atención:**  
WhatsApp, correo electrónico y teléfono para solicitudes de soporte.

**Horarios y Tiempos de Respuesta:**  
- Horario laboral (Lunes a Viernes, 8AM - 6PM)
- Prioridad alta para incidentes críticos (imposibilidad de registrar ventas/consultar inventario): **4 horas**
- Consultas generales: **24 horas**

**Alcance del Soporte Incluido:**  
✅ Atención de fallas técnicas  
✅ Corrección de errores  
✅ Apoyo en uso normal de la herramienta  
✅ Consultas sobre funcionalidades existentes  
❌ Desarrollos nuevos o cambios mayores (se cotizan como evolutivos)  
❌ Integración con sistemas externos (se cotiza por separado)

---

## 📞 Contacto

**Juan Camilo**  
📧 Email: [j.juancamilojurado@gmail.com]  
📱 WhatsApp: [3132973032]

---

## 📋 Anexo: Preguntas Frecuentes

**P: ¿El sistema genera facturas legales para la DIAN?**  
R: No. El sistema genera documentos internos para control de inventario y ventas, pero NO son facturas electrónicas válidas fiscalmente. Debe mantenerse su proveedor de facturación electrónica autorizado.

**P: ¿Se puede integrar con mi software de facturación actual?**  
R: Sí, pero requiere un desarrollo evolutivo adicional que debe cotizarse por separado según la complejidad de la integración.

**P: ¿Qué pasa si mi negocio crece mucho?**  
R: El sistema escala automáticamente en Railway. Si el crecimiento supera el 50% de uso sostenido, se notifica con 30 días de anticipación para ajustar recursos y tarifa transparentemente.

**P: ¿Puedo exportar mis datos?**  
R: Sí, el sistema permite exportar reportes e información en formatos estándar (CSV, PDF) para análisis externo.

---

*Propuesta válida por 30 días a partir de la fecha de emisión.*
