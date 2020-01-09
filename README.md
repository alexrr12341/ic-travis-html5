# Integración continúa: Comprobación de html5 válido y Despliegue en surge.sh 

[![Build Status](https://travis-ci.com/alexrr12341/ic-travis-html5.svg?branch=master)](https://travis-ci.com/alexrr12341/ic-travis-html5)


Integración continúa con travis que realiza dos operaciones:

* test: Comprueba que el html5 es válido. Para ello vamos a utilizar (https://github.com/svenkreiss/html5validator)
* deploy: Si la prueba ha sido exitosa se sube al servicio surge.sh (http://surge.sh/)


