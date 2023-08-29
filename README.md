# Sonarqube - Code analyzer

Como ejemplo, se hará uso de la herramienta [Sonarqube on-cloud](https://www.sonarsource.com/open-source-editions/) y se tendrá que realizar un registro [aquí](https://www.sonarsource.com/products/sonarcloud/signup/). También se hará uso de un [repositorio](https://github.com/sebaez11/carboneros-gastrobar) público en github, el cuál deberá [clonar](https://docs.github.com/es/repositories/creating-and-managing-repositories/cloning-a-repository) en su máquina local y [publicar](https://docs.github.com/es/get-started/quickstart/create-a-repo) en su cuenta de Github, para poder realizar todo el tutorial.

## Pasos

1. **Analizar nuevo proyecto:** Para poder integrar un proyecto de Github con Sonarqube, deberás estar logueado y darle click en el icono de agregar al extremo superior derecho y luego darás click en "Analyze new project".

![crear proyecto](https://lh3.googleusercontent.com/u/3/drive-viewer/AITFw-zJk_HcmI-GXHDs4hNCKDX5wyaO6t7KKWzlKNu6J4RUZiODZVjX71R-NoLmvOI9zjArHcZUW1c-2HbxFokHmQmowl3O_w=w1920-h937)

2. **Agregar repositorio**: Luego, te aparecerá una interfaz cómo esta y tendrás que crear una "Organization" y seleccionar el repositorio que quieres analizar.

![Agregar proyecto](https://lh3.googleusercontent.com/u/3/drive-viewer/AITFw-zypzdlvWNIVXvpPBsxrMFik7fXmHB0i0jx9QltbQ2HG4tzKT3KaiBAgB83q0CrhEcay40hz-BYMQ6kmVM9aUjrPxyLyw=w1920-h937)

**Nota**: Puedes acceder a la pestaña "My projects" y observar que tu proyecto ha sido añadido correctamente. Además, puedes observar todos los proyectos que has agregado en tu cuenta y ver algunas analíticas sobre bugs, vulnerabilidades, code smells y otros errores que Sonarqube encuentre en tu código, cómo lo puede ser fallos en la seguridad.

3. **Seleccionar el proyecto:** Para poder seleccionar el proyecto, deberás ir a la pestaña "My Projects" y visualizarás algo similar a la imagen de abajo. Deberás dar click en el proyecto "carboneros-gastrobar".

![My Projects View](https://lh3.googleusercontent.com/u/3/drive-viewer/AITFw-xIywi2R2KWfeeyXcFn-vWq4VlNmcu_weUzUn3O5uPhhFqE4gd37rxvzsSu96OhxdOz9M7OLiQKqfjplh6ZVMQk8_Lehg=w1920-h937)

4. **Visualizar Métricas:** Los datos que se pueden visualizar son desde la última fecha que se analizó el código, la cantidad de líneas analizadas, bugs, code smells, vulnerabilidades y brechas de seguridad. En cada sección puede dar click y recibir más detalle sobre las líneas de código que tienen fallas.

![](https://lh3.googleusercontent.com/u/3/drive-viewer/AITFw-xRVi6y3egvOw0xdOBESR-uoZ_BjHrojYmaMlleiqqlLvdMIdeeTTm4e8c6xms859N66PCA9RuOp1y_DtQfcRnjdOyEAw=w1920-h937)

¡Ahora, ya estás lista para analizar tus propios proyectos y evitar que los errores de código salgan a producción!

SonarQube se ha establecido como una herramienta esencial en el desarrollo de software, proporcionando análisis profundos y continuos que mejoran la calidad, la seguridad y la eficiencia de las aplicaciones. Al integrar SonarQube en el proceso de desarrollo, los equipos pueden identificar y abordar problemas de manera proactiva, lo que resulta en software más confiable y exitoso. La inversión en herramientas de análisis como SonarQube demuestra ser fundamental en un mundo donde la excelencia en el desarrollo de software es un requisito imprescindible.
