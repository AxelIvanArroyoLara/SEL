# project2-teamKarkerkarkurkur

Repositorio del proyecto **SEL-MAIN**.  
Este README documenta el funcionamiento de la calculadora de **Eliminación de Gauss–Jordan**, describe cada archivo brevemente.

---

## Miembros del equipo

| Integrante     | Rol            |
|----------------|----------------|
| Ángel García   | Interfaz       |
| Bruno Tarango  | Gauss–Jordan   |
| Iván Arroyo    | Comprobaciones |

---

## 🌐 Demo (abrir el programa)

> **No se requiere instalación.**  
> Abre la aplicación directamente en tu navegador:
>
> 👉 https://illustrious-rabanadas-79a5c5.netlify.app/

---

## 📁 Estructura del repositorio

SEL-MAIN/
└─ project2-teamKarkerkarkurkur/
├─ index.html
├─ project2-teamKarkerkarkurkur.py
└─ README.md (este archivo)

---

## ▶️ Cómo abrir/usar

- **Opción recomendada (online):**  
  Abre **https://dainty-platypus-bfb8e4.netlify.app/**
- **Opción local (para desarrollo):**
  1. Clona el repo.
  2. Abre `index.html` en tu navegador (doble clic o con *Live Server*).
  3. Si deseas probar el script de Python localmente:
     ```bash
     python project2-teamKarkerkarkurkur.py
     ```
     *(solo si ese script expone CLI; de lo contrario, ver su sección más abajo).*

---

## 🧠 ¿Qué hace cada archivo? (resumen)

- **index.html**  
  Página principal, contiene HTML, estilos base y **toda la lógica JS embebida** para:
  - generar la matriz aumentada `[A|b]`,
  - calcular el **determinante** de `A`,
  - reducir con **Gauss–Jordan** a **RREF**,
  - **analizar soluciones** (única / infinitas / inconsistente), rango y base del núcleo.

- **project2-teamKarkerkarkurkur.py**  
  Implementación en **NumPy** de la misma idea:
  - Gauss–Jordan sobre matriz aumentada, limpieza numérica, impresión de estados,
  - determinante con `np.linalg.det` (con tolerancia),
  - análisis de solución desde la RREF (rango, solución única/infinitas/inconsistente, base del núcleo),
  - `main()` con ejemplo de uso y verificación.


---
