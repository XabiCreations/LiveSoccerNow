LiveSoccerNow - Documentación del Proyecto
==========================================

Descripción del Proyecto
------------------------

LiveSoccerNow es una plataforma web desarrollada en Python utilizando MVC (Modelo-Vista-Controlador). La aplicación se centra en proporcionar información en tiempo real sobre partidos de fútbol, incluyendo resultados, próximos partidos y noticias relacionadas.

Funcionalidades
---------------

1.  Inicio: Página principal que destaca la marca y ofrece acceso rápido a otras secciones.
2.  Resultados: Muestra los resultados recientes de los partidos, incluyendo detalles como goles, quien a marcado,  fecha y hora.
3.  Mis Equipos: Permite a los usuarios hacer un seguimiento personalizado de sus equipos favoritos.
4.  Noticias: Sección que presenta noticias sobre el fútbol.

Tecnologías Utilizadas
----------------------

-   Lenguaje de Programación: Python
-   Framework MVC: Flask
-   Base de Datos: PGAdmin (PostgreSQL)
-   Interfaz de Usuario: HTML y CSS
-   API Externa: Se utiliza una API externa para obtener datos sobre partidos de fútbol. (https://www.openligadb.de/)

Instalación del Proyecto
------------------------

1.  Clona el repositorio desde GitHub:
git clone https://github.com/XabiCreations/LiveSoccerNow.git

cd LiveSoccerNow

2.  Crea y activa un entorno virtual:

python -m venv venv

source venv/bin/activate  # Para sistemas basados en Unix

3.  Instala las dependencias:

pip install -r requirements.txt

4.  Configura la base de datos PGAdmin con las credenciales correspondientes.

5.  Ejecuta la aplicación:

python app.py

6.  Accede a la aplicación desde tu navegador: http://localhost:5000

Datos Extraídos por la API
--------------------------

1.  Equipos: Nombre, icono.
2.  Partidos: Fecha, hora, puntuación, goles (jugador, minuto, si es penalty o propia puerta).

Estructura del Proyecto
-----------------------

-   static: Contiene archivos estáticos como hojas de estilo y scripts.
-   templates: Almacena los archivos HTML que conforman las vistas de la aplicación.
-   app.py: Archivo principal que inicia la aplicación Flask.
-   models.py: Define los modelos de datos para la base de datos.
-   controllers.py: Contiene la lógica del controlador para manejar las solicitudes del usuario.
-   config.py: Configuración de la aplicación.

Espero que te guste!
