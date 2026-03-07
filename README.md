# Análisis estructural de redes de interacción proteína-proteína (PPI)

**Biología de Sistemas — Práctica 1**  
Máster en Bioinformática, Universidad de Murcia (2025-2026)  
Autora: Laura Llamas López

## Descripción

Análisis topológico de la red PPI de *Arabidopsis thaliana* (Arabidopsis Interactome Mapping Consortium, 2011) y estudio de redes de enfermedad humanas mediante STRING, incluyendo clustering MCL y enriquecimiento funcional. Realizado con Cytoscape 3.10.4 y Python.

## Contenido del repositorio

| Archivo | Descripción |
|---------|-------------|
| `analisis_red_PPI.ipynb` | Notebook con el código Python para análisis estadístico y generación de figuras |
| `node_table_p1.csv` | Tabla de nodos de la red PPI completa de *A. thaliana* (exportada desde Cytoscape / Network Analyzer) |
| `subred_node_table.csv` | Tabla de nodos de la subred del hub AT5G22290 y primeros vecinos |
| `merged_network_clustered.csv` | Tabla de nodos de la red fusionada de enfermedades con clusters MCL (exportada desde Cytoscape) |
| `p1.cys` | Sesión de Cytoscape con todas las redes y análisis |

## Requisitos

- Python ≥ 3.10 con pandas, numpy, matplotlib y scipy
- Cytoscape ≥ 3.10.4 (para abrir `p1.cys`)
