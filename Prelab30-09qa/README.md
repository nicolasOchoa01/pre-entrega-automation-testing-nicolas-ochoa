# Pre-Entrega de Proyecto: Automatización de Pruebas E2E en Saucedemo

Este repositorio contiene la solución de la pre-entrega de automatización de pruebas para el sitio web [SauceDemo](https://www.saucedemo.com/), utilizando **Python**, **Selenium WebDriver** y **Pytest**.

El objetivo del proyecto es validar flujos críticos como el proceso de inicio de sesión (*Login*), verificación del catálogo de productos y la interacción con el carrito de compras.

## Tecnologías Utilizadas

* **Lenguaje:** Python 3.x
* **Framework de Pruebas:** Pytest
* **Automatización Web:** Selenium WebDriver
* **Gestor de Drivers:** WebDriver Manager
* **Reportes:** pytest-html
* **Control de Versiones:** Git y GitHub

## Requisitos Previos e Instalación

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/nicolasOchoa01/pre-entrega-automation-testing-nicolas-ochoa.git
   cd pre-entrega-automation-testing-nicolas-ochoa
   ```

2. **Crear y activar un entorno virtual (Recomendado):**
   * En Windows:
     ```bash
     python -m venv venv
     .\venv\Scripts\activate
     ```
   * En macOS/Linux:
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

3. **Instalar dependencias necesarias:**
   ```bash
   pip install selenium pytest pytest-html webdriver-manager
   ```

## Ejecución de las Pruebas

Para ejecutar el conjunto de pruebas unitarias y generar el reporte HTML de ejecución, ejecuta el siguiente comando en la raíz del proyecto:

```bash
pytest -v --html=reports/reporte.html --self-contained-html
```