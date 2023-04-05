## End to End ML Project

# Doubts 
# 1. How to open a floder in neuro lab 

### Create a enibvirinment 
```
conda create -p venv python==3.8

conda activate venv/
```
## Install all neccessary libraries

```
pip install -r requirements.txt
```
## To install setup.py  

```
python setup.py install  # but it is not word in company laptop

```

# for commit 
## 1. git (repository)
```
> ls -a
> git remote -v             # it shows the default origin
> git remote rm origin      # To remove default origin
# ls -a and git remote -v   # it shows empty
```

# intial steps to commit in git from VScode
```
git init
git add .
git remote add origin {Github REPo URL}
git commit -m "initial commit"
git branch -M main
git push origin main
```

# we have git and it will add using git clone
```
git clone https://github.com/SimhaChalamPathru/LinearRegression.git

```