1.¿Tuviste que modificar calcularTotalNomina() para que incluyera a los comerciales? ¿Por qué no? ¿Qué concepto de POO lo hizo posible?
Respuesta:
No fue necesario modificarlo, porque el método recorre todos los empleados y llama al metodo calcularSalarioTotal(). Gracias al polimorfismo, cada clase utiliza su versión del método. Por eso, el metodo EmpleadoComercial() puede calcular su salario incluyendo la comisión sin modificar el meotodo calcularTotalNomina().

2. ¿Cuántos archivos de la capa modelo modificaste (no creaste)? ¿Qué te dice eso sobre MVC?
Respuesta:
No modifiqué ningún archivo existente de la capa modelo y solamente creé la clase EmpleadoComercial. Ya demuestra que MVC permite separar las responsabilidades del programa y agregar nuevas funciones sin la necesidad de modificar innecesariamente las clases que existen.
