# Flask web API 取得台灣氣象局公開資料
##### pip install flask

取得台中資料
![](./demo_images/taichung.png)
取得台北資料
![](./demo_images/taipei.png)

# web API部署到網頁伺服器
##### heroku 利用 git 進行部署
1.下載 git for win / for mac
https://git-scm.com/ 

2.設定
git config --global user.name"user name"
git config --global user.email"user e-mail"

3.create new app
![](./demo_images/create_new_app.png)

pip install flask
pip install gunicorn
pip install requests
##### pip list
![](./demo_images/pip_list.png)

# Heroku 必須包含
1. requirements.txt

![](./demo_images/requirements.png)
2. runtime.txt 

![](./demo_images/runtime.png)
3. Procfile

![](./demo_images/procfile.png)

# Push to Heroku
