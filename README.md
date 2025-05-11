<div align="center">
  <h1>Cognixion Studio Sistema Pulpería</h1>
  <p>
    <b>Un sistema personal, modular y completo desarrollado con C# y Python v14</b>
  </p>
  <p>
    <img src="https://img.shields.io/badge/.NET-8.0-blueviolet?logo=.net&logoColor=white" alt=".NET Version">
    <img src="https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white" alt="Python Version">
    <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
    <img src="https://img.shields.io/badge/status-active-success.svg" alt="Status">
  </p>
</div>

## 📋 Características Principales

1. **📦 Gestión Completa de Productos**  
   - Registro de productos con nombre, precio, cantidad en stock y categoría.  
   - Edición y eliminación de productos con actualización en tiempo real.  
   - Visualización en tabla interactiva con filtrado automático.  
   - Control de inventario: el stock se actualiza automáticamente al realizar ventas.

2. **💰 Sistema de Ventas Intuitivo**  
   - **Doble modalidad de venta**:  
     - Productos registrados (selección desde el inventario).  
     - Productos manuales (artículos no registrados, como servicios o productos temporales).  
   - Cálculo automático de subtotales y totales.  
   - Opción para cancelar ventas o eliminar productos individuales.  
   - Registro en base de datos con fecha/hora exacta y tipo de producto (registrado/manual).

3. **📝 Gestión de Deudas y Abonos**  
   - Registro de clientes con información de contacto (nombre, teléfono, dirección).  
   - Creación de deudas vinculadas a clientes (descripción, monto total, fecha).  
   - Sistema de abonos parciales o completos con actualización del saldo pendiente.  
   - Visualización del estado de deudas ("pendiente" o "pagado").  
   - Historial detallado de abonos por deuda.

4. **📊 Reportes y Análisis**  
   - **Gráficos interactivos** (usando Matplotlib):  
     - Ventas por día.  
     - Top 10 productos más vendidos.  
     - Deudas pendientes por cliente.  
   - Historial de ventas agrupadas por fecha.  
   - Exportación implícita (los datos están disponibles en SQLite para análisis externo).

5. **🔒 Seguridad y Acceso**  
   - Base de datos SQLite con estructura relacional (productos, ventas, clientes, deudas).  
   - Validación de datos en todos los formularios (evita errores por entradas inválidas).  
   - Mensajes de confirmación para acciones críticas (eliminar productos, cancelar ventas).

6. **🔄 Funciones Adicionales**  
   - **Interfaz con pestañas** para organizar módulos (Productos, Ventas, Deudas).  
   - Diseño profesional con `ttkthemes` (estilo "clam").  
   - Tablas con scrollbars para manejar grandes volúmenes de datos.  
   - Notificaciones visuales (éxito/error) con `messagebox`.

---

**Flujo de Trabajo:**

1. **Productos**:  
   - Agregar → Llenar formulario → Guardar (actualiza la tabla y el inventario).  
   - Editar/Eliminar → Seleccionar producto → Confirmar cambios.  

2. **Ventas**:  
   - Seleccionar productos (o agregar manuales) → Especificar cantidades → Registrar venta (actualiza stock).  
   - Opción de convertir venta en deuda (vinculada a un cliente).  

3. **Deudas**:  
   - Registrar cliente → Crear deuda → Abonar (reduce saldo pendiente).  
   - Ver detalle de abonos y estado actual.  

---

## 🐲 Tecnologías Usadas

- **Lenguaje**: Python 3.x.  
- **GUI**: Tkinter + ttk (Treeview, Notebook, estilos).  
- **Base de datos**: SQLite3 (almacenamiento local).  
- **Gráficos**: Matplotlib integrado en Tkinter.  


## ✔ Requisitos
- **Python 3.x**
- **Librerías: tkinter, sqlite3, matplotlib, datetime**
- **Opcional: PIL/Pillow (para cambiar el ícono en Linux/Mac)**

## 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 📞 Soporte

Si necesitas ayuda o tienes alguna pregunta:

- Abre un issue en este repositorio
- Únete a nuestro [servidor de Discord](https://discord.gg/cognixion)
- Contacta con el desarrollador en Discord: `tu_usuario#0000`

## 🙏 Agradecimientos

- [discord.js](https://discord.js.org/) por proporcionar una excelente biblioteca
- [Node.js](https://nodejs.org/) por el entorno de ejecución
- A todos los contribuidores y usuarios del bot

---

<div align="center">
  <p>Desarrollado con ❤️ por Cognixion Studio</p>
  <p>
    <a href="https://discord.gg/cognixion">Discord</a> •
    <a href="https://github.com/tu-usuario">GitHub</a> •
    <a href="https://cognixion.com">Website</a>
  </p>
</div>
