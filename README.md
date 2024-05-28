
# A partir de un CRUD de cursos previamente realizado crear otro que obtenga e inserte parseando en su propio objeto:

Servicio formación 
Desarrollar un servicio formación que interaccionará con el servicio de cursos para ofrecer su funcionalidad. 
Los datos que caracterizan una formación serán: 

 curso (texto) 

 asignaturas (numérico entero) 

 precio (numérico decimal) 


El servicio ofrecerá los siguientes recursos: 

· Devuelve la lista de cursos existentes. Como el microservicio de cursos no dispone del dato de asignaturas, se seguirá el siguiente algoritmo: Si un curso tiene una duración igual o superior a 50 horas, se considera que tiene 10 asignaturas, sino, serán 5 asignaturas 

· Alta curso. A partir de los datos de formación recibidos en el cuerpo, se dará de alta el curso a través del microservicio de cursos, siempre que no exista un curso con el mismo nombre, en cuyo caso no se hará nada. La duración del curso se establecerá según la fórmula: asignaturas*10 


## Authors

- [@RaulRodal](https://www.github.com/raulrodal)


## Features

- Creacion de 2 microservicios
- Interoperabilidad entre los mismos
- Mapeo de objetos
