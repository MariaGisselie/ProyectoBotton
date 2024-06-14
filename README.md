# Proyecto Diseño de formulario en JavaFx
IMAGEN 
![image](https://github.com/MariaGisselie/ProyectoBotton/assets/169214799/fadf5a10-2a06-4c19-bb13-02ab3cc93f42)
# Botón
Un botón en JavaFX es un control de interfaz de usuario que permite a los usuarios interactuar con una aplicación. Al hacer clic en un botón, se puede desencadenar una acción, como abrir una nueva ventana, mostrar un mensaje o ejecutar una función.

    Button button = new Button("Button");   
# Botón de activación
Un ToggleButton en JavaFX es un control de interfaz de usuario que permite a los usuarios seleccionar o deseleccionar una opción, similar a una casilla de verificación. Por lo general, se parece a un botón con una etiqueta de texto y un estado asociado, ya sea seleccionado o no seleccionado. A diferencia de un botón normal, un ToggleButton mantiene su estado hasta que el usuario lo activa explícitamente o mediante programación.

    ToggleButton toggleButton = new ToggleButton("ToggleButton");
# Etiqueta
Una etiqueta en JavaFX es un control de texto no editable que se utiliza para mostrar un breve fragmento de texto o una imagen dentro de una aplicación JavaFX. Es un elemento básico de la interfaz de usuario que sirve para presentar información al usuario.

   Label label = new Label("Label");
# Indicador de progreso
Un ProgressIndicator en JavaFX es un control de interfaz de usuario que representa visualmente el progreso de una tarea u operación. Es un indicador circular que se llena de color a medida que avanza el progreso, brindando a los usuarios una señal visual sobre el estado de un proceso de larga duración.

     ProgressIndicator ProgressIndicator = new ProgressIndicator(0.49);
# control deslizante
Un control deslizante en JavaFX es un control de interfaz de usuario que permite a los usuarios seleccionar un valor numérico de un rango continuo. Por lo general, consta de una pista y un pulgar que se puede arrastrar y que el usuario puede mover para indicar el valor deseado. Los controles deslizantes se usan combinados para configuraciones, ajustes y entrada dentro de las aplicaciones.

     Slider slider = new Slider(0, 100, 50);
