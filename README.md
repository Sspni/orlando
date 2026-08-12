# Birthday Code Card

Una tarjeta de cumpleaños para un profesor de inglés programador, con estilo de terminal y un mensaje en inglés.

## Uso rápido

Abre `birthday_code_card.html` en el navegador. Para compartirla como PDF, presiona `Ctrl + P` y elige **Guardar como PDF**.

## Personalizar

En `birthday_code_card.py`, cambia estas variables:

```python
TEACHER = "Teacher"
STUDENT = "Nicolás Valencia"
GRADE = "Grade 11"
```

Después ejecuta:

```bash
python birthday_code_card.py
```

El programa crea el archivo HTML. Si instalas las dependencias, también creará un PDF:

```bash
pip install -r requirements.txt
python birthday_code_card.py
```

> En Windows, WeasyPrint puede requerir componentes adicionales. Si ocurre, usa la opción de imprimir desde el navegador: funciona sin instalar nada.
