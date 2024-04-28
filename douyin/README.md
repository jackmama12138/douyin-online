git config --global user.name="showMaker"
git config --global user.email="946519656@qq.com"
git init
git add .
git commit -m "1.0"
git remote add origin 你的远程仓库URL
git pull
git push -u origin master
报错解决
git config --global http.version HTTP/1.1