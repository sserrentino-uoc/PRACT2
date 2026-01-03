# PRACT2 — Adult Income (Python)

## Integrantes
- SEBASTIAN SERRENTINO — iniciales: SS
- ALBERTO MOCHON — iniciales: AM

Fuente de Datos: Becker, B. & Kohavi, R. (1996). Adult [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5XW20.

Repositorio GitHub: https://github.com/sserrentino-uoc/PRACT2-BPS

Vídeo (Google Drive UOC): https://drive.google.com/file/d/1tnYbskKgCPtXX6o70qJ0-3UyY5_nEG31/view?usp=drive_link

## Estructura
- `src/`: código fuente (pipeline end-to-end)
- `data/raw/`: datos fuente (`adult.zip`) y CSV crudo generado
- `data/processed/`: dataset seleccionado y dataset limpio final
- `reports/`: resumen, tablas, figuras, reporte y memoria PDF
- `config/project.json`: metadatos del proyecto (nombres, links, parámetros)

## Requisitos (Python)
Instalar dependencias:

```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# Linux/macOS:
# source .venv/bin/activate

pip install -r requirements.txt
```

Ejecutar el pipeline completo:

```bash
python -m src.run_all
```

## Artefactos generados
- `data/raw/adult_raw.csv` (datos originales integrados train+test)
- `data/processed/adult_selected.csv` (selección)
- `data/processed/adult_clean.csv` (datos finales analizados)
- `reports/summary.json` (resumen numérico para trazabilidad)
- `reports/report.md` (reporte con observaciones/conclusiones)
- `reports/memoria.pdf` (memoria final en PDF)
