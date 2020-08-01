# Multiplicar Console App

Descripción: Esta es una aplicación para generar archivos de tablas de multiplicar.

# Modo de uso de la app
1. Clonar el repositorio [aquí](https://github.com/Andres25b/multiplicar-node)
2. Para instalar las dependencias. Ejecute el siguiente comando:

        npm install

3. Ejecute el siguiente comando para mostrar la tabla de multiplicar que desee.

        node app listar --limite 10 --base 3

        ó

        node app listar -l 30 -b 3

4. Ejecute el siguiente comando si desea crear un archivo .txt, el cual contendrá la multiplicación especificada.

        node app crear --base 2 --limite 15

        ó

        node app crear -b 2 -l 15


