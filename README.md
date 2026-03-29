**Teclado Macro programable 4x4**

Proyecto de un Stream Deck casero basado en un ESP32-S3, implementado mediante un teclado matricial 4x4 con diodos para eliminación de ghosting. 
El sistema permite la ejecución de macros personalizadas a partir de la detección eléctrica de cada tecla. La arquitectura se basa en el escaneo continuo de los pines 
asociados al teclado matricial, permitiendo identificar de forma eficiente la interacción del usuario. Los eventos generados son transmitidos mediante 
comunicación serial hacia una aplicación en Java, donde se realiza el mapeo lógico entre cada identificador de tecla y su acción correspondiente, 
como la ejecución de URLs, despliegue de imágenes o cualquier otro comportamiento configurado dinámicamente. Este enfoque desacopla la capa de hardware 
del procesamiento de alto nivel, permitiendo una mayor flexibilidad, escalabilidad y personalización del sistema.
