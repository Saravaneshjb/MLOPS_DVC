```
mkdir dvc
cd dvc
code .
```

```
conda create venv python==3.8 -y
```

```
git init
```

```
touch .gitignore
touch README.md
```

```
pip install -r requirements.txt
```

```
dvc repro
dvc dag
```