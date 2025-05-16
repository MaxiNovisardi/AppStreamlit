# Contribuir

## Flujo de Trabajo

El proceso que seguiremos implica utilizar la rama `main` como la rama de producción del proyecto. Cualquier nueva funcionalidad o corrección de errores se realizará creando nuevas ramas.

Para incorporar una función en la rama `main`, simplemente se crea un "PR" (Pull Request), que deberá ser aprobado por algún colaborador. Cualquier colaborador puede hacerlo o, si no requiere revisión, puede ser aceptado por quien esté incluyendo la funcionalidad.

Es crucial que el nombre de las ramas creadas sea lo más descriptivo posible. Por ejemplo, si trabajamos en una nueva funcionalidad relacionada con la API, la rama se debe llamar como referencia a la funcionalidad en cuestión. En el caso de tratarse de la corrección de un error en el código de la API, la llamaremos `fix-api`.

Además, se contarán con ramas específicas para la documentación del proyecto denominada `docs`. Esta rama será utilizada para registrar toda la documentación, ya sea de la carpeta `docs` o el mismo `README.md`.

## Pasos para contribuir

1. Clonar el repositorio:

   ```bash
   git clone <url-del-repositorio>
   ```

2. Crear una nueva rama a partir de main para la nueva función:

   ```bash
   git checkout -b <nombre-de-la-nueva-rama>
   ```

3. Publicar la rama en el repositorio remoto:

   ```bash
   git push --set-upstream origin <nombre-de-la-nueva-rama>
   ```

4. Realizar commits con los cambios:

   ```bash
   git commit -m 'Add some AmazingFeature'
   ```

5. Hacer push a la rama:

   ```bash
   git push origin <nombre-de-la-nueva-rama>
   ```

6. Abrir un Pull Request dirigido a la rama main.
