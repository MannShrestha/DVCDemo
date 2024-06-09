## create environment

```bash

conda create -p venv python==3.9 -y
```

## create .gitignore file -> venv/

```bash

pip install -r requirements.txt
```

```bash

git init
```

```bash

dvc init
```


## Create a directory -> data/data.txt

```bash

dvc init
```

```bash

git status

git commit -m "dvc init"
```

## Now track the data with dvc
```bash

dvc add data/data.txt
```

## Then track other files with git 

```bash

git add data/data.txt.dvc

git add data/.gitignore
```

## update data in data.txt

```bash

dvc add data/data.txt

git add data/data.txt.dvc

git status

git commit -m "DVC"

git log
```

## For changing a branch

```bash

git branch

git checkout <hash key address>

dvc checkout
```

## return to master branch
```bash

git checkout master

dvc checkout
```