========================
 Despliegue de Odoo (8.0) con Workers (Gunicorn + Supervisor + openerp-wsgi.py)
========================

(doc por terminar)

# Intro
Realizar el despliegue de Odoo (openerp v8.0) con workers requiere un despliegue un tanto diferente
de los métodos tradicionales manejados en Odoo, esto debido a que es necesario desplegar un middleware
que se encargue de manejar los workers (gunicorn) y un servicio (supervisor) para demonizar el middleware.


    # Instalar requisitos previos:
    apt-get install gunicorn supervisor 

    # Configuración openerp-wsgi.py

    # Configuración Gunicorn

    # Configuración Supervisor
