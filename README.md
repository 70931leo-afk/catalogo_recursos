Catalogo de recursos academicos

Descripcion:
Sistema que posteriormente podría registrar y consultar, libros, sitios web, videos, Artículos y herramientas de software.

Objetivo:
Aplicar de manera autónoma el flujo de preparación, versionamiento y colaboración de un proyecto
utilizando Visual Studio Code, Python, Git y GitHub. En esta práctica no se proporcionan los comandos: cada
instrucción describe una acción y el resultado esperado, y deberás determinar qué comando utilizar,
ejecutarlo y comprobar su resultado.

Estructura general:
catalogo_recursos/
│
├── app/
│ ├── main.py
│ └── configuracion.py
│
├── data/
│ └── recursos.json
│
├── docs/
│ ├── alcance.md
│ ├── criterios.md
│ ├── respuestas.md
│ └── evidencias/
│ ├── evidencia_01.png
│ ├── evidencia_02.png
│ └── ...
│
├── tests/
│ └── test_basico.py
│
├── .gitignore
├── README.md
├── requirements.txt
└── CHANGELOG.md

Tecnologias utilizadas:
- Python
- Visual Studio Code
- Git
- GitHub

Instrucciones para preparar el entorno y dependencias

Crear el entorno virtual

1. Crea un entorno virtual denominado .venv
2. Actívalo.
3. Configura Visual Studio Code para utilizar el intérprete de Python contenido en ese entorno.
4. Comprueba la versión de Python activa.
5. Comprueba que el administrador de paquetes corresponde al entorno virtual.

Instalar dependencias

1. Instala las bibliotecas requests y rich dentro del entorno virtual.
2. Consulta las bibliotecas instaladas.
3. Genera requirements.txt a partir del entorno actual.
4. Abre el archivo y verifica que ambas dependencias se encuentren registradas.

Proximaas mejoras:
Agregar nuevas funciones al sistema tales como buscar recursos por nombre autor o fecha del recurso, organizar recursos por fechas autores y genero, actualizar versiones de libros.

Tipos de recursos:
- Artículos académicos
- Libros
- Documentación técnica
- Cursos
- Tutoriales