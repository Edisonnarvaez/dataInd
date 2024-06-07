# dataInd
Descripción:
DataInd es un proyecto de tesis que tiene como objetivo desarrollar una aplicación para la gestión de indicadores en salud y el seguimiento de los diferentes resultados obtenidos. Esta herramienta permitirá a los usuarios registrar, monitorear y analizar indicadores clave de oportunidad de manera eficiente y precisa.

Características principales:

Gestión de Indicadores: Permite la creación, edición y eliminación de indicadores.
Seguimiento de Resultados: Proporciona funcionalidades para el seguimiento y visualización de los resultados obtenidos a lo largo del tiempo.
Análisis de Datos: Ofrece herramientas de análisis para interpretar los datos y tomar decisiones informadas.
Interfaz de Usuario Amigable: Diseñada para ser intuitiva y fácil de usar.
Tecnologías Utilizadas:

Backend: Desarrollado en Python utilizando el framework Django.
Base de Datos: PostgreSQL, para una gestión robusta y escalable de los datos.
Front-end 
Docker 

Instalación y Configuración:

Clonar el repositorio:
bash
Copiar código
git clone [https://github.com/Edisonnarvaez/dataInd.git]
Crear y activar un entorno virtual:
bash
Copiar código
python3 -m venv env
source env/bin/activate  # En Windows usa `env\Scripts\activate`
Instalar las dependencias:
bash
Copiar código
pip install -r requirements.txt
Configurar la base de datos:
Editar el archivo settings.py para agregar las credenciales de tu base de datos PostgreSQL.
Aplicar las migraciones:
bash
Copiar código
python manage.py migrate
Ejecutar el servidor de desarrollo:
bash
Copiar código
python manage.py runserver
Contribución:
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

Haz un fork del repositorio.
Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
Realiza tus cambios y haz commit (git commit -am 'Añadir nueva funcionalidad').
Sube tu rama (git push origin feature/nueva-funcionalidad).
Abre un Pull Request.
