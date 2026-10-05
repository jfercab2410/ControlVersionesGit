# 5.- Conceptos básicos: Git / GitHub

## Conceptos Generales

* **Repositorio:** Es como una carpeta en la que se encuentran archivados los ficheros de tu proyecto (código, documentación o ejemplos).
  * **Tipos de repositorios:**
    * **Público:** Visible para todos.
    * **Privado:** Acceso restringido para usuarios específicos.
* **Archivo README:** Contiene instrucciones básicas para moverse en tu repositorio. Suele incluir el nombre del proyecto, descripción/créditos, índice de contenidos, uso del proyecto y licencia.

## Ramas y Copias

* **Rama:** Realmente son copias del contenido de un proyecto.
  * **Rama master:** Contiene el proyecto original.
  * **Rama remota:** Copia del proyecto original en la que se trabaja en paralelo. Es una copia local y *offline* utilizada para avanzar en el proyecto sin que un error afecte al proyecto original.
* **Clone / Fork:** Son instantáneas que hacemos del repositorio.
  * **Clone:** Copia del proyecto original para trabajar en local (*offline*).
  * **Fork:** Copia del proyecto original creada en tu perfil de GitHub para trabajar *online*.

## Operaciones y Flujo de Trabajo

* **Commit:** Registro o "foto" de los cambios realizados (modificar ficheros, añadir líneas, borrar existentes, etc.) que se guarda en la rama local.
* **Push / Pull Request:**
  * **Push:** Envías y "empujas" tus cambios hacia la rama master.
  * **Pull Request:** Solicitud para integrar tus cambios en la rama master, funcionando como una revisión o aportación que se realiza desde la interfaz gráfica.
* **Merge:** Integración de los cambios de una rama remota en una rama master (o viceversa) para actualizar ambas ramas. De remota a master los cambios deben ser aprobados mediante *pull requests*; una vez realizado el *merge*, ambas ramas son idénticas.

## Áreas de Trabajo en Git

Git trabaja con tres áreas diferentes en local:
1. **Working Directory (Área de trabajo):** Directorio en el que estamos trabajando.
2. **Staging Area (Área de preparación):** Lugar donde colocamos los archivos de los que queremos guardar versiones.
3. **Repository (Repositorio):** Donde se almacenan los datos y todos los cambios.
