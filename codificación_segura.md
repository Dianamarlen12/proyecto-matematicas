# Explicar los principios de codificación segura.

# ¿Qué es la codificación segura?
La codificación segura es diseñar y desarrollar software evitando las debilidades que conducen a vulnerabilidades relacionadas con la seguridad al adherirse a los estándares de seguridad especificados y las mejores prácticas de la industria.

Principios de codificación segura

1. Partir siempre de un modelo de permisos mínimos, es mejor ir escalando privilegios por demanda de acuerdo a los perfiles establecidos en las etapas de diseño.
2. Si se utiliza un lenguaje que no sea compilado, asegurarse de limpiar el código que se pone en producción, para que no contenga rutinas de pruebas, comentarios o cualquier tipo de mecanismo que pueda dar lugar a un acceso indebido.
3. Nunca confiar en los datos que ingresan a la aplicación, todo debe ser verificado para garantizar que lo que está ingresando a los sistemas es lo esperado y además evitar inyecciones de código.
4. Hacer un seguimiento de las tecnologías utilizadas para el desarrollo. Estas van evolucionando y cualquier mejora que se haga puede dejar obsoleta o inseguras versiones anteriores.
5. Todos los accesos que se hagan a los sistemas deben ser validados.
6. Para intercambiar información sensible utilizar protocolos para cifrar las comunicaciones, y en el caso de almacenamiento la información confidencial debería estar cifrada utilizando algoritmos fuertes y claves robustas.
7. Cualquier funcionalidad, campo, botón o menú nuevo debe agregarse de acuerdo a los requerimientos de diseño. De esta forma se evita tener porciones de código que resultan siendo innecesarias.
8. La información almacenada en dispositivos móviles debería ser la mínima, y más si se trata de contraseñas o datos de sesión. Este tipo de dispositivos son los más propensos a ser que se pierdan y por lo tanto su información puede ser expuestas más fácilmente.
9. Cualquier cambio que se haga debería quedar documentado, esto facilitará modificaciones futuras.
10. Poner más cuidado en los puntos más vulnerables, no hay que olvidar que el nivel máximo de seguridad viene dado por el punto más débil.

# BUENAS PRÁCTICAS 
* Validación de entradas.
* Codificación de salidas.
* Estilo de programación.
* Manejo de Log de Cambios.
* Prácticas Criptográficas.
* Manejo de errores y LOgs.
* Manejo de memoria.
* Estandarización y reutilización de funciones de seguridad.

![image](https://user-images.githubusercontent.com/50559771/140587455-5525507f-7033-454d-8371-8be47f83e225.png)

