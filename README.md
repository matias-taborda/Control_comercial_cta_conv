📊 Control Comercial – Cuenta Convergente
Sistema en Python para el seguimiento de objetivos comerciales de asesores, orientado a cuentas convergentes (Portabilidad, Línea Nueva y Fibra Óptica / BAF).
El programa permite:
Registrar ventas por asesor
Calcular ventas faltantes
Evaluar desempeño diario
Aplicar reglas de mix comercial
Determinar cumplimiento de comisiones

🎯 Objetivo del proyecto
Brindar una herramienta simple y clara para que cada asesor pueda:
Cargar sus ventas manualmente
Ver su estado en tiempo real
Saber si está en condiciones de comisionar
Corregir su estrategia antes de fin de mes

👉 Los objetivos se ingresan manualmente, ya que pueden variar mes a mes.

🧠 Lógica del sistema
Servicios contemplados
📱 Portabilidad
➕ Línea Nueva
🌐 Fibra Óptica (BAF)

Reglas principales
Control de mix de portabilidad (máx. 25% planes 4GB)
Cálculo de ventas faltantes
Promedio de ventas por día hábil
Semáforo de rendimiento:
🟢 Verde
🟡 Amarillo
🔴 Rojo

Evaluación automática de comisiones
🏆 Esquema de comisiones evaluado
Comisión
Portabilidad
Línea Nueva
BAF
60% + sábados libres
Portabilidad 17
Lineas nuevas 2
Baf 3
100% + sábados libres

Portabilidad 28

Lineas nuevas 2

Baf 5

📌 Condición excluyente:
Si el mix de 4GB supera el 25%, no comisiona portabilidad.

🛠️ Tecnologías utilizadas

Jupyter Notebook

#👨‍💻 Autor
Matías Alejandro Taborda
Proyecto desarrollado como parte de portfolio en Python orientado a análisis comercial y control de gestión.
