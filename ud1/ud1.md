# 📌 Resumen del comando `ps` en Linux

El comando `ps` (process status) muestra información sobre los procesos en ejecución en el sistema.

## 🧭 Opciones más utilizadas

| Comando | Descripción |
|--------|-------------|
| `ps` | Muestra los procesos del usuario actual en la terminal actual. |
| `ps -e` | Lista **todos** los procesos del sistema. |
| `ps -f` | Muestra formato extendido (PPID, UID, tiempo, etc.). |
| `ps -ef` | Lista todos los procesos con formato completo (muy usado). |
| `ps aux` | Lista todos los procesos con información detallada usando estilo BSD. |
| `ps aux --sort=-%cpu` | Ordena procesos por **uso de CPU**. |
| `ps aux --sort=-%mem` | Ordena procesos por **uso de memoria**. |
| `ps -u <usuario>` | Muestra procesos pertenecientes a un usuario. |
| `ps -p <PID>` | Muestra información de un PID específico. |

## 🔍 Ejemplos útiles

```bash
# Ver todos los procesos con formato extendido
ps -ef

# Ver procesos ordenados por uso de CPU
ps aux --sort=-%cpu | head

# Ver procesos de un usuario
ps -u nombre_usuario

# Obtener detalles de un proceso concreto
ps -p 1234 -f

![sx](img/disco.webp)
