# Procesamiento de Imágenes I – Trabajos Prácticos (TUIA)

Repositorio académico que reúne los trabajos prácticos de la materia **Procesamiento de Imágenes I** de la **Tecnicatura Universitaria en Inteligencia Artificial (TUIA)**.

Incluye scripts, insumos (imágenes y videos) y documentación asociada a cada trabajo práctico, organizados de forma clara para facilitar su ejecución, análisis y evaluación académica.

---

## Objetivos

* Aplicar técnicas fundamentales de procesamiento de imágenes utilizando Python.
* Desarrollar soluciones correctas y eficientes a los ejercicios propuestos en cada trabajo práctico.
* Documentar los procedimientos y resultados obtenidos.
* Consolidar buenas prácticas de organización del código y reproducibilidad.

---

## Estructura del repositorio

* **TP1/**: ejercicios, insumos e informe del Trabajo Práctico 1.
* **TP2/**: ejercicios, imágenes de prueba e informe del Trabajo Práctico 2.
* **TP3/**: ejercicios, videos de prueba e informe del Trabajo Práctico 3.
* **unidad_1...unidad_6/**: materiales correspondientes a las distintas unidades de la cursada.

---

## Requisitos

* **Python 3.9 o superior**
* Dependencias listadas en `requirements.txt`:

  * `opencv-python`
  * `numpy`
  * `matplotlib`
  * `roipoly`

---

## Instalación y configuración

1. Clonar el repositorio.
2. (Opcional) Crear y activar un entorno virtual:

```bash
python -m venv .venv
source .venv/bin/activate  # Linux / Mac
.venv\\Scripts\\activate     # Windows
```

3. Instalar dependencias:

```bash
pip install -r requirements.txt
```

---

## Uso

Ejecutar los scripts desde la raíz del repositorio. Algunos ejemplos:

```bash
python TP1/Ejercicio1.py
python TP2/Ejercicio2.py
python TP3/ejercicio1.py
```

**Nota:** algunos ejercicios requieren archivos de imagen o video que ya se encuentran dentro de cada carpeta de TP.

Por ejemplo, en **TP3**, el archivo `ejercicio1.py` utiliza los videos `ruta_1.mp4` y `ruta_2.mp4`, ubicados en la carpeta `TP3/`.

---

## Créditos

Trabajo realizado por **Rodríguez, Barros, Texier y Masciangelo** para la cátedra de **Procesamiento de Imágenes I** (TUIA).
