# 专用代码仓库
```
git clone https://github.com/melopeasant/code.git  
```
```
git clone git@github.com:melopeasant/code.git
```
## 常用操作
```
git add .  
```
```
git commit -m "message"
```  
```  
git push
```  
## 创建 Git 仓库:
```
mkdir <仓库名>
cd <仓库名>
git init 
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/<用户名>/<仓库名>.git
git push -u origin "main"
```
## 已有仓库?
```
cd <仓库名>
git remote add origin https://github.com/<用户名>/<仓库名>.git
git push -u origin "main"
```
