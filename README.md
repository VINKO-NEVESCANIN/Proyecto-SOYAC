$) Sistema Operativo Básico en Python



$) Descripción

Este proyecto es una simulación de un sistema operativo básico desarrollado en Python, enfocado en la gestión de procesos y planificación de CPU.

Permite modelar cómo un sistema operativo:

Administra procesos
Controla estados
Ejecuta algoritmos de planificación

$) Objetivos
Comprender el funcionamiento interno de un sistema operativo
Implementar algoritmos de planificación de CPU
Aplicar conceptos de concurrencia y estados de procesos
Desarrollar lógica en Python orientada a sistemas

$) Características
✔ Creación de procesos
✔ Visualización de procesos
✔ Eliminación de procesos
✔ Estados de proceso (Listo, Ejecutando, Terminado)
✔ Planificación FCFS
⚠️ Base para Round Robin (por implementar)

🧱 Estructura del proyecto
.
├── main.py
└── README.md
⚙️ Requisitos
Python 3.x
Consola / Terminal
▶️ Ejecución
git clone <URL_DEL_REPOSITORIO>
cd nombre-del-repo
python main.py
🖥️ Vista del sistema
==== SISTEMA OPERATIVO ====
1. Crear proceso
2. Ver procesos
3. Eliminar proceso
4. Ejecutar FCFS
5. Ejecutar Round Robin
6. Salir


🧠 Conceptos implementados
Procesos
Estados de procesos
Planificación de CPU
FCFS (First Come First Serve)
Simulación de ejecución
⚠️ Trabajo pendiente (para estudiantes)

Este proyecto está diseñado como base, por lo que el alumno debe completar:

🔴 Obligatorio
Implementar completamente Round Robin
🟡 Recomendado (para mejor calificación)
Validación de entradas
Manejo de errores
Implementación de diagrama de Gantt
Agregar prioridad a procesos
Métricas:
Tiempo de espera
Tiempo de retorno
🔄 Flujo del sistema
Usuario → Menú → Sistema Operativo → Procesos → Ejecución (FCFS / RR)
🧪 Ejemplo de proceso
P1 | Tiempo: 5 | Estado: Listo
P2 | Tiempo: 3 | Estado: Ejecutando
P3 | Tiempo: 2 | Estado: Terminado
🚀 Roadmap
 Estructura base
 FCFS
 Round Robin completo
 Gantt
 Prioridades
 Interfaz gráfica
