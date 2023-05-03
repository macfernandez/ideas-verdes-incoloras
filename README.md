# Ideas verdes incoloras

Repositorio con recursos relacionados a temáticas de NLP.

<details>
<summary><b>Intrucciones para el uso de este repo</b></summary>
<br>

1. Clonar el repositorio;

    ```bash
    git clone https://github.com/macfernandez/ideas-verdes-incoloras.git
    ```

2. Ubicarse dentro del repositorio:

    ```bash
    cd ideas-verdes-incoloras
    ```

3. Moverse a la carpeta deseada:

    ```bash
    cd <topic-name>
    ```

4. Crear un entorno:

    ```bash
    python3 -m venv venv
    ```

5. Activar el entorno e instalar las dependencias necesarias:

    ```bash
    source venv/bin/activate
    pip intall -r requirements.text
    ```

</details>

<details>
<summary><b>Intrucciones para colaborar con este repo</b></summary>
<br>

1. Clonar el repositorio;

    ```bash
    git clone https://github.com/macfernandez/ideas-verdes-incoloras.git
    ```

2. Ubicarse dentro del repositorio:

    ```bash
    cd ideas-verdes-incoloras
    ```

3. Crear una rama con un nombre medianamente descriptivo. Para separar palabras, utilizar guiones medios (`-`):

    ```bash
    git checkout -b <branch-name>
    ```

4. Si se desea colaborar con un tópico ya existente, pasar al paso 4.

    Si el tópico, en cambio, todavía no ha sido abordado, crear una carpeta con un nombre descriptivo para alojar los recursos:

    ```bash
    mkdir <topic-name>
    ```

    El nombre no debe contener espacios y, si la temática se compone de más de una palabra, estas pueden ser separadas por un guión medio (`-`).

5. Moverse a la carpeta con cuyo tópico se desea contribuir:

    ```bash
    cd <topic-name>
    ```

6. Crear un entorno:

    ```bash
    python3 -m venv venv
    ```

7. Activas el entorno.

    ```bash
    source venv/bin/activate
    ```

    Si existe un archivo `requirements.txt`, instalar las dependencias allí indicadas. Si la contribución lo requiere, agregar en este archivo las librerías adicionales:

    ```bash
    pip install -r requirements.txt
    ```

    Si este archivo no existe, crearlo y agregar las dependencias necesarias.

8. Una vez que se agregó todo el código deseado, realizar la PR correspondiente desde la interfaz de GitHub.

</details>
