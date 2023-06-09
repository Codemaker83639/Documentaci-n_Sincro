# Documentaci-n_Sincro
### Francisco Ogando (2021-0160)
### Documentación problema del barbero Sincronización
[Link video explicando resolución del problema barbero durmiente](https://miucateciedu-my.sharepoint.com/personal/20210160_miucateci_edu_do/_layouts/15/onedrive.aspx?login_hint=20210160%40miucateci%2Eedu%2Edo&id=%2Fpersonal%2F20210160%5Fmiucateci%5Fedu%5Fdo%2FDocuments%2FSist%20operativo%20II%2FInShot%5F20230328%5F235646128%2Emp4&parent=%2Fpersonal%2F20210160%5Fmiucateci%5Fedu%5Fdo%2FDocuments%2FSist%20operativo%20II)

*En el archivo presente en este repositorio, osea el archivo python barberoDormilon, se encuentra el bloque de código que básicamente simula el funcionamiento de una barbería, donde hay un número de barberos y un número de clientes que llegan en momentos aleatorios. El programa utiliza hilos para simular el comportamiento de los barberos y los clientes.* 

*En el bloque de código, se definen tres clases: "Barbero", "Cliente" y "Main". La clase Barbero representa a un barbero, la clase Cliente representa a un cliente y la clase Main es la clase principal que contiene el código que se ejecuta.* 

*El programa utiliza una cola de espera para controlar el número de clientes que pueden esperar a ser atendidos en la sala de espera, y cada cliente que llega es añadido a esta cola. Cuando un barbero está disponible, toma al próximo cliente en la cola y lo atiende. Si la cola está llena, el cliente se va sin ser atendido.* 

*El programa utiliza métodos de sincronización de hilos, como "wait", "notify" y "notify_all", para asegurar que los barberos y los clientes estén sincronizados y no haya errores en la comunicación entre ellos.* 

*En resumen, el bloque de código utiliza hilos y métodos de sincronización para simular una barbería, donde los clientes llegan y esperan en una cola para ser atendidos por un barbero. El programa funciona de manera concurrente, lo que significa que múltiples hilos están ejecutándose al mismo tiempo.* 

### Muchas Gracias

