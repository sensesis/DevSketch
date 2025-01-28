### <p align = center>2024 Techeer Winter BootCamp I team<p>
<div align=center>
<br> <image width=50%, height=50%, src="">


<br> DevSketch 
##### URL : https://devsketch.site
</div>

## 🔮 Table of Contents
- [Medium](#-Medium)
- [Demo](#-Demo)
- [System Architechture](#-System-Architechture)
- [Tech stack](#-Tech-stack)
- [ERD](#-Erd)
- [API](#-API)
- [Flow Chart](#-Flow-Chart)
- [Sequence Diagram](#-Sequence-Diagram)
- [Monitoring](#-Monitoring)
- [Directory Structure](#-Directory-Structure)
- [How to Start](#-How-to-Start)
- [Member](#-Member)



## 📝 Medium 
https://naver.com

</br>

## ✨ Demo

<table width="1000">
    
</table>

## 🏢 System Architechture
<img src="">

</br>

## 💻 Tech stack
<table width="100%">

</table>

</br>


## 🗺️ ERD
<img src="https://github.com/user-attachments/assets/9ee49521-fbce-45a1-9a79-d0624d476ed4">

</br>


## 📄 API 
<div style="text-align: center;">

</div>
</br>

## 🪐 Flow Chart
<img src="">

</br>

## 📊 Sequence Diagram
<img src="">

</br>

## 🧑🏻‍💻 Monitoring
<table align="center" style="border-collapse: collapse;">

</table>


## 📂 Directory Structure
<details>
    <summary>DevSketch-Backend</summary>
<pre>
<code>

🗂️Backend
┣🗂️.github
┃┗ 🗂️ISSUE_TEMPLATE
┣🗂️config
┃ ┣ 📃__init__.py
┃ ┣ 📃asgi.py
┃ ┣ 📃celery.py
┃ ┣ 📃settings.py
┃ ┣ 📃urls.py
┃ ┗ 📃wsgi.py
┣🗂️dind
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃admin.py
┃ ┣ 📃apps.py
┃ ┣ 📃models.py
┃ ┣ 📃serializers.py
┃ ┣ 📃tasks.py
┃ ┣ 📃tests.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣🗂️document
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃admin.py
┃ ┣ 📃apps.py
┃ ┣ 📃models.py
┃ ┣ 📃serializers.py
┃ ┣ 📃tasks.py
┃ ┣ 📃tests.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣🗂️grafana/data
┃ ┣ 🗂️csv
┃ ┣ 🗂️pdf
┃ ┣🗂️plugins
┃ ┣ 🗂️png
┃ ┗ 📃grafana.db
┣🗂️prometheus
┃ ┗ 📃prometheus.yml
┣🗂️document
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃admin.py
┃ ┣ 📃apps.py
┃ ┣ 📃authentication.py
┃ ┣ 📃models.py
┃ ┣ 📃serializers.py
┃ ┣ 📃tests.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣🗂️repo
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃admin.py
┃ ┣ 📃apps.py
┃ ┣ 📃models.py
┃ ┣ 📃serializers.py
┃ ┣ 📃tasks.py
┃ ┣ 📃tests.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣🗂️Tech_Stack
┃ ┣ 📂backend
┃ ┣ 📂frontend
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃models.py
┃ ┣ 📃tasks.py
┃ ┣ 📃urls.py
┃ ┣ 📃utils.py
┃ ┗ 📃views.py
┣ 📃.gitignore
┣ 📃docker-compose.yml
┣ 📃Dockerfile
┣ 📃Jenkinsfile
┣ 📃manage.py
┣ 📃README.md
┣ 📃requirements.txt

</code>
</pre>
</details>


<details>
    <summary>DevSketch-Frontend</summary>
<pre>
<code>

🗂️Frontend
┣🗂️.github
┃┗ 🗂️ISSUE_TEMPLATE
┣🗂️.storybook
┃ ┣ 📃main.js
┃ ┗ 📃preview.jsx
┣🗂️.vite/deps
┃ ┣ 📃_metadata.json
┃ ┣ 📃chunk-GT27OAPC.js
┃ ┣ 📃chunk-GT27OAPC.js.map
┃ ┣ 📃chunk-SY4HHCYH.js
┃ ┣ 📃chunk-SY4HHCYH.js.map
┃ ┣ 📃package.json
┃ ┣ 📃react-dom_client.js
┃ ┣ 📃react-dom_client.js.map
┃ ┣ 📃react-router-dom.js
┃ ┣ 📃react-router-dom.js.map
┃ ┣ 📃react.js
┃ ┗ 📃react.js.map
┣🗂️.vscode
┃ ┣ 📃launch.json
┃ ┗ 📃tasks.json
┣🗂️dist
┃ ┣ 📂assets
┃ ┗ 📃index.html
┣🗂️src
┃ ┣ 📂api
┃ ┣ 📂assets
┃ ┣ 📂components
┃ ┣ 📂config
┃ ┣ 📂pages
┃ ┣ 📂store
┃ ┣ 📂utils
┃ ┣ 📃.DS_Store
┃ ┣ 📃App.css
┃ ┣ 📃App.jsx
┃ ┣ 📃index.css
┃ ┗ 📃main.jsx
┣ 📃.DS_Store
┣ 📃.gitignore
┣ 📃.dockerignore
┣ 📃.eslintignore
┣ 📃.eslintrc.json
┣ 📃.gitattributes
┣ 📃.gitignore
┣ 📃.prettierignore
┣ 📃.prettierrc
┣ 📃.yarnrc.yml
┣ 📃Dockerfile
┣ 📃README.md
┣ 📃build-storybook.log
┣ 📃chromatic.config.json
┣ 📃docker-compose.debug.yml
┣ 📃docker-compose.yml
┣ 📃eslint.config.js
┣ 📃index.html
┣ 📃migration-storybook.log
┣ 📃package.json
┣ 📃postcss.config.js
┣ 📃tailwind.config.js
┣ 📃vite.config.js
┗ 📃yarn.lock

</code>
</pre>
</details>

</br>

## 🧐 How to Start
### Backend 
```
git clone --recursive https://github.com/2024-Techeer-Winter-BootCamp-Team-I/Backend.git
```
### env setting in the Backend folder
* backend/.env
```
MYSQL_ROOT_PASSWORD=
MYSQL_DATABASE=
MYSQL_USER=
MYSQL_PASSWORD=

DATABASE_HOST=
DATABASE_HOST2=
DATABASE_NAME=
DATABASE_USER=
DATABASE_PASSWORD=

DEEPSEEK_API_KEY=
DEEPSEEK_API_URL=

FRONTEND_RESULT_URL=

GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=

GITHUB_REDIRECT_URI=

CELERY_BROKER_URL=
CELERY_RESULT_BACKEND=
```
### Run Docker
```
docker-compose up -d --build
```
### Frontend
```
git clone --recursive https://github.com/2024-Techeer-Winter-BootCamp-Team-I/Frontend.git
```
### Install
```

```

### Run
```

```
</br>

## 👪 Member
<table width="100%" align="center" style="border-collapse: collapse; text-align: center;">
<thead>
<tr>
<th>Pictures</th>
<td width="100" align="center">
<a href="https://github.com/ukongee">
<img src="" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/kimyeeun21">
<img src="" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/daiseek">
<img src="" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/sensesis">
<img src="" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/hwanh2">
<img src="" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/seungje1217">
<img src="https://github.com/user-attachments/assets/a663dcf4-e128-4112-a1eb-58d040a1e81f" width="60" height="60">
</a>
</td>
</tr>
<tr>
<th>Name</th>
<td width="100" align="center">박유경</td>
<td width="100" align="center">김예은</td>
<td width="100" align="center">정원희</td>
<td width="100" align="center">진기태</td>
<td width="100" align="center">김환희</td>
<td width="100" align="center">임승제</td>
</tr>
<tr>
<th>Position</th>
<td width="150" align="center">
Team Leader<br>
Frontend<br>
</td>
<td width="150" align="center">
Frontend<br>
</td>
<td width="150" align="center">
Frontend<br>
</td>
<td width="150" align="center">
Backend<br>
</td>
<td width="150" align="center">
Backend<br>
</td>
<td width="150" align="center">
Backend<br>
</td>
</tr>
<tr>
<th>GitHub</th>
<td width="100" align="center">
<a href="https://github.com/ukongee">
<img src="http://img.shields.io/badge/ukongee-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/kimyeeun21">
<img src="http://img.shields.io/badge/kimyeeun21-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/daiseek">
<img src="http://img.shields.io/badge/daiseek-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/sensesis">
<img src="http://img.shields.io/badge/sensesis-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/hwanh2">
<img src="http://img.shields.io/badge/hwanh2-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/seungje1217">
<img src="http://img.shields.io/badge/seungje1217-green?style=social&logo=github"/>
</a>
</td>
</tr>
</thead>
</table>

</br>
