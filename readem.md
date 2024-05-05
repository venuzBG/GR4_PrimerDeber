# Clase01: 30 Abril del 2024
## Comandos visual code

- **Windows**: ==CTRL+SHIFT+P== :  Abre el panel de control que tiene VSC.
- **Windows**: ==CTRL+P== : Abre panel para cambiar de diferente archivo que tengas en tu carpeta.
- **Windows**: ==CTRL+B== : La pestaña que te muestra tus archivos.
- **Windows**: ==CTRL+D== : Te permite cambiar el nombre de varias palabras/variables del mismo nombre.
- **Windows**: ==CTRL+F== : Te ayuda a buscar palbara/variable en el codigo.
- **windows**: ==CTRL+S== : Es la opcion para guardar.
- **Windows**: ==AlT + or -== : Si esta abierto pestañas te permite cambiar a otra.
- **Windows**: ==AlT + up or down== :  Mueve toda la linea de acuerdo a la flecha.

- **windows**: ==SHIFT+ALT+ up or down== : Copia toda la linea a la siguiente.
- **windows**: ==SHIFT+ALT+A== : Pone para comentar una linea.
- **windows**: ==CTRL+K+C== : Pondra toda la linea como comentario.
- **windows**: ==CTRL+T== : Permite mostrar todos los simbolos.
- **windows**: ==CTRL+SPACE== : Te ayuda autocompletar una palabra.
- **windows**: ==CTRL+x== :Borra una linea.
- **windows**: ==ClICK en el archivo + F2== : Cambia el normbre del archivo.

## Comandos de la terminal
- pwd <!-- me permite saber en que directorio estoy trabajando -->
- touch <!-- para crear un archivo -->
Ej: touch readme.md
- code <!-- para crear archivos -->
Ej: code readme.md
- touch "" >> texto2.txt <!-- dentro de las comillas escribo lo que quiero que se escriba al crear el archivo -->
EJ: touch "hola mundo" >> texto2.txt

### Recomendaciones de otros comandos que tiene markdown

- Si queremos enumerar hacemos lo siguiente:
    1. Linea 1  
    2. Linea 2
        1. Linea 1
        2. linea 2
    3. Linea 3
- Si queremos poner otro signo para ideas hacemos lo siguiente:
    + Linea 1  
    + Linea 2
        + Linea 1
        + linea 2
    + Linea 3

# Clase03: 31 Abril del 2024

- markdown (para convertir a pdf mi markdown):
    - Windows: CTRL+SHIFT+P 
    - despues busco la opcion de "markdown export pdf"
    - se crea automaticamente un archivo pdf de tu markdown 
    
- t * palabra o texto * <!-- entre los asteriscos la palbra o el texto estara en cursiva -->
- ** palabra o texto ** <!-- entre los dos signos nos permite poner el todo un texto o una palabra en negrita -->
- *** palabra o texto *** <!-- cursiva y en negrita -->
- windows: ALT+9+6 (`) or windows: ALT+1+2+6 (~) <!-- crear este signo para lo siguiente -->
    -   Nos permite poner una parte del codigo para analizar despues de (```) tenemos que poner el lenguaje de progrmacion
        - Ejemplos:
            1. 
                ```java
                public int sumar(){
                int i=10;
                }
                ```
            2. 
                 ```java
                public clas Hola{
                /* clase principal */
                    public class void main{
                        System.out.println();   
                    }
                }
                ```
- Para hacer cuadros:

|Columna 1 | columna 2 |
|---------|----------|
|    A    |     B    |
|    C    |     D    |

- Comandos de git
    1. choco <!-- revisar en el internet -->
    2. git init <!-- Crea un carpeta oculta en tu carpeta de proyecto  y va aparecer tus archivo con "U"-->
    3. git status <!-- te muestra que archivos has guardado --> (rojo: no esta guardado and verde: esta guardado)
    4. git commit <!-- para guradar el proyecto -->
    5. git checkout -b main
    6. git branch
    7. git push <!-- subo todo al git -->
    8. git pull <!-- nos ayuda a traer los cambios hechos en la nube  -->
    9. git clone url <!-- baja el archivo de algun proyecto -->
    10. git ignore <!-- dentro del archivo puedes poner archivos q va ignorar o no va a guardar -->   