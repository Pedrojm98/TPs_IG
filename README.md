Este proyecto en Java simula una concesionaria de vehículos, mostrando una lista de
autos y motos con sus respectivas descripciones.

La aplicación imprime en consola:
- El vehículo más caro.
- El vehículo más barato.
- El vehículo cuyo modelo contiene la letra "Y".
- Listados ordenados por precio (de mayor a menor) y por orden natural (marca, modelo, precio).

 Estructura del Proyecto:
- Vehiculo.java: clase abstracta base para todos los vehículos.
- Auto.java: representa un automóvil (incluye número de puertas).
- Moto.java: representa una motocicleta (incluye cilindrada).
- MetodoConcesionaria.java: contiene la lógica principal del programa (carga, ordenamientos, búsquedas).
- TestConcesionaria.java: contiene el método "main", desde donde se ejecuta la aplicación.

 Herramientas Utilizadas:
- Java 17 (funciona también con versiones anteriores compatibles)
- Spring Boot como base del proyecto
- Maven para la gestión de dependencias y ejecución
- Lombok para simplificar el código (anotaciones como @Getter, @AllArgsConstructor, @ToString)
