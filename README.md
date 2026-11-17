# TP Integrador — Control de Sistemas 2026 (Cuadricóptero)

Trabajo Práctico Integrador de la materia Control de Sistemas (Ingeniería en IA, FICH-UNL). Diseño y simulación de control de estabilización de un cuadricóptero: modelo linealizado de 8 estados / 4 entradas virtuales, control por asignación de polos y LQR, con y sin observador, comparación final de las 4 variantes.

## Cómo correr el notebook

```bash
python -m venv .venv
.venv\Scripts\activate      # Windows
pip install -r requirements.txt
jupyter notebook notebook/
```

## Estructura

- `notebook/` — notebook principal con el desarrollo del TP.
- `CLAUDE.md` — contexto completo del proyecto (consigna, modelo, convenciones).
- `ROADMAP.md` — fases del proyecto.
- `estado.md` — estado actual y próxima acción.
