
# 🧭 Ruta de aprendizaje en Bioinformática con Python y bases de datos

## ✅ Etapa 1 – Reforzar Python y lógica bioinformática
**Objetivo:** Aprender a manejar listas, diccionarios, funciones, loops y manipular archivos de texto (.fasta, .gff, etc.)  
**Herramientas:** Python, Jupyter Notebook, Biopython  
**Recursos:**  
- YouTube: Curso Python para Bioinformáticos – Bioinformaticos: https://www.youtube.com/playlist?list=PLKK2u3U83TgH0q_o3ydOTC_hghkBFnA7b
- GitHub: Python for Biologists – Martin Jones: https://github.com/MartinJones/noBSbioinformatics
- Rosalind: https://rosalind.info/problems/locations/

**Ejercicios:**  
- Leer archivos FASTA con Biopython  
- Calcular contenido GC  
- Encontrar secuencias palindrómicas  

## ✅ Etapa 2 – Bases de datos biológicas (NCBI, UniProt, Ensembl)
**Objetivo:** Extraer información automática de genes, proteínas y anotaciones  
**Herramientas:** Biopython (`Entrez`, `SeqIO`), Requests, JSON, APIs  
**Recursos:**  
- YouTube: Extraer secuencias de NCBI con Python: https://www.youtube.com/watch?v=IHJcJjG7OPQ
- GitHub: NCBI Entrez API + Python: https://github.com/biopython/biopython/blob/master/Doc/examples/entrez_einfo.py
- OpenTargets Python API: https://platform.opentargets.org/

**Ejercicios:**  
- Buscar genes por nombre y descargar su secuencia  
- Obtener metadatos de UniProt  
- Guardar resultados en .csv con Pandas  

## ✅ Etapa 3 – Alineamientos, anotación y análisis funcional
**Objetivo:** Alinear secuencias, anotar proteínas, interpretar funciones  
**Herramientas:** MAFFT, MUSCLE, Prokka, eggNOG-mapper, Biopython  
**Recursos:**  
- YouTube: Alineamiento de secuencias con Clustal y MEGA: https://www.youtube.com/watch?v=NX9sDZs7FNM  
- GitHub: Pipeline con Prokka + EggNOG: https://github.com/vrmarcelino/prokka-eggnog  
- eggNOG-mapper online: https://eggnog-mapper.embl.de/

**Ejercicios:**  
- Alinear genes ortólogos entre especies  
- Ejecutar Prokka y revisar los genes anotados  
- Obtener GO terms, COGs y pathways KEGG con EggNOG  

## ✅ Etapa 4 – Filogenia y evolución molecular
**Objetivo:** Construir árboles filogenéticos, interpretar relaciones evolutivas  
**Herramientas:** MEGA, IQ-TREE, iTOL, SeaView  
**Recursos:**  
- YouTube: Cómo hacer árboles filogenéticos con MEGA e iTOL: https://www.youtube.com/watch?v=wSYKiog4CjU  
- GitHub: IQ-TREE pipelines: https://github.com/CibioCM/iQTree  
- iTOL para visualizar árboles: https://itol.embl.de/

**Ejercicios:**  
- Construir un árbol ML con IQ-TREE usando tus alineamientos  
- Anotar ramas en iTOL  
- Comparar árboles de diferentes ortólogos  

## ✅ Etapa 5 – Automatización de pipelines y proyectos reales
**Objetivo:** Automatizar análisis y construir proyectos reales  
**Herramientas:** Snakemake, Nextflow, Git, GitHub  
**Recursos:**  
- YouTube: Curso Snakemake bioinformático (ESP): https://www.youtube.com/watch?v=ZRXJgX3vnN8  
- GitHub: SnakeMake bioinformatics workflow: https://github.com/snakemake/snakemake-wrappers

**Proyectos sugeridos:**  
- Pipeline para descargar secuencias de ortólogos y alinearlas  
- Automatizar anotación con eggNOG + árbol con IQ-TREE  
- Publicar proyecto en GitHub con README + diagrama  

## ✅ Tips adicionales
- YouTube (inglés): Omics Tutorials, StatQuest, Ken Jee, Bioinformatics Review  
- GitHub: Explorar tags como `bioinformatics`, `genomics`, `python`  
- Kaggle: Usar datasets biológicos para visualización o ML
