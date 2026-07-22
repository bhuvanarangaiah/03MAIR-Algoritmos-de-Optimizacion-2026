# 03MAIR – Algoritmos de Optimización · Trabajo Práctico (Seminario)

**Máster VIU – Universidad Internacional de Valencia**
Repositorio: `bhuvanarangaiah/03MAIR-Algoritmos-de-Optimizacion-2026`

This README documents the instructor's instructions for the *Trabajo Práctico*,
extracted from the assignment PDF (`VIU-03MIAR-Trabajo_Práctico.pdf`).

---

## Overview

Develop, model, and analyze algorithms using different techniques to solve **one**
of the proposed problems. The work is delivered as a Jupyter/Colab notebook
following the provided template, plus a PDF export.

**Weight:** 30% of the course grade.

---

## Problems (choose one)

1. **Sesiones de doblaje** — Coordinate a film's dubbing. Voice actors must be
   present for the takes their characters appear in. Actors are paid per **day**
   they travel to the studio (same rate, regardless of how many takes recorded).
   No more than **6 takes per day**. Plan the sessions per day so total actor
   cost is **minimized**. Data: 10 actors, 30 takes, participation matrix
   (`1` = actor is in the take, `0` = not).
2. **Organizar los horarios de partidos de La Liga** — Assign matches to time
   slots to **maximize audience**, considering team categories, slot
   coefficients, mandatory Friday/Monday matches, and audience penalties for
   overlapping matches.
3. **Combinar cifras y operaciones** — Using digits 1–9 (no zero) and the four
   operators `+ - * /`, combined alternately **without repeating** any digit or
   operator, reach a target value. Determine the min/max reachable values and
   which integers in between are reachable.

> **This repository solves Problem 1 — Sesiones de doblaje.**

---

## Deliverable

- A **Jupyter Notebook** hosted on **GitHub** (in the `SEMINARIO` folder),
  based on the official template:
  <https://colab.research.google.com/drive/1NVFHsnmrE-wFLX8y1SC3tKlh2et5FOz8>
- A **PDF export** of the completed notebook (as in the guided activities).
- Notebook header must include: name, GitHub URL, chosen problem, and the
  problem statement (copiar enunciado).

---

## Required questions

The notebook must answer 13 questions. **6 are mandatory (`*`)** and guarantee
up to 7/10; the **7 optional** ones add up to 9/10.

1. `(*)` ¿Cuántas posibilidades hay sin tener en cuenta las restricciones?
2. ¿Cuántas posibilidades hay teniendo en cuenta todas las restricciones?
3. `(*)` ¿Cuál es la estructura de datos que mejor se adapta al problema?
   Argumentar (es posible elegir una al principio y ver la necesidad de cambiar).
4. `(*)` ¿Cuál es la función objetivo?
5. `(*)` ¿Es un problema de maximización o minimización?
6. Diseña un algoritmo para resolver el problema por fuerza bruta.
7. Calcula la complejidad del algoritmo por fuerza bruta.
8. `(*)` Diseña un algoritmo que mejore la complejidad del algoritmo por fuerza
   bruta. Argumenta por qué mejora.
9. `(*)` Calcula la complejidad del algoritmo mejorado.
10. Según el problema (y tenga sentido), diseña un juego de datos de entrada
    aleatorios.
11. Aplica el algoritmo al juego de datos generado.
12. Enumera las referencias utilizadas.
13. Describe brevemente cómo es posible avanzar en el estudio del problema
    (variaciones del problema y/o variaciones al alza del tamaño).

Each answer combines **text** (explanation) and **Python code**.

---

## Repository contents

| File | Description |
|------|-------------|
| `Seminario_Algoritmos.ipynb` | Completed notebook solving Problem 1 (Sesiones de doblaje). |
| `README.md` | This file — assignment instructions. |

---

## Instructor

`jcamacho@professor.universidadviu.com`
