# ciencia-de-datos-

taller #2 del curso que voy a editar.

\# Actividad 2: Manipulación de Git y GitHub



> Repositorio de la Actividad 2 del curso de Git y GitHub, donde practico el control de versiones y el trabajo colaborativo.



!\[Git](https://img.shields.io/badge/Git-F05032?style=flat\&logo=git\&logoColor=white)

!\[GitHub](https://img.shields.io/badge/GitHub-181717?style=flat\&logo=github\&logoColor=white)

!\[Estado](https://img.shields.io/badge/estado-en%20progreso-yellow)



\## Tabla de contenido



\- \[Descripción](#descripción)

\- \[Objetivos](#objetivos)

\- \[Requisitos previos](#requisitos-previos)

\- \[Instalación y configuración](#instalación-y-configuración)

\- \[Estructura del repositorio](#estructura-del-repositorio)

\- \[Comandos practicados](#comandos-practicados)

\- \[Flujo de trabajo](#flujo-de-trabajo)

\- \[Aprendizajes](#aprendizajes)

\- \[Autor](#autor)



\## Descripción



Este repositorio contiene el desarrollo de la \*\*Actividad 2\*\* del curso, cuyo propósito es aprender a manipular \*\*Git\*\* (control de versiones local) y \*\*GitHub\*\* (plataforma para alojar y colaborar en repositorios).



Aquí documento el paso a paso de lo que voy realizando: crear commits, trabajar con ramas, sincronizar con el repositorio remoto y más.



\## Objetivos



\- Entender qué es el control de versiones y por qué es útil.

\- Crear y configurar un repositorio local y vincularlo con GitHub.

\- Practicar el ciclo básico: `add`, `commit`, `push`, `pull`.

\- Trabajar con ramas (`branch`) y fusionarlas (`merge`).

\- Escribir mensajes de commit claros y una documentación útil.



\## Requisitos previos



\- \[Git](https://git-scm.com/downloads) instalado.

\- Una cuenta en \[GitHub](https://github.com/).

\- Un editor de código (por ejemplo, VS Code).



Verifica tu instalación de Git:



```bash

git --version

```



\## Instalación y configuración



1\. \*\*Configura tu identidad en Git\*\* (solo la primera vez):



&#x20;  ```bash

&#x20;  git config --global user.name "Tu Nombre"

&#x20;  git config --global user.email "tu-correo@ejemplo.com"

&#x20;  ```



2\. \*\*Clona este repositorio:\*\*



&#x20;  ```bash

&#x20;  git clone https://github.com/TU-USUARIO/NOMBRE-DEL-REPO.git

&#x20;  cd NOMBRE-DEL-REPO

&#x20;  ```



\## Estructura del repositorio



```text

.

├── README.md        # Documentación del proyecto

└── ...              # Archivos de la actividad

```



> Actualiza esta sección a medida que agregues archivos y carpetas.



\## Comandos practicados



| Comando | Para qué sirve |

| --- | --- |

| `git init` | Inicializa un repositorio local |

| `git status` | Muestra el estado de los archivos |

| `git add <archivo>` | Agrega cambios al área de preparación |

| `git commit -m "mensaje"` | Guarda los cambios en el historial |

| `git log --oneline` | Muestra el historial resumido |

| `git branch` | Lista o crea ramas |

| `git checkout -b <rama>` | Crea una rama y se cambia a ella |

| `git merge <rama>` | Fusiona una rama en la actual |

| `git remote add origin <url>` | Vincula el repositorio local con GitHub |

| `git push origin <rama>` | Sube los cambios a GitHub |

| `git pull` | Descarga y fusiona cambios del remoto |

| `git clone <url>` | Copia un repositorio remoto |



\## Flujo de trabajo



```bash

\# 1. Revisar el estado

git status



\# 2. Agregar los cambios

git add .



\# 3. Guardar con un mensaje descriptivo

git commit -m "Agrega descripción de la actividad en el README"



\# 4. Subir a GitHub

git push origin main

```



\### Convención de mensajes de commit



Uso mensajes cortos, en presente y que expliquen \*\*qué\*\* se hizo:



\- `Agrega README inicial`

\- `Corrige error en la sección de instalación`

\- `Actualiza estructura del repositorio`



\## Aprendizajes



\- \_Escribe aquí lo que aprendiste, por ejemplo: la diferencia entre `git add` y `git commit`.\_

\- \_Dificultades que encontraste y cómo las resolviste.\_

\- \_Qué te gustaría practicar después.\_



\## Autor



\*\*Tu Nombre\*\*

\- GitHub: \[@TU-USUARIO](https://github.com/TU-USUARIO)

\- Curso: \_Nombre del curso\_ · Actividad 2

