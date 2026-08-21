# Cómo contribuir a esta wiki

1. Crea una rama a partir de `main`.
2. Edita o agrega archivos `.md` en `docs/`.
3. Para previsualizar localmente:

   ```bash
   pip install -r requirements.txt
   mkdocs serve
   ```

   Esto levanta un servidor en `http://127.0.0.1:8000`.
4. Abre un Pull Request. Al hacer merge a `main`, el sitio se despliega automáticamente a GitHub Pages.

## Convenciones

- Usa carpetas `usuarios/` y `tecnica/` según a quién va dirigido el contenido.
- Las specs de features van en `tecnica/specs/`, usando la plantilla `_template.md`.
- Las decisiones de arquitectura relevantes se documentan como ADR en `tecnica/decisiones/`.
