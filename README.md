# TPespecial

Análisis de calidad del agua en el Río de la Plata:
Indicación paso a paso de como poder obtener el informe y de como lograr correr el archivo tp.ipynb:
    Primer paso: Instalar VSC.
        vamos al siguiente enlace:
            https://code.visualstudio.com/
        Descargamos el archivo correcto para nuestra computadora.
        Procedemos con la instalación.

    Segundo paso: Instalar git en tu computadora. Git es una recurso que nos permite utilizar todas las herramientas útiles para el proyecto.
        entre al siguiente enlace https://git-scm.com/downloads/win
        luego, marque la opción que le corresponda según su computadora para poder descargar el ejecutable de git.
        Una vez que se descargue, abra el archivo y siga los pasos hasta "Choosing the default editor by git" donde debe seleccionar "Visual Studio Code as Git default editor".
        Luego, termine con la istalación hasta finalizarla.

    Tercer paso: Clonar el repositorio en su computadora.
        Primero obtenemos el link del repositorio:
            https://github.com/joegoicoechea24/TPespecial.git
        Luego, abrimos en el explorador de archivos de nuestra computadora la ubicación de donde queremos guardar el proyecto. hacemos click derecho allí y seleccionamos "Git Bash Here".
        Se abre la consola de git, donde escribimos el comando:
            git init
        Luego, para así si tener el proyecto listo en nuestra computadora, ejecutamos el comando git clone de tal manera
            git clone https://github.com/joegoicoechea24/TPespecial.git
        Una vez finalizado se deberá crear la carpeta del proyecto en nuestro directorio local.
        Entramos en la carpeta, y dentro de ella en un espacio en blanco hacemos click derecho nuevamente para seleccionar otra vez "Git Bash Here"
        Se abre de nuevo la consola de git, ahora introducimos el siguiente comando:
            code .
        Para así abrir el proyecto en Visual Studio Code.
    Cuarto paso: Instalar las librerías y los paquetes que fueron utilizados en el proyecto. Estos se encuentran en el requirements.txt
        Para ello primero creamos un ambiente virtual, para no instalar nada directamente en nuestra computadora.
        En la terminal de VSC, dentro del proyecto, realizamos los siguiente:
            escribimos:
                python -m venv venv
            Así creamos un ambiente virtual llamado 'venv' para el proyecto. Luego, lo activamos también por la misma terminal:
                venv\Scripts\activate
        Ahora si, instalamos lo especificado en el archivo requirements.txt también a través de la misma terminal.
            pip install -r requirements.txt

    Listo, ya podemos ejecutar y abrir lo que se encuentra en el proyecto libremente.