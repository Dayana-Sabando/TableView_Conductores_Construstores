## TableView de conductores y constructores
### Introducción 
El código presentado consiste en una aplicación JavaFX que muestra los resultados de los constructores de Fórmula 1 para un año específico.


![Captura de pantalla 2024-07-09 151301](https://github.com/Dayana-Sabando/TableView_Conductores_Construstores/assets/168872451/b5deb9b5-57ac-480c-9d59-ec8433832601)




### Desarrollo 
Este código utiliza un `ComboBox` para la selección del año y un `TableView` para la visualización de los datos, la aplicación permite a los usuarios consultar las estadísticas de los constructores, tales como nombre, victorias, puntos totales y clasificación. La clase principal `Main`, que extiende `Application`, se encarga de configurar y mostrar la interfaz de usuario, así como de actualizar los datos mostrados en el `TableView` mediante el método `updateTable`. Los datos se obtienen de un repositorio de constructores (`ConstructorsRepository`), el cual interactúa con una base de datos PostgreSQL. La clase `Constructors`, en el paquete `demo_jdbc.models`, define los atributos y métodos necesarios para manejar la información de los constructores.



![Captura de pantalla 2024-07-09 151318](https://github.com/Dayana-Sabando/TableView_Conductores_Construstores/assets/168872451/3ac92761-8ecc-45f4-ac05-d49b725d9cd5)






![Captura de pantalla 2024-07-09 152844](https://github.com/Dayana-Sabando/TableView_Conductores_Construstores/assets/168872451/c06daec8-3262-44b9-a685-e8ccd0f0956d)




### Conclusión 
Este proyecto facilita la consulta y visualización de datos de Fórmula 1, proporcionando una herramienta útil para los aficionados y analistas del deporte que desean buscar información de puntajes de manera ordenada. 
