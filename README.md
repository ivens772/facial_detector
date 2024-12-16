
# Levantar Servicio de Python

Este documento describe los pasos para configurar y levantar un servicio en Python, utilizando la versión **Python 3.12.3**.

---

## **Requisitos previos**
- Tener **Python 3.12.3** instalado en tu sistema.
- Tener acceso al archivo `app.py` que contiene el servicio.

---

## **Pasos para levantar el servicio**

### 1. Crear un entorno virtual
Crea un entorno virtual para aislar las dependencias del proyecto:
```bash
python -m venv venv
```

### 2. Activar el entorno virtual
Activa el entorno virtual para instalar las dependencias y ejecutar el servicio:
- **En Windows:**
  ```bash
  venv\Scripts\activate
  ```
- **En Linux/Mac:**
  ```bash
  source venv/bin/activate
  ```

### 3. Instalar dependencias
Instala las dependencias necesarias:
```bash
pip install -r requirements.txt
```

### 4. Levantar el servidor
Ejecuta el archivo `app.py` dentro de la carpera ./src para iniciar el servicio:
```bash
python app.py
```

---

## **Notas adicionales**
- Asegúrate de que todas las dependencias adicionales estén listadas en un archivo `requirements.txt` si es necesario.
- Si no tienes la versión correcta de Python, descárgala desde [python.org](https://www.python.org/downloads/).

---

¡Listo! Ahora deberías tener el servicio corriendo correctamente.
