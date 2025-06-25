# clase03-2bim

Gracias a la relacion que existe entre las entidades Estudiante y numero telefonico podemos acceder a la informacion de numeros telefonicos con e.numerotelefonico_set.all
![Captura de pantalla de 2025-06-18 08-09-16](https://github.com/user-attachments/assets/1af4c3c5-3f41-4738-9ff7-1016e14ae888)

### 25 junio 2025


* Al momento de crear un numero de telefono, aunque no sea visible para el usuario por atras esta conectada la vista en django que busca el objeto estudiante y al momento de llenar los datos del nuevo numero de telefono se asocian con ese estudiante, al momento de llenar el formulario nuevo numero telefonico obtenemos el estudiante, que gracias al widget Hidden se esconde el elemento que trae al estudiante para tener una vista m[as limpia del formulario para el usuario, siendo que al estar asociados estudiante y numero telefonico es necesario traer este estudiante.

