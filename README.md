create env 

```bash
 conda create --name wineq python=3.7 -y    
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


download the data from:

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5
```bash
git init 
```
```bash
dvc init 
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add . 
```

```bash
git commit -m "first commit" 
```

```bash
git add . && git commit -m "update Readme.md" 
```

```bash
git remote add origin https://github.com/aymane1234/simple-dvc-demo.git
git branch -M main
git push origin main
```