# Curso de Capacitación en Infraestructura Computacional para Finanzas Cuantitativas

Repositorio del curso. Aquí practicas el flujo de trabajo con Git y GitHub que se usa en equipos reales: **clonar, crear una rama, hacer un commit, enviarlo con push y abrir un pull request**.

**Docente:** Claudio De Jesús · claudio.dejesus@pucp.edu.pe

## Qué hay en este repositorio

| Carpeta | Para qué sirve |
|---|---|
| `notebooks/` | Cuadernos de Colab del curso (guía de GitHub, mini reto de entornos y ejercicio de costos en la nube) |
| `entornos/` | Aquí subes **tu** `requirements.txt` con tu apellido |
| `cuadernos/` | Aquí subes tu cuaderno si usas el atajo de Colab: *Archivo → Guardar una copia en GitHub* |

## Tu primera contribución

1. Abre `notebooks/Guia_GitHub_Colab.ipynb` en Colab y sigue los pasos.
2. Crea tu rama con tu apellido: `apellido-requirements`.
3. Genera tu archivo `entornos/requirements_apellido.txt` (una librería por línea, con versión exacta).
4. Haz tu commit y envíalo con `git push`.
5. En GitHub, abre un **pull request** desde tu rama hacia `main`.
6. El docente lo revisa y lo incorpora (*merge*).

## Reglas

- Un solo archivo por estudiante en `entornos/`, con tu apellido en el nombre.
- **Nunca** subas claves, tokens ni contraseñas.
- **Nunca** subas datos reales de clientes. Los datos del curso son ficticios.
- No trabajes directamente en `main`: todo cambio entra por pull request.

## Si algo falla

Revisa la tabla de errores al final del cuaderno `Guia_GitHub_Colab.ipynb` o escribe al docente.
