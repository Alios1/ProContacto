
# Evaluación Practica



## Ejercicio 2

**1.	¿Qué es un servidor HTTP?**   

Es el software que utiliza el servidor para comprender direcciones URLs y los protocolos de transmisión (HTTP).

**2.	¿Qué son los verbos HTTP? Mencionar los más conocidos**
- POST
- DELETE
- HEAD
- PATCH
- PUT

**3.	¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?**

- **Request:** Es el resultado de un GET, y te regresa o recupera la información de la dirección especificada.
- **Response:** Es el mensaje respuesta que envía el servidor despues de un request (GET).
- **Header:** Es la información que se manda en un request o un response sobre los datos solicitados y el usuario.
    

**4.	¿Qué es un queryString? (En el contexto de una url)**   
El Query String en un URL es la parte donde viene la información o datos a transimitir a la aplicación web.

**5.	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?**   
Son los codigos numéricos que devuleve el servidor de acuerdo al estado de solicitud de un HTTP.    Existen valores de **errores**, **redireccionamiento** y de **respuesta**.


**6.	¿Cómo se envía la data en un Get y cómo en un POST?**   
- **GET:** a traves del Query String anexado en un URL
- **POST:** en un HTML para cambiar lo que hay en el servidor 

**7.	¿Qué verbo http utiliza el navegador cuando accedemos a una página?**   
    
    GET

**8.	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.**    
Los 2 son formatos utilizados para la tranferencia de datos con funcionalidades y complejidades diferentes.

Ejemplo datos objeto empleado JSON

    {
    "empleado": 
    [ 
	
     { 
        "numID":"001", 
        "nombre": "Alejandro", 
        "apellidoP": "Bautista"
        "apellidoM": "Palacios" 
     }
    ]   
    }

Ejemplo datos empleado XML

    <?xml version="1.0" encoding="UTF-8" ?>
    <root>
        <empleado>
            <numID>001</numID>
            <nombre>Alejandro</nombre>
            <apellidoP>Bautista</apellidoP>
            <apellidoM>Palacios</apellidoM>
        </empleado>
    </root>

**9.	Explicar brevemente el estándar SOAP**  
Es el protocolo que permite la comunicación entre dos aplicaciones en diferentes lenguajes, utilizando XML.

**10.	Explicar brevemente el estándar REST Full** 
Es una interfaz basada en REST; es una API que utiliza la arquitectura REST.

**11.	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?**




## Ejercicio 3

**1.	Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json** 
#### Screenshot

![Screenshot1](images/C1.png)


**2.	Realizar un request POST a la URL anterior, y con body:
Tip: (Marcar la opción “raw” como body)**

![Screenshot1](images/C2.png)

**3.	Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json**

![Screenshot1](images/C3.png)

**¿Qué diferencias se observan entre las llamadas el punto 1 y 3?**     
Se agrego el correo con mi nombre el momento de mandar el POST en el paso 2.
