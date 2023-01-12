Backend del Mínimo 2

Ha sido necesario crear una nueva clase llamada Faqs, la cual está compuesta por dos Strings (question y answer), con sus getters y setters
Se ha modificado la interfaz del GameManager y su implementación, añadiendo funcionalidades y servicios para las FAQs. Básicamente, añadir FAQs a una lista y obtener esa lista
De momento, estas FAQs no están implementadas en ninguna base de datos, queda pendiente para la versión final del proyecto
El GameManagerService se ha modificado para poder hacer un POST de las FAQs (solo serviría para hacerse desde el Swagger) y un GET (para conseguir las FAQs en Android y mostrarlas al usuario)