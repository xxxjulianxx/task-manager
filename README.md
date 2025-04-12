# task_manager.py
def crear_tarea(nombre):
    tarea = {"id": generar_id(), "nombre": nombre, "completada": False}
    tareas.append(tarea)
    return tarea
