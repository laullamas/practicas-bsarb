# Biología de Sistemas — Prácticas

**Máster en Bioinformática, Universidad de Murcia (2025-2026)**  
Autora: Laura Llamas López

Repositorio de prácticas de la asignatura **Biología de Sistemas**.

---

## Práctica 1 — Análisis estructural de redes PPI

Análisis topológico de la red de interacción proteína-proteína de *Arabidopsis thaliana* (Arabidopsis Interactome Mapping Consortium, 2011) y estudio de redes de enfermedad humanas mediante STRING, incluyendo clustering MCL y enriquecimiento funcional.

**Herramientas:** Cytoscape 3.10.4 · Python (pandas, numpy, matplotlib, scipy)

| Archivo | Descripción |
|---------|-------------|
| `practica1/analisis_red_PPI.ipynb` | Notebook Python: análisis estadístico y figuras |
| `practica1/node_table_p1.csv` | Tabla de nodos de la red PPI completa de *A. thaliana* |
| `practica1/subred_node_table.csv` | Tabla de nodos de la subred del hub AT5G22290 |
| `practica1/merged_network_clustered.csv` | Red fusionada de enfermedades con clusters MCL |
| `practica1/p1.cys` | Sesión de Cytoscape con todas las redes y análisis |

---

## Práctica 2 — Análisis FBA e ingeniería metabólica en *E. coli*

Análisis de flujos metabólicos (FBA/FVA) del modelo *E. coli* core y del modelo genome-scale iJO1366 mediante OptFlux. Incluye simulaciones en condiciones aerobias y anaerobias, cálculo de rendimientos (YIELD/CYIELD), análisis de variabilidad de flujos, knockouts de reacciones y genes, comparación pFBA vs MOMA, y propuesta de ingeniería metabólica para maximizar la producción de succinato.

**Herramientas:** OptFlux 3 · CellDesigner · Cytoscape · SBML/BiGG Models

| Archivo | Descripción |
|---------|-------------|
| `practica2/matriz.txt` | Matriz estequiométrica de la red sencilla (formato plano) |
| `practica2/metabolitos.txt` | Lista de metabolitos de la red sencilla |
| `practica2/reacciones.txt` | Lista de reacciones de la red sencilla |

---

## Práctica 3 — Simulación de un fragmento de la glucólisis (S-system)

Modelización y simulación de un fragmento de la ruta glucolítica (Glucosa-1-fosfato, Glucosa-6-fosfato y Fructosa-6-fosfato) mediante el formalismo de S-system de la Teoría de Sistemas Bioquímicos (BST). Incluye análisis de estado estacionario, perturbaciones en variables independientes (glucosa, PFK), alteraciones estructurales del modelo, escalado de constantes cinéticas, inhibición por producto de la glucoquinasa y simulación de pulsos de metabolito.

**Herramientas:** COPASI v4.46 · Python (matplotlib)

| Archivo | Descripción |
|---------|-------------|
| `practica3/figuras_practica3.ipynb` | Notebook Python: generación de figuras comparativas |
| `practica3/steady2000.txt` | Datos exportados de COPASI: evolución temporal 2000 min (referencia) |
| `practica3/f_alteracion_estructural.txt` | Datos exportados de COPASI: alteración estructural (α₂, g₂₂) |
| `practica3/g_todasx10.txt` | Datos exportados de COPASI: todas las constantes ×10 |
| `practica3/g_x2.txt` | Datos exportados de COPASI: solo constantes de X₂ ×10 |
