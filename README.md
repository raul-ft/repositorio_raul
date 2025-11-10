# A Game to fork Raul
**Esta es mi version del juego**

Voy a explicar los cambios que he hecho en este juego paso a paso para llegar a mi versión

## pasos

1. Me he creado un repositorio vacio en mi cuenta de GitHub.
![Alt Text](./img/Pasted-image)
2. Entro a Gitkraken, inicio sesion, y pongo mi repositorio vacio, para luego clonar el repositorio de Alvaro en mi repositorio.
![Alt Text](./img/Pasted-image(2))
3. Edito el remoto de mi Gitkraken y pongo mi repositorio.
![Alt Text](./img/Pasted-image(3))
4. Creamos una nueva rama en el juego para hacer nuestros cambios.
![Alt Text](./img/Pasted-image(4))
5. Con el Idea, podemos comenzar a hacer los cambios.
    ```java private final double MIN_RADIUS = 9;
    private final double MAX_RADIUS = 20;
    private final double FALL_SPEED = 9;
    private final double LOST_LINE_Y = 450;
    finalScoreLabel.setText("has ganado estos puntos craack: " + finalScore);
    public static void switchToStartView() throws IOException {
    loadScene("start-view.fxml", 1280, 720);```
    
6. despues de hacer los cambios los añades y realizas un **commit y un push**.
    ![Alt Text](./img/Pasted-image(10))
7. Despues de tener tus cambios en la rama secundaria de tu repositorio en GitHub haces un **pull request** para fusionar tu rama secundaria con la principal.
    ![Alt Text](./img/Pasted-image(12))
8. y asi se nos ve la fusion de la rama:
    ![Alt Text](./img/Pasted-image(11))
