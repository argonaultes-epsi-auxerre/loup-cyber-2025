Créer l'environnement virtuel

```bash
python -m venv .venv
. ./.venv/bin/activate
pip install -r requirements.txt
```

Start adminserver

```bash
python src/adminserver.py
```

Start interfacetcp

```bash
python src/interfacetcp.py
```


Run client

```bash
python src/clienttcp.py
```


Test client

```bash
action (q: quitter, p: participer, d: deplacer, c: carte): p
login: gael
```
