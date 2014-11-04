# Inteligência Artificial na Prática

Disponibilizamos um notebook [IPython](http://ipython.org/notebook.html) demonstrando
o uso do algoritmo [DBSCAN](en.wikipedia.org/wiki/DBSCAN) como implementado no
pacote open-source [ddbscan](https://github.com/cloudwalkio/ddbscan).

No diretório `slides` você encontra os slides utilizados na palestra.

## Dependências

### Linux

Para rodar o notebook, devemos ter instalados:

* IPython: `pip install ipython`
* scikit-learn: `pip install scikit-learn`
* ddbscan: `pip install ddbscan`
* matplotlib: `sudo apt-get install python-matplotlib`

### Windows e Mac

É mais fácil instalar o [Anaconda](http://continuum.io/downloads) (funciona
também no Linux).

Ainda restarão duas dependências que podem ser instaladas via console:

```
pip install scikit-learn
pip install ddbscan
```
## Utilização

É só iniciar uma sessão do IPython neste diretório:
```
ipython notebook
```

O código estará disponível no browser em `http://localhost:8888/notebooks/Using_DDBSCAN.ipynb`.
