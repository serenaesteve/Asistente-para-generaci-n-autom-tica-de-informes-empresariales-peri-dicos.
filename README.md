# s.reports — Generador Automático de Informes Empresariales

App Flask con análisis IA vía Ollama (LLaMA 3) para generar informes ejecutivos periódicos.

## Instalación

```bash
pip install -r requirements.txt --break-system-packages
```

## Requisitos
- Python 3.8+
- Ollama corriendo en localhost:11434 con modelo llama3
- (Opcional) WeasyPrint para exportar PDF nativo

## Ejecutar

```bash
cd sreports
python app.py
# Accede en http://localhost:5000
```

## Funcionalidades

- **4 tipos de informe**: Ventas/KPIs, Financiero, RRHH, Marketing
- **3 fuentes de datos**: CSV/Excel, entrada manual de métricas, formulario guiado por tipo
- **Análisis IA**: Generado automáticamente con Ollama LLaMA 3 (resumen ejecutivo, análisis, alertas, recomendaciones)
- **Output doble**: Vista web interactiva con Chart.js + exportación PDF
- **Multi-empresa**: Gestión de varias empresas
- **Regenerar**: Vuelve a analizar cualquier informe con 1 clic
