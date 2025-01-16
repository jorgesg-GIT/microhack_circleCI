# microhack_circleCI

# 021 CircleCI 1
Objetivo
Iniciarse en CircleCI configurando un pipeline básico y realizando un despliegue sencillo de una aplicación.
Desarrollo de tu primer pipeline con CircleCI
Como CTO de TuEmpresa, buscas una herramienta de integración continua que sea fácil de usar, rentable y eficiente para gestionar los pipelines de tus aplicaciones. Decides hacer una prueba de concepto utilizando CircleCI, aprovechando su versión gratuita para configurarlo y desplegar una aplicación.
Implementación
Crea un repositorio en GitHub:
Contendrá un archivo config.yml (almacenado en .circleci/) donde desarrollarás tu pipeline.
Añade un archivo index.html o un simple archivo de texto que será el contenido a desplegar.
Configura el pipeline básico:
Tu pipeline debe incluir al menos los siguientes steps:
Checkout del código desde el repositorio.
Ejecución de un script simple (puede ser un archivo test.sh que contenga echo "Ejecutando tests").
Despliegue del contenido a un servidor estático local o simulado (puedes usar un servidor web sencillo como Python http.server).
Prueba la configuración:
Conecta tu repositorio con CircleCI.
Ejecuta el pipeline y verifica que los pasos funcionan correctamente.
Tips
Usa la versión gratuita de CircleCI, que permite ejecutar pipelines sin coste inicial.
Documentación útil:
https://circleci.com/docs/getting-started/
https://circleci.com/docs/configuration-reference/
Como opcional: Implementa paralelismo configurando un job que ejecute dos scripts diferentes en paralelo (por ejemplo, test1.sh y test2.sh).
