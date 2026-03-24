1. ¿Qué tipo de relación existe entre "Vehículo" y "Camioneta"? ¿Es herencia, agregación o asociación?
Es herencia Esto porque la Camioneta es un Vehículo. Esto significa que hereda todo lo esta que son las placas, la marca y el modelo solo para ponerle sus características especiales

2. ¿Cómo se representa la restricción de que un cliente solo puede alquilar un máximo de tres vehículos?
Lo más fácil es con la multiplicidad. En la línea que une al Cliente con el Alquiler, en lugar de un asterisco, use el 0..3. 
3. ¿Qué modificadores de acceso serían adecuados para los atributos de cada clase?
Lo ideal es aplicar encapsulamiento:

Privado (-): Para casi todos los atributos . Nadie los toca desde afuera si no es por un método.

Público (+): Para los métodos como , porque son las funciones que el sistema tiene que llamar.