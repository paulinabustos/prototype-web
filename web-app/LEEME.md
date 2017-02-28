[![Build Status](https://travis-ci.org/shapeable/prototype-web.svg?branch=master)](https://travis-ci.org/shapeable/prototype-web)

[![Code Climate](https://codeclimate.com/github/shapeable/prototype-web/badges/gpa.svg)](https://codeclimate.com/github/shapeable/prototype-web)

[![Test Coverage](https://codeclimate.com/github/shapeable/prototype-web/badges/coverage.svg)](https://codeclimate.com/github/shapeable/prototype-web/coverage)

#California Alerts
===
 ([IN ENGLISH](./README.md))
___
​
Realizado en  [Ruby on Rails](http://rubyonrails.org/) con Rails '5.0.1'
​
##Dependencias:
​
**[Sendgrid](https://sendgrid.com/)**: para el manejo de correos.

**[Twilio](https://www.twilio.com/)**: para el manejo de SMS.

**[Swagger](http://swagger.io/)**: Framework para APIs.

===

## Base de Datos PostgreSQL
<img src="https://cdn.rawgit.com/shapeable/prototype-web/dev/diagrams/relational.png" alt="DP" height="300" width="500"/>

===
​
##Environments:
​
​Se requieren las siguientes llaves:
​
###Twilio

    FRIENDLY_NAME: ''
    TWILIO_ACCOUNT_SID: ''
    TWILIO_AUTH_TOKEN: ''
    SENDER_PHONE_NUMBER: ''

###Sengrid

    SENDER_EMAIL: ''
   
   
===

##Instalación:
​
Puedes acceder al repositorio en [GitHub](https://github.com) de [California Alerts](https://github.com/shapeable/prototype-web)

Clonamos el repositorio:
    
    git@github.com:shapeable/prototype-web.git
    
Entramos a la carpeta: 

	cd web-app
	      
Instalamos y actualizamos las gemas:
    
    bundle install
    
Creamos las migraciones de la base de datos:
    
    rake db:setup
​
Iniciamos el servidor:
    
    rails s
    

===
 
##¿Preguntas o problemas?
​
Mantenemos la conversación del proyecto en nuestra página de problemas  [issues](https://github.com/shapeable/prototype-web/issues). Si usted tiene cualquier otra pregunta, nos puede contactar por correo a <equipo@civica.digital>.


##Licencia
​
Licencia: Apache License, Version 2.0 [Lee la documentación](http://www.apache.org/licenses/LICENSE-2.0) para más información.
​
Creado por [Cívica Digital](http://www.civica.digital), 2017.