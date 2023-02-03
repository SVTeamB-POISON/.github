# Introduction
### <p>AI를 활용한 독초 판별 서비스 POISON</p>
<div align=center>
<img src="https://user-images.githubusercontent.com/112836685/216101873-695f850c-1647-4374-b744-d76cef4f1ab3.png"/>

  
### 배포 링크 [poisonsvb.com](https://poisonsvb.com)
  
</div>
  
***
## Features
- 반응형 UI ![반응형](https://user-images.githubusercontent.com/83197138/216485464-ba868a0a-3625-429f-8883-d47504e6a74c.gif)
- 이미지 업로드 및 판별![사진업로드](https://user-images.githubusercontent.com/83197138/216485225-5e284db3-d0c8-400d-8b18-c825fc5969c3.gif)
- 도감 ![도감 무한스크롤](https://user-images.githubusercontent.com/83197138/216485419-960d34f1-04f2-4546-9843-9ca0bc5d6d35.gif)
- 검색 ![검색](https://user-images.githubusercontent.com/83197138/216485432-be9465a4-8935-4cc5-a2df-f2993e5e02fd.gif)
-  ![차트](https://user-images.githubusercontent.com/83197138/216485444-51852996-3fa4-4e6f-a325-00fded4055b2.gif)






***
## System Arcitechture
<div align =center>
<image src="https://user-images.githubusercontent.com/112836685/216496964-67b71afe-feb5-4d87-913d-ae3d83e9bd3c.png">
</div>
  
  
  
***
## Tech Stack

<div align =center>

Area| Tech Stack|
:--------:|:------------------------------:|
**Fronted** | <img src="https://img.shields.io/badge/TypeScript-3178C6.svg?style=for-the-badge&logo=TypeScript&logoColor=black"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/ReactQuery-FF4154.svg?&style=for-the-badge&logo=ReactQuery&logoColor=white"> <img src="https://img.shields.io/badge/Sass-CC6699?&style=for-the-badge&logo=Sass&logoColor=white">
**Backend** | <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white"> <img src="https://img.shields.io/badge/DJANGO_REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white"> <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white"> <img src="https://img.shields.io/badge/mongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white">  <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white">
**AI** | <img src="https://img.shields.io/badge/flask-000000?&style=for-the-badge&logo=flask&logoColor=white"> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=OpenCV&logoColor=white"> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?&style=for-the-badge&logo=TensorFlow&logoColor=white"> <img src="https://img.shields.io/badge/scikit_learn-F7931E?&style=for-the-badge&logo=scikit-learn&logoColor=white">
**DevOps** | <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=black"> <img src="https://img.shields.io/badge/gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=black"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/Github_Actions-2088FF?style=for-the-badge&logo=Github-Actions&logoColor=black"> <img src="https://img.shields.io/badge/Amazon_EC2-FF9900?style=for-the-badge&logo=Amazon-EC2&logoColor=black">
**Monitoring** |   <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=black"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=black"> <img src = "https://img.shields.io/badge/cadvisor-1478FF?style=for-the-badge&logoColor=black"> ![node-exporter](https://img.shields.io/badge/node_exporter-37D100?style=for-the-badge&logoColor=black) ![Elastic Stack](https://img.shields.io/static/v1?style=for-the-badge&message=Elastic+Stack&color=005571&logo=Elastic+Stack&logoColor=FFFFFF&label=)
**etc** | ![Slack](https://img.shields.io/static/v1?style=for-the-badge&message=Slack&color=4A154B&logo=Slack&logoColor=FFFFFF&label=) ![Notion](https://img.shields.io/static/v1?style=for-the-badge&message=Notion&color=000000&logo=Notion&logoColor=FFFFFF&label=) ![Figma](https://img.shields.io/static/v1?style=for-the-badge&message=Figma&color=F24E1E&logo=Figma&logoColor=FFFFFF&label=) ![Postman](https://img.shields.io/static/v1?style=for-the-badge&message=Postman&color=FF6C37&logo=Postman&logoColor=FFFFFF&label=) <img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"> ![GitKraken](https://img.shields.io/static/v1?style=for-the-badge&message=GitKraken&color=179287&logo=GitKraken&logoColor=FFFFFF&label=) ![Visual Studio Code](https://img.shields.io/static/v1?style=for-the-badge&message=Visual+Studio+Code&color=007ACC&logo=Visual+Studio+Code&logoColor=FFFFFF&label=)
</div>
  
***

## API


### swagger
<div markdown="1">

![image](https://user-images.githubusercontent.com/112836685/215753323-26257498-ce14-435b-9bd6-def0dc1f64f7.png)

</div>

***

## Monitoring
Grafana + Prometheus, ELK

|**Django** |**Node exporter**|
|-----|-----|
<img src = "https://user-images.githubusercontent.com/112836685/215755917-d95d1f67-284e-46bc-bb1a-4b4d60d0248d.png" width="500px" height="300px">|<img src = "https://user-images.githubusercontent.com/112836685/215756393-afd0c358-198c-475b-afc4-2a61ef44a20d.png" width="500px" height="300px">


|**cAdvisor** |**ELK**|
|-----|-----|
<img src = "https://user-images.githubusercontent.com/112836685/215756456-c339b819-463f-4b1b-9434-075df74f3684.png" width="500px" height="300px">|<img src = "https://user-images.githubusercontent.com/112836685/216101722-55819672-9a8e-4165-b45e-6b42f7b3f101.png" width="500px" height="300px">

***
  
## Installation

### 서버 시작하기

Backend .env file

- config/.env

```
DJANGO_SECRET_KEY=
DJANGO_PASSWORD=
```

```shell
$ git clone https://github.com/SV-Team-B/docker.git
$ git submodule update --recursive --remote --init
$ cd frontend
$ yarn
$ yarn build
$ cd ..
$ docker-compose up --build -d
```

### 개발 서버 시작하기

```shell
$ git clone https://github.com/SV-Team-B/docker.git
$ git submodule update --recursive --remote --init
$ docker-compose -f docker-compose-dev.yml up -d
```
***

| Name    | <center>이상민</center>|<center>한정욱</center> |<center>강석규</center> | 
| ------- | --------------------------------------------- | ------------------------------------ | --------------------------------------------- | 
| Profile | <center> <img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/83197138?v=4" /> </center>|<center><img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/101189924?v=4" /></center>|<center><img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/8746067?v=4" /></center>|
| role    | <center>Team Leader<br> Frontend, DevOps</center>   | <center>Frontend, <br> DevOps</center>    | <center>Frontend ,<br> DevOps</center>  | 
GitHub | <center>[@sangminlee98](https://github.com/sangminlee98)</center> | <center>[@nowrobin](https://github.com/nowrobin) </center>| <center>[@AlgeMoya](https://github.com/AlgeMoya) </center>|



| Name    | <center>강기환</center> | <center>이준우</center> | <center>박영식</center> | <center>정동훈</center>
| ------- | --------------------------------------- | --------------------------------------- | --------------------------------------- | --------------------------------------- |
| Profile |<center><img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/100124081?s=400&v=4" /></center>|<center><img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/107318116?v=4" /></center>|<center><img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/99026631?v=4" /></center>|<center><img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/112836685?s=400&v=4" /></center>|
| role    | <center>Bakcend ,<br> DevOps, <br> AI</center> | <center>Backend,<br> DevOps</center> | <center>Backend,<br> DevOps</center> | <center>Backend,<br> DevOps</center> |
GitHub | <center>[@sangminlee98](https://github.com/sangminlee98)</center> | <center>[@nowrobin](https://github.com/nowrobin) </center>| <center>[@AlgeMoya](https://github.com/AlgeMoya) </center>| <center>[@GiHwan2](https://github.com/GiHwan2)</center> | <center>[@JunRain2](https://github.com/JunRain2)</center> | <center>[@0sik](https://github.com/0sik)</center> | <center>[@jjeongdong](https://github.com/jjeongdong)</center>





</div>
