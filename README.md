create env

```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

created a req file

install the req
```bash
pip install -r requirements.txt
```

download the data from

https://www.kaggle.com/rajyellow46/wine-quality


git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

for updates

git add .
git commit -m "update Readme.md"

for adding remote origin

git remote add origin https://github.com/Shrashi/simple-dvc-demo.git
git branch -M main
git push origin main