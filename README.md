# PayU webcheckout

Documentación: http://developers.payulatam.com/es/web_checkout/integration.html

**Nota:** Es necesario tener cuenta en Payu.

## Probar
1. Editar el archivo `conf.php`., comentar la url sandbox y descomentar la url producción
2. Subir los archivos a un servidor para comprobar las respuestas "verificar que las rutas `$responseUrl` y `$confirmationUrl` del archivo `config.php` concuerden con la url del archivo
3. Ejecutar `index.php` y darle click en el boton enviar
4. En la pasarela de pagos para verificar los estados de transacción: escoger cualquier credicard y en el campo del nombre ingresar segun el caso:  APPROVED, REJECTED, PENDING

**Nota:** Tener en cuenta cambiar la referencia "referenceCode" en cada prueba

## Sandbox

1. Editar el archivo `conf.php`.
2. Subir los archivos a un servidor para comprobar las respuestas "verificar que las rutas `$responseUrl` y `$confirmationUrl` del archivo `config.php` concuerden con la url del archivo
3. Ejecutar `index.php` y darle click en el boton enviar
4. En la pasarela de pagos para verificar los estados de transacción: escoger cualquier credicard y en el campo del nombre ingresar segun el caso:  APPROVED, REJECTED, PENDING

| merchantId | API Login       | API Key                    | accountId | País      |
|------------|-----------------|----------------------------|-----------|-----------|
| 508029     | pRRXKOl8ikMmt9u | 4Vj8eK4rloUd272L48hsrarnUA | 512322    | Argentina |
|            |                 |                            | 512325    | Chile     |
|            |                 |                            | 512321    | Colombia  |
|            |                 |                            | 512324    | México    |
|            |                 |                            | 512326    | Panamá    |
|            |                 |                            | 512323    | Perú      |
|            |                 |                            | 512327    | Brasil    |



## Credicards de prueba
Son credicards generadas en linea. 

### VISA 											
4663982493286321							
CVV2/CVC2: 747							
Fecha: 11/2019							

### American
378927791329723
CVV2/CVC2: 5302
Fecha: 03/2019


### Mastercard
5154017132448314
CVV2/CVC2: 359
Fecha: 05/2018