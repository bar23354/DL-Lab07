# Deep Learning: Laboratorio 07

Roberto José Barreda Siekavizza, 23354

NLP end-to-end y embeddings: skip-gram con negative sampling en PyTorch, Word2Vec de gensim y GloVe, evaluados con analogías, WordSim-353, SimLex-999 y clasificación de AG News.

| Ruta | Contenido |
|---|---|
| `Lab07_NLP_Embeddings.ipynb` | Notebook completo con resultados |
| `docs/Informe_Lab07.pdf` | Informe |
| `vectors/sgns_mejor.kv` | Vectores del mejor SGNS, se cargan con `KeyedVectors.load` |
| `results/`, `figures/` | Tablas y figuras que genera el notebook |

```bash
pip install torch gensim datasets nltk scikit-learn pandas matplotlib truststore
```

El notebook descarga los datos en la primera ejecución y guarda cachés en `data/`, que no se sube al repositorio. Requiere GPU con CUDA.
