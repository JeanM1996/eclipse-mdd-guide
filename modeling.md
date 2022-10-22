# Modelamiento y Validación 

Una vez generado nuestro proyecto de Ecore Modeling, podemos comenzar a modelar nuestro dominio. Para ello, se debe seguir los siguientes pasos:

1.  Accedemos al Viewpoint Modeling para generar nuestro dominio
 
![Step1](./imagenes/modeling_step1.jpg)

2. Para generar una entidad debemos seleccionar la opción **Class** del apartado **Classifier** y arrastrarla al diagrama de clases (Panel **Palette**).
![Step2](./imagenes/modeling_step2.jpg)


3. Para cambiar el nombre de la entidad, debemos dar doble click sobre la entidad y escribir el nombre deseado en el apartado **name**.

![Step3](./imagenes/modeling_step3.jpg)

4. Para agregar un atributo a la entidad, debemos seleccionar la entidad y seleccionar la **quinta opción** con lo que se agregara un atributo a la entidad.

![Step4](./imagenes/modeling_step4.jpg)

5. Para definir un nombre al atributo debemos dar doble click sobre el atributo y escribir el nombre deseado en el apartado **name**.

![Step5](./imagenes/modeling_step5.jpg)

6. Para definir un tipo de dato al atributo debemos dar doble click sobre el atributo y seleccionar la opción **...*** ubicada en **EType**

![Step6](./imagenes/modeling_step5.jpg)

7. Se desplegará una ventana con los tipos de datos disponibles, seleccionamos el tipo de dato deseado ** ** y seleccionamos la opción **OK**.

![Step7](./imagenes/modeling_step6.jpg)

8. Para agregar una relación entre entidades en el panel **Palette** seleccionamos la opción **Relation** al seleccionar la **Relation** debemos dar click en la entidad origen y luego en la entidad destino.

![Step8](./imagenes/modeling_step7.jpg)

9. El proceso sigue con la generación de los diversos modelos 
   - En el explorador del proyecto dar doble click en la opción **nameModel.genmodel**, luego dar click derecho sobre la opción nameModel e ir generando en orden secuencial cada una de las opciones que inician con la palabra **Generate**. 
    1. Generate Model Code
    2. Generate Edit Code
    3. Generate Editor Code

![Step9](./imagenes/modeling_step8.jpg)

10. Se nos generaran diversos proyectos con terminanciones **.edit** y **.editor**

![Step10](./imagenes/modeling_step9.jpg)

11. Para validar debemos dar click derecho sobre el proyecto **nameModel.editor** y seleccionar la opción **Run As > Eclipse Application**. Donde se nos desplegará una nueva ventana de Eclipse con el editor de nuestro modelo.

![Step11](./imagenes/modeling_step10.jpg)

12. Creamos un nuevo proyecto general accediendo a la opción **File > New > Project** y seleccionamos la opción **General > Project**. Luego definimos un nombre en la ventana seleccionamos la opción **Finish**.

![Step12](./imagenes/modeling_step11.jpg)

13. Dentro del proyecto creado, creamos un nuevo archivo de tipo **EMF Model** accediendo a la opción **File > New > Other** y seleccionamos la opción **EMF Model Creation Wizard**. Luego definimos un nombre en la ventana seleccionamos la opción **Next**.

![Step13](./imagenes/modeling_step12.jpg)

14. Damos click en **Next**

![Step14](./imagenes/modeling_step13.jpg)

15. Elegimos el modelo que deseamos crear y damos click en **Finish**. Se nos creara en el proyecto la entidad seleccionada

![Step15](./imagenes/modeling_step14.jpg)

16. Para generar la relación damos click derecho sobre la entidad y seleccionamos la opción **New Child > entity**. Validadndo que esta se agrega en nuestro tree

![Step16](./imagenes/modeling_step15.jpg)

17. Definimos los datos para cada atributo en el **panel inferior** en el campo **value**

![Step17](./imagenes/modeling_step16.jpg)







