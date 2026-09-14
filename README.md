# portfolio Eleazar López Mahiques

## Portfolio de la pagina de Eleazar

### Arquitectura de despliegue: evento disparador y servicio ejecutor

Un **sistema de despliegue automatizado** se basa en dos componentes principales. El evento disparador es la señal que inicia el pipeline, normalmente generada por acciones en el repositorio como push, pull request, ejecuciones manuales (workflow dispatch) o tareas programadas. Este evento crea el contexto de ejecución y determina qué workflow debe activarse.

El **servicio ejecutor** es el componente que procesa el despliegue. En plataformas como GitHub Actions, este rol lo cumple el runner, que puede ser hospedado por GitHub o autogestionado. El runner recibe el workflow, descarga el código y ejecuta los pasos definidos: compilación, pruebas, empaquetado y despliegue hacia el entorno objetivo.

### Ruta relativa del archivo de definición del workflow dentro del repositorio
.github/workflows/static.yml

### Enlace directo a la URL pública del entorno de producción.
https://eleazar-1.github.io/portfolio/