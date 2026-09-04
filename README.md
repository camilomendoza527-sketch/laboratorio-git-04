# Modelo de Negocio y Requerimientos: Sistema ATM

**Asignatura:** Requerimientos de Software  
**Metodología:** Análisis y Diseño Orientado a Objetos (Stephen Schach)  

## Información General
* **Autor:** Youbry Camilo Mendoza Martínez
* **Proyecto:** Modelo de Negocio para Cajero Automático (ATM)
* **Fecha:** 2026

---

## Descripción del Proyecto
Este proyecto aborda la formalización del modelo de negocio y la elicitación de requerimientos para un sistema de Cajero Automático (ATM). El objetivo principal es mitigar fallas operativas recurrentes, como caídas de red y bloqueos del sistema operativo en horas pico de alta demanda transaccional, garantizando la continuidad y disponibilidad del servicio financiero bajo la metodología de Stephen Schach.

---

## Contenido del Repositorio
* `docs/`: Documentación detallada del proyecto (incluye el informe formal en formato Word y PDF).
* `diagramas/`: Archivos fuente de modelado gráfico en `.drawio` e imágenes exportadas en `.png`.

---

## Actores del Sistema
* **Customer / Usuario:** Cliente externo que realiza operaciones transaccionales (consultas, retiros, depósitos).
* **Técnico de Mantenimiento:** Personal interno encargado del reabastecimiento de efectivo y soporte técnico de la terminal.
* **Bank System / Red:** Sistema core bancario externo que autoriza, procesa y valida las transacciones.

---

## Casos de Uso
1. **Autenticar Usuario:** Validación de identidad y credenciales (tarjeta y PIN) frente al core bancario.
2. **Consultar Saldo:** Verificación del balance de fondos disponibles en cuentas vinculadas.
3. **Retirar Efectivo:** Procesamiento de solicitudes de retiro y dispensación de dinero físico.
4. **Depositar Dinero:** Recepción, validación y acreditación de dinero en efectivo.
5. **Recargar Efectivo:** Reabastecimiento físico de los casetes de billetes y calibración del estado operativo por parte del personal técnico.
