<div align="center">

# 🐍 Python Exercises

**De los fundamentos a los algoritmos. Aprender, practicar y mejorar.**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Ejercicios](https://img.shields.io/badge/Ejercicios-133-183A32?style=for-the-badge) ![Enfoque](https://img.shields.io/badge/Enfoque-Pr%C3%A1ctica-6F42C1?style=for-the-badge)

Colección personal de **133 ejercicios de Python** para desarrollar la lógica de programación y aprender mediante la práctica.

[Catálogo de ejercicios](./CATALOGO.md) · [Cómo ejecutar](#-cómo-ejecutar) · [Contenidos](#-contenidos)

</div>

---

## 📖 Acerca del repositorio

Este repositorio reúne ejercicios de programación realizados durante mi proceso de aprendizaje de Python. Incluye desde problemas básicos de consola hasta algoritmos, manejo de datos, archivos, pequeñas simulaciones e integración con librerías externas.

**Es un registro de aprendizaje, no una colección de soluciones verificadas para producción.** Algunos programas pueden conservar errores o requerir una configuración específica.

## 🧠 Contenidos

| Área | Temas |
| :--- | :--- |
| **Fundamentos** | Variables, operadores, conversiones, entrada y salida de datos |
| **Control de flujo** | Condicionales, `for`, `while` y rangos |
| **Funciones y algoritmos** | Recursividad, factoriales, números primos, Collatz y Luhn |
| **Cadenas y colecciones** | Texto, listas, tuplas, diccionarios y conjuntos |
| **Funciones avanzadas** | Generadores, `*args`, excepciones y decoradores |
| **Archivos y formatos** | Lectura, escritura, expresiones regulares, fechas y JSON |
| **Proyectos aplicados** | MySQL, consultas HTTP, SMTP, Pillow, Pygame y juegos |

## 🗂️ Organización

Los scripts se nombran con su identificador original de tres dígitos y un nombre descriptivo en `snake_case`.

```text
python-exercises/
├── README.md
├── CATALOGO.md
├── .gitignore
└── ejercicios/
    ├── 001_cuadrados_en_intervalo.py
    ├── 020_interes_compuesto.py
    ├── 032_secuencia_de_collatz.py
    ├── 064_crud_de_usuarios_mysql.py
    └── ...
```

**[Ver los 133 ejercicios en el catálogo](./CATALOGO.md)**

## ▶️ Cómo ejecutar

Requiere Python 3. Clona el proyecto y ejecuta el script deseado desde la raíz:

```bash
git clone https://github.com/TryNeo/python-exercises.git
cd python-exercises
python ejercicios/032_secuencia_de_collatz.py
```

En algunos sistemas necesitarás escribir `python3` en lugar de `python`. Muchos ejemplos requieren datos por consola mediante `input()`.

Los archivos se ejecutan como scripts independientes; el prefijo numérico conserva el orden original. Para ejercicios que usan rutas relativas, ejecútalos desde `ejercicios/` o ajusta la ruta del archivo de entrada. El archivo de ejemplo `a.txt` está en esa carpeta.

### Dependencias opcionales

La mayoría de los ejercicios utiliza la biblioteca estándar de Python. Otros necesitan paquetes o servicios adicionales:

| Ejercicio | Requisito |
| :--- | :--- |
| [055 - Miniaturas](./ejercicios/055_generar_miniaturas.py) | `Pillow` |
| [064 - CRUD MySQL](./ejercicios/064_crud_de_usuarios_mysql.py) | `mysql-connector-python` y base de datos configurada |
| [065 - Directorio](./ejercicios/065_monitorizar_directorio.py) | `click` |
| [101 - API Pokémon](./ejercicios/101_consulta_api_pokemon.py) | `requests` y acceso a Internet |
| [109 - Reloj](./ejercicios/109_reloj_digital_pygame.py) | `pygame` y entorno gráfico |
| [116 - Correo SMTP](./ejercicios/116_enviar_correo_smtp.py) | Acceso a un servidor SMTP y credenciales propias |

Ejemplo:

```bash
python -m pip install requests
python ejercicios/101_consulta_api_pokemon.py
```

Los scripts no cuentan con una suite de pruebas automatizadas general. Revisa cada archivo antes de ejecutarlo: algunos requieren archivos externos, credenciales o interacción y podrían presentar errores.

## Estado de los ejercicios

Una revisión estática de los 133 scripts detectó errores de sintaxis preexistentes en estos archivos:

| Archivo | Pendiente |
| :--- | :--- |
| [029_concatenar_hola.py](./ejercicios/029_concatenar_hola.py) | Indentación inconsistente |
| [079_clasificacion_por_imc.py](./ejercicios/079_clasificacion_por_imc.py) | Sintaxis inválida |
| [123_posiciones_del_alfabeto.py](./ejercicios/123_posiciones_del_alfabeto.py) | Indentación inesperada |
| [130_suma_de_filas_y_columnas.py](./ejercicios/130_suma_de_filas_y_columnas.py) | Indentación inesperada |

Esta revisión no ejecuta los programas ni verifica sus resultados. Los otros 129 scripts pasan el análisis de sintaxis, pero pueden requerir correcciones de lógica o configuración. El cambio de nombres conserva el contenido original de los ejercicios.

## ⭐ Ejercicios destacados

| N.º | Ejercicio | Concepto |
| :---: | :--- | :--- |
| 003 | [Cálculos geométricos](./ejercicios/003_calculos_geometricos.py) | Matemáticas y funciones |
| 020 | [Interés compuesto](./ejercicios/020_interes_compuesto.py) | Operaciones y porcentajes |
| 032 | [Secuencia de Collatz](./ejercicios/032_secuencia_de_collatz.py) | Bucles y algoritmos |
| 033 | [Algoritmo de Luhn](./ejercicios/033_validacion_luhn.py) | Validación |
| 064 | [CRUD MySQL](./ejercicios/064_crud_de_usuarios_mysql.py) | Base de datos |
| 097 | [Cédula ecuatoriana](./ejercicios/097_validar_cedula_ecuatoriana.py) | Algoritmos de verificación |
| 101 | [PokéAPI](./ejercicios/101_consulta_api_pokemon.py) | HTTP y JSON |
| 122 | [Raíz digital](./ejercicios/122_raiz_digital.py) | Operaciones con dígitos |
| 130 | [Filas y columnas](./ejercicios/130_suma_de_filas_y_columnas.py) | Matrices |

## 📝 Sobre los enunciados

Algunos ejercicios hacen referencia a prácticas de **PyWombat** y desafíos de **Codewars**. Este proyecto contiene mis implementaciones personales como parte de mi formación. Las marcas, los enunciados y sus respectivos derechos pertenecen a sus autores.

---

<div align="center">

**Aprender · Practicar · Mejorar**

</div>
