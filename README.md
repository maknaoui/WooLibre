# WooLibre
Woocommerce - Mercado Libre

Este repositorio contiene un plugin de Woocommerce para sincronizar productos y actualizar el stock entre Mercado Libre y WooCommerce.

## Descripción

Este script facilita la gestión de productos entre tu tienda WooCommerce y tus publicaciones en Mercado Libre. Permite:

* **Sincronización de productos:** Importa y actualiza productos de WooCommerce a Mercado Libre y viceversa.
* **Actualización de stock:** Actualiza automáticamente el stock en WooCommerce cuando se realiza una venta en Mercado Libre.

## Requisitos

* PHP 7.4 o superior
* WooCommerce instalado y configurado
* Cuenta de desarrollador de Mercado Libre con acceso a la API
* Composer (opcional, pero recomendado para gestionar dependencias)

## Instalación

1.  Clona este repositorio:

    ```bash
    git clone https://github.com/maknaoui/WooLibre.git
    ```
2.  Configura las credenciales de la API de Mercado Libre y la conexión a WooCommerce:

    * Crea un archivo `.env` en la raíz del proyecto.
    * Añade las siguientes variables de entorno con tus credenciales:

        ```
        MERCADOLIBRE_APP_ID=tu_app_id
        MERCADOLIBRE_SECRET_KEY=tu_secret_key
        WOOCOMMERCE_URL=tu_url_de_woocommerce
        WOOCOMMERCE_CONSUMER_KEY=tu_consumer_key_de_woocommerce
        WOOCOMMERCE_CONSUMER_SECRET=tu_consumer_secret_de_woocommerce
        ```
3.  Copiar el archivo "WooLibre" en la carpeta "wp-content/plugins/"
4. Enjoy!
## Contribución

¡Las contribuciones son bienvenidas! Si encuentras algún error o tienes alguna mejora, no dudes en crear un pull request.

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.
