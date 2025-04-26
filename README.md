# CRUD con Python 🐍 MySQL 📂 y un Dashboard Asombroso 🚀

Aprende a desarrollar un sistema **CRUD** utilizando **Python 🐍** y **MySQL 📂** mientras creas un impresionante panel de control interactivo. Este proyecto es ideal para quienes buscan gestionar datos de manera eficiente y construir aplicaciones dinámicas con una interfaz amigable.

## Vista previa 🗃

![Dashboard Login](https://raw.githubusercontent.com/urian121/imagenes-proyectos-github/master/Dashboard-python-login-urian-viera.png)

![Crear Usuario](https://raw.githubusercontent.com/urian121/imagenes-proyectos-github/master/dashboard-python-crear-user-urian-viera.png)

![Recuperar Contraseña](https://raw.githubusercontent.com/urian121/imagenes-proyectos-github/master/dashboard-python-recuperar-clave-urian-viera.png)

![Panel Principal](https://raw.githubusercontent.com/urian121/imagenes-proyectos-github/master/dashborad-python-home-urian-viera.png)

![Registrar Cliente](https://raw.githubusercontent.com/urian121/imagenes-proyectos-github/master/dashboard-python-registrar-cliente-urian-viera.png)

![Lista de Empleados](https://raw.githubusercontent.com/urian121/imagenes-proyectos-github/master/dashboard-python-lista-empleados-urian-viera.png)

![Lista de Usuarios](https://raw.githubusercontent.com/urian121/imagenes-proyectos-github/master/dashboard-python-lista-usuarios-urian-viera.png)

![Editar Perfil](https://raw.githubusercontent.com/urian121/imagenes-proyectos-github/master/dashboard-python-editar-perfil-urian-viera.png)

![Reporte de Empleados](https://raw.githubusercontent.com/urian121/imagenes-proyectos-github/master/dashboard-python-reporte-empleados-urian-viera.png)

---

## Requerimientos 📋

Para ejecutar este proyecto, necesitas:

- **Servidor Web:** Apache (o equivalente).
- **Base de Datos:** MySQL 5 o superior.
- **phpMyAdmin:** Opcional, para gestionar la base de datos.
- **Entorno de desarrollo todo en uno:** XAMPP, WAMPP u otra alternativa.

---

## Instrucciones para la descarga e instalación 🔧

1. **Descarga el proyecto:** Clona este repositorio o descárgalo como archivo ZIP.

   ```bash
   git clone https://github.com/urian121/CRUD-COMPLETO-con-Python-MySQL-y-un-Dashboard.git
   ```

2. **Importa la base de datos:**
   - Entra a phpMyAdmin (o cualquier gestor MySQL).
   - Importa el archivo `crud_python.sql` incluido en el proyecto.

3. **Configura la conexión:**
   - Abre el archivo `conexionBD.py`.
   - Actualiza los datos de conexión (host, usuario, contraseña, base de datos).

4. **Crea un entorno virtual (opcional):**

   ```bash
   python -m venv env
   source env/bin/activate       # En Linux/Mac
   env\Scripts\activate         # En Windows
   ```

5. **Instala las dependencias:**

   ```bash
   pip install -r requirements.txt
   ```

6. **Ejecuta la aplicación:**

   ```bash
   python app.py
   ```

7. **Accede desde el navegador:**

   - Ingresa a: [http://127.0.0.1:5600/](http://127.0.0.1:5600/)
