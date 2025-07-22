# 📘 Guía de Usuario: Aplicación de Gestión de Biblioteca

Esta aplicación permite **gestionar libros, usuarios y préstamos** de forma sencilla, usando formularios y consultas personalizadas, todo funcionando sobre archivos `.csv`.

---

## 🖥 Requisitos previos

Para usar la app necesitas:

- Tener instalado **Python 3.8 o superior**
- Tener instalada la librería **Streamlit**
- Tener los archivos del proyecto (`app.py`, `libros.csv`, `usuarios.csv`, `prestamos.csv`) en la misma carpeta

### 🧱 Instalación de dependencias

```bash
pip install streamlit pandas
```

---

## 🚀 Cómo ejecutar la aplicación

```bash
streamlit run app.py
```

---

## 🧭 Navegación de la app

### 1️⃣ Libros
- 📖 Consultar por título, autor o categoría
- ➕ Añadir nuevo libro
- ✏️ Modificar datos por ID
- 🗑️ Eliminar por ID

### 2️⃣ Usuarios
- 🔍 Buscar por nombre, teléfono o email
- ➕ Añadir nuevo usuario
- ✏️ Modificar por ID
- 🗑️ Eliminar por ID

### 3️⃣ Préstamos
- 📋 Consultar por fecha
- 🛑 Ver préstamos vencidos
- ➕ Añadir nuevo préstamo

---

## 🛠 Archivos importantes

| Archivo         | Función                           |
|----------------|------------------------------------|
| `app.py`        | Código principal de la aplicación |
| `libros.csv`    | Base de datos de libros           |
| `usuarios.csv`  | Base de datos de usuarios         |
| `prestamos.csv` | Registro de préstamos             |

---

## 📌 Recomendaciones

- Haz copia de seguridad de los `.csv` regularmente
- No abras los `.csv` mientras la app está en uso para evitar errores
- Para múltiples usuarios, considera usar una base de datos

