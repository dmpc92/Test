# Test
Jmeter test

Es la primera vez que utilizo JMeter. Al configurar ambas request HTTP get estoy pidiendo un recurso y cuando se configura el REsponse assertion por lo que veo se comparan valores, similar al método Assert.assertEquals() que se utiliza en Java(con Junit).
Para visualizar resultados tuve que agregar un Listener(elegí "View Results Tree). Pude ver que el primer request fue exitoso con un result code 200 pero el segundo no, ya que recibí la siguiente respuesta: 
Response code:400
Response message:Bad Request
Si bien entiendo que esta respuesta significa que hay algo incorrecto de mi lado al pedir el recurso, no logro ubicar mi error.
