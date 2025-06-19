![Motor de avance y retroceso](https://github.com/user-attachments/assets/d4d868e0-0b83-4246-a92e-2b640542d7cc)

# Motor-de-avance-y-retroceso-
El control de motor de avance y retroceso basado en PLC es una solución ampliamente utilizada en la automatización industrial para cambiar la dirección de un motor trifásico de forma segura, eficiente y automática.
Mediante el uso de botones de control, lógica programada en el PLC, y componentes eléctricos como contactores y relés, se logra un sistema confiable que protege el motor y asegura una operación adecuada.

Descripción del sistema:

El sistema está organizado en tres secciones clave:

Panel de control (Campo):

Botones de avance (FWD), retroceso (REV) y paro (STOP).

El operador inicia manualmente las órdenes de movimiento.

Sala de control (PLC):

El PLC recibe señales desde los botones y ejecuta lógica de control y enclavamiento.

Verifica condiciones de seguridad antes de activar cualquier salida.

Solo energiza un contactor (avance o retroceso) si es seguro hacerlo.

Centro de control de motores (MCC):

Incluye MCB (disyuntor principal), contactores FWD y REV, y el OLR (relé de sobrecarga).

Proporciona alimentación al motor y protección contra sobrecargas.

Funcionamiento en modo reversa:

Cuando se presiona el botón REV, el PLC verifica:

Que el contactor de avance no esté activado.

Que no haya condición de fallo o sobrecarga.

Que el botón de parada no esté activo.
Si todo está en orden, energiza la bobina de reversa, haciendo que el motor gire en sentido contrario.

Condición de paro o falla:

Si se pulsa el botón STOP o el relé de sobrecarga (OLR) detecta un problema, el PLC desenergiza ambos contactores inmediatamente. Esto detiene el motor y previene daños.

Seguridad y enclavamiento:

El sistema evita que avance y retroceso estén activos al mismo tiempo.

Protege contra cortocircuitos entre fases.

El botón de parada tiene prioridad sobre cualquier otra señal.

El OLR interrumpe la alimentación en caso de sobrecarga.

Aplicaciones comunes:

Transportadores bidireccionales

Mezcladoras o agitadores

Portones industriales y persianas

Maquinaria que requiere inversión de giro
