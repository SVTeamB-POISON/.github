
### <p>AI를 활용한 독초 판별 서비스 POISON</p>
<div align=center>
<img src="https://user-images.githubusercontent.com/112836685/216101873-695f850c-1647-4374-b744-d76cef4f1ab3.png"/>
 
</div>

***
## Medium.com
https://medium.com/@nowrobin3/poison-973f84627409
***
## Production
https://poisonsvb.com
  
***
## Features

### 반응형 UI
<img src="https://user-images.githubusercontent.com/83197138/216485464-ba868a0a-3625-429f-8883-d47504e6a74c.gif" width="50%"/>
Desktop, Tablet, Mobile 등 화면사이즈에 맞는 UI 제공

### 이미지 업로드 및 판별
<img src="https://user-images.githubusercontent.com/83197138/216485225-5e284db3-d0c8-400d-8b18-c825fc5969c3.gif" width="50%"/>
Drag&Drop 을 통한 이미지 업로드 및 독초 판별 결과 제공

### 도감 
<img src="https://user-images.githubusercontent.com/83197138/216485419-960d34f1-04f2-4546-9843-9ca0bc5d6d35.gif" width="50%"/>
학습된 식물들의 리스트 및 식물 정보를 볼 수 있는 페이지<br/>
도감리스트 전체를 로딩하는 것이 아닌 무한스크롤을 통해 필요한 만큼의 데이터 로딩

### 검색 
<img src="https://user-images.githubusercontent.com/83197138/216485432-be9465a4-8935-4cc5-a2df-f2993e5e02fd.gif" width="50%"/>
도감에 등록된 식물을 검색할 수 있는 페이지<br/>
MongoDB Atlas Search를 통해 유사어 검색, 다중검색 지원

### 랭킹 
<img src="https://user-images.githubusercontent.com/83197138/216485444-51852996-3fa4-4e6f-a325-00fded4055b2.gif" width="50%"/>
판별 결과로 많이 조회된 순으로 랭킹을 보여주는 컴포넌트<br/>
스케쥴러를 사용하여 1시간 단위의 랭킹 제공 가능<br/>
차트를 통해 결과를 시각적으로 표현






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
**Frontend** | <img src="https://img.shields.io/badge/TypeScript-3178C6.svg?style=for-the-badge&logo=TypeScript&logoColor=black"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/ReactQuery-FF4154.svg?&style=for-the-badge&logo=ReactQuery&logoColor=white"> <img src="https://img.shields.io/badge/React Router-CA4245.svg?&style=for-the-badge&logo=reactrouter&logoColor=white"> <img src="https://img.shields.io/badge/Vite-646CFF.svg?&style=for-the-badge&logo=vite&logoColor=white"> <img src="https://img.shields.io/badge/Sass-CC6699?&style=for-the-badge&logo=Sass&logoColor=white"> <img src="https://img.shields.io/badge/Framer Motion-0055FF?&style=for-the-badge&logo=framer&logoColor=white"> <img src="https://img.shields.io/badge/Storybook-FF4785?&style=for-the-badge&logo=storybook&logoColor=white"> <img src="https://img.shields.io/badge/Mock Service Worker-FF6A33?&style=for-the-badge"> <img src="https://img.shields.io/badge/ApexChart-0682F2?&style=for-the-badge"> 
**Backend** | <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white"> <img src="https://img.shields.io/badge/DJANGO_REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white"> <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white"> <img src="https://img.shields.io/badge/mongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white">  <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white">
**AI** | <img src="https://img.shields.io/badge/flask-000000?&style=for-the-badge&logo=flask&logoColor=white"> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=OpenCV&logoColor=white"> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?&style=for-the-badge&logo=TensorFlow&logoColor=white"> <img src="https://img.shields.io/badge/scikit_learn-F7931E?&style=for-the-badge&logo=scikit-learn&logoColor=white">
**DevOps** | <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=black"> <img src="https://img.shields.io/badge/gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=black"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/Github_Actions-2088FF?style=for-the-badge&logo=Github-Actions&logoColor=black"> <img src="https://img.shields.io/badge/Amazon_EC2-FF9900?style=for-the-badge&logo=Amazon-EC2&logoColor=black">
**Monitoring** |   <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=black"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=black"> <img src = "https://img.shields.io/badge/cadvisor-1478FF?style=for-the-badge&logoColor=black"> <img src="https://img.shields.io/badge/Sentry-362D59?&style=for-the-badge&logo=sentry&logoColor=white"> ![node-exporter](https://img.shields.io/badge/node_exporter-37D100?style=for-the-badge&logoColor=black) ![Elastic Stack](https://img.shields.io/static/v1?style=for-the-badge&message=Elastic+Stack&color=005571&logo=Elastic+Stack&logoColor=FFFFFF&label=)
**etc** | ![Slack](https://img.shields.io/static/v1?style=for-the-badge&message=Slack&color=4A154B&logo=Slack&logoColor=FFFFFF&label=) ![Notion](https://img.shields.io/static/v1?style=for-the-badge&message=Notion&color=000000&logo=Notion&logoColor=FFFFFF&label=) ![Figma](https://img.shields.io/static/v1?style=for-the-badge&message=Figma&color=F24E1E&logo=Figma&logoColor=FFFFFF&label=) ![Postman](https://img.shields.io/static/v1?style=for-the-badge&message=Postman&color=FF6C37&logo=Postman&logoColor=FFFFFF&label=) <img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"> ![GitKraken](https://img.shields.io/static/v1?style=for-the-badge&message=GitKraken&color=179287&logo=GitKraken&logoColor=FFFFFF&label=) ![Visual Studio Code](https://img.shields.io/static/v1?style=for-the-badge&message=Visual+Studio+Code&color=007ACC&logo=Visual+Studio+Code&logoColor=FFFFFF&label=)
</div>
  
*** 
 
<details>
<summary><h3>Frontend</h3></summary>
 
## File Directory
```
📦frontend
 ┣ 📂.github
 ┃ ┣ 📂ISSUE_TEMPLATE
 ┃ ┃ ┣ 📜error-report.md
 ┃ ┃ ┣ 📜feature-request.md
 ┃ ┃ ┣ 📜refactoring-report.md
 ┃ ┃ ┗ 📜setting-report.md
 ┃ ┗ 📜PULL_REQUEST_TEMPLATE.md
 ┣ 📂.storybook
 ┃ ┣ 📜main.cjs
 ┃ ┣ 📜preview-head.html
 ┃ ┗ 📜preview.cjs
 ┣ 📂public
 ┃ ┣ 📜favicon.ico
 ┃ ┗ 📜mockServiceWorker.js
 ┣ 📂src
 ┃ ┣ 📂assets
 ┃ ┃ ┣ 📜FirstMedal.png
 ┃ ┃ ┣ 📜SecondMedal.png
 ┃ ┃ ┣ 📜ThirdMedal.png
 ┃ ┃ ┣ 📜crown.svg
 ┃ ┃ ┣ 📜firstPlace.svg
 ┃ ┃ ┣ 📜icon_x.png
 ┃ ┃ ┣ 📜image1.svg
 ┃ ┃ ┣ 📜logo.svg
 ┃ ┃ ┣ 📜logo2.png
 ┃ ┃ ┣ 📜main_background.png
 ┃ ┃ ┣ 📜outercrown.svg
 ┃ ┃ ┣ 📜react.svg
 ┃ ┃ ┣ 📜search.svg
 ┃ ┃ ┗ 📜upload.svg
 ┃ ┣ 📂components
 ┃ ┃ ┣ 📂BarChart
 ┃ ┃ ┃ ┗ 📜index.tsx
 ┃ ┃ ┣ 📂DetailModal
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂DonutChart
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂EncyclopediaBtn
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂FlowerCard
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂Loading
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂Loading2
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂LogoTitle
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂NavigationBar
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂PieChart
 ┃ ┃ ┃ ┗ 📜index.tsx
 ┃ ┃ ┣ 📂RankList
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂RankModal
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂RankTop
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂RankingBtn
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┗ 📂ResultCard
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┣ 📂hooks
 ┃ ┃ ┣ 📜useInput.ts
 ┃ ┃ ┗ 📜useSearchFlower.ts
 ┃ ┣ 📂mocks
 ┃ ┃ ┣ 📜handlers.ts
 ┃ ┃ ┗ 📜worker.ts
 ┃ ┣ 📂pages
 ┃ ┃ ┣ 📂Encyclopedia
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂Main
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂Result
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┗ 📜_layout.tsx
 ┃ ┣ 📂stories
 ┃ ┃ ┣ 📂DetailModal
 ┃ ┃ ┃ ┣ 📜DetailModal.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂DonutChart
 ┃ ┃ ┃ ┣ 📜DountChart.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂EncyclopediaBtn
 ┃ ┃ ┃ ┣ 📜EncyclopediaBtn.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂FlowerCard
 ┃ ┃ ┃ ┣ 📜FlowerCard.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂Loading
 ┃ ┃ ┃ ┣ 📜Loading.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂Loading2
 ┃ ┃ ┃ ┣ 📜Loading2.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂LogoTitle
 ┃ ┃ ┃ ┣ 📜Logotitle.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂NavigationBar
 ┃ ┃ ┃ ┣ 📜NavigationBar.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂RankList
 ┃ ┃ ┃ ┣ 📜RankList.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂RankModal
 ┃ ┃ ┃ ┣ 📜RankModal.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂RankTop
 ┃ ┃ ┃ ┣ 📜RankTop.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂RankingBtn
 ┃ ┃ ┃ ┣ 📜RankingBtn.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂ResultCard
 ┃ ┃ ┃ ┣ 📜ResultCard.stories.tsx
 ┃ ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┃ ┗ 📜styles.module.scss
 ┃ ┃ ┣ 📂assets
 ┃ ┃ ┃ ┣ 📜FirstMedal.png
 ┃ ┃ ┃ ┣ 📜SecondMedal.png
 ┃ ┃ ┃ ┣ 📜ThirdMedal.png
 ┃ ┃ ┃ ┣ 📜code-brackets.svg
 ┃ ┃ ┃ ┣ 📜colors.svg
 ┃ ┃ ┃ ┣ 📜comments.svg
 ┃ ┃ ┃ ┣ 📜crown.svg
 ┃ ┃ ┃ ┣ 📜direction.svg
 ┃ ┃ ┃ ┣ 📜firstPlace.svg
 ┃ ┃ ┃ ┣ 📜flow.svg
 ┃ ┃ ┃ ┣ 📜icon_x.png
 ┃ ┃ ┃ ┣ 📜image1.svg
 ┃ ┃ ┃ ┣ 📜logo copy.svg
 ┃ ┃ ┃ ┣ 📜logo.svg
 ┃ ┃ ┃ ┣ 📜logo2.png
 ┃ ┃ ┃ ┣ 📜main_background.png
 ┃ ┃ ┃ ┣ 📜outercrown.svg
 ┃ ┃ ┃ ┣ 📜plugin.svg
 ┃ ┃ ┃ ┣ 📜react.svg
 ┃ ┃ ┃ ┣ 📜repo.svg
 ┃ ┃ ┃ ┣ 📜search.svg
 ┃ ┃ ┃ ┣ 📜stackalt.svg
 ┃ ┃ ┃ ┗ 📜upload.svg
 ┃ ┃ ┣ 📂hooks
 ┃ ┃ ┃ ┣ 📜useInput.ts
 ┃ ┃ ┃ ┗ 📜useSearchFlower.ts
 ┃ ┃ ┣ 📜Button.stories.tsx
 ┃ ┃ ┣ 📜Button.tsx
 ┃ ┃ ┣ 📜Header.stories.tsx
 ┃ ┃ ┣ 📜Header.tsx
 ┃ ┃ ┣ 📜Introduction.stories.mdx
 ┃ ┃ ┣ 📜Page.stories.tsx
 ┃ ┃ ┣ 📜Page.tsx
 ┃ ┃ ┣ 📜button.css
 ┃ ┃ ┣ 📜header.css
 ┃ ┃ ┣ 📜media.scss
 ┃ ┃ ┣ 📜page.css
 ┃ ┃ ┗ 📜queryClient.ts
 ┃ ┣ 📂types
 ┃ ┃ ┣ 📜detail.ts
 ┃ ┃ ┣ 📜ency.ts
 ┃ ┃ ┣ 📜rank.ts
 ┃ ┃ ┣ 📜result.ts
 ┃ ┃ ┗ 📜test.ts
 ┃ ┣ 📜App.tsx
 ┃ ┣ 📜Routes.tsx
 ┃ ┣ 📜main.tsx
 ┃ ┣ 📜media.scss
 ┃ ┣ 📜queryClient.ts
 ┃ ┣ 📜reset.scss
 ┃ ┗ 📜vite-env.d.ts
 ┣ 📜.dockerignore
 ┣ 📜.eslintrc.js
 ┣ 📜.git
 ┣ 📜.gitignore
 ┣ 📜.prettierrc
 ┣ 📜Dockerfile.dev
 ┣ 📜Dockerfile.prod
 ┣ 📜LICENSE
 ┣ 📜README.md
 ┣ 📜index.html
 ┣ 📜package.json
 ┣ 📜postcss.config.cjs
 ┣ 📜tailwind.config.cjs
 ┣ 📜tsconfig.json
 ┣ 📜tsconfig.node.json
 ┣ 📜vite.config.ts
 ┗ 📜yarn.lock
 ```
 
## React Vite TypeScript
<img src="https://user-images.githubusercontent.com/83197138/216725991-05cc308e-13b0-415e-ba68-df336f37aa3a.png" width="60%"/>
ESModule 기반의 Vite를 사용하여 개발 서버를 더욱 빠르게 구동했습니다.
SPA인 React를 사용함으로써 UX를 향상시켰습니다.
Code splitting을 사용해 라우트별로 파일을 나누어 트래픽과 로딩 속도를 개선하였습니다.
정적 타입 언어인 Typescript을 사용하여 컴파일 단계에서 에러를 빠르게 확인할 수 있게 하였습니다.

## React Query & MSW
<img src="https://user-images.githubusercontent.com/83197138/216726050-67a1da9b-e822-4e4d-94e6-6e45148fa3ef.png" width="60%"/>
React query를 사용하여 서버와 클라이언트가 비동기적으로 공유하는 데이터를 관리하고 데이터 캐싱을 활용하여, API 트래픽을 감소시켰습니다.
네트워크 단에서 API를 Mocking 할 수 있는 MSW를 사용하여 API 개발을 기다리는 지연시간 없이 프론트엔드 개발이 가능하도록 하여 개발 속도를 향상시켰습니다.


## Storybook
<img src="https://user-images.githubusercontent.com/8746067/216549205-d8daf99f-19e4-4676-8e64-9243b030bbfd.png" width="60%"/>

Storybook을 사용해서 UI를 구성하는 컴포넌트들의 인터렉션 및 UI를 테스팅할 수 있게 했습니다.

## Monitoring
Sentry
|**Performance Monitoring** |**Error Example**|
|-----|-----|
<img src = "https://user-images.githubusercontent.com/8746067/216548977-2ed0a9b7-3d73-4442-9160-3d144285cdd9.png" width="500px" height="300px">|<img src = "https://user-images.githubusercontent.com/8746067/216548978-ce661720-1700-46b4-a5f1-4b77a65fe83f.png" width="500px" height="300px">

프론트엔드 에러 모니터링 및 트래킹 툴인 센트리를 사용하여 에러를 추적하였습니다. 에러의 종류, 발생 위치 등에 대한 정보를 제공하므로 원인을 찾는 데 들이는 시간을 덜 수 있으며, 에러 발생 즉시 메일 알림을 받아 빠르게 확인할 수 있습니다.
  
</details>  
  


<details> 
<summary><h3>Backend</h3></summary>
 
## File Directory

```
📦backend
 ┣ 📂.github
 ┃ ┣ 📂ISSUE_TEMPLATE
 ┃ ┃ ┣ 📜error-report.md
 ┃ ┃ ┣ 📜feature-request.md
 ┃ ┃ ┣ 📜refactoring-report.md
 ┃ ┃ ┗ 📜setting-report.md
 ┃ ┣ 📜.DS_Store
 ┃ ┗ 📜PULL_REQUEST_TEMPLATE.md
 ┣ 📂config
 ┃ ┣ 📜.env
 ┃ ┣ 📜__init__.py
 ┃ ┣ 📜asgi.py
 ┃ ┣ 📜settings.py
 ┃ ┣ 📜urls.py
 ┃ ┗ 📜wsgi.py
 ┣ 📂flower
 ┃ ┣ 📂migrations
 ┃ ┃ ┣ 📜0001_initial.py
 ┃ ┃ ┗ 📜__init__.py
 ┃ ┣ 📜__init__.py
 ┃ ┣ 📜admin.py
 ┃ ┣ 📜apps.py
 ┃ ┣ 📜celery.py
 ┃ ┣ 📜connect.py
 ┃ ┣ 📜models.py
 ┃ ┣ 📜serializers.py
 ┃ ┣ 📜tasks.py
 ┃ ┣ 📜tests.py
 ┃ ┣ 📜updater.py
 ┃ ┣ 📜urls.py
 ┃ ┗ 📜views.py
 ┣ 📂static
 ┃ ┣ 📂admin
 ┃ ┃ ┣ 📂css
 ┃ ┃ ┃ ┣ 📂vendor
 ┃ ┃ ┃ ┃ ┗ 📂select2
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LICENSE-SELECT2.md
 ┃ ┃ ┃ ┃ ┃ ┣ 📜select2.css
 ┃ ┃ ┃ ┃ ┃ ┗ 📜select2.min.css
 ┃ ┃ ┃ ┣ 📜autocomplete.css
 ┃ ┃ ┃ ┣ 📜base.css
 ┃ ┃ ┃ ┣ 📜changelists.css
 ┃ ┃ ┃ ┣ 📜dashboard.css
 ┃ ┃ ┃ ┣ 📜fonts.css
 ┃ ┃ ┃ ┣ 📜forms.css
 ┃ ┃ ┃ ┣ 📜login.css
 ┃ ┃ ┃ ┣ 📜nav_sidebar.css
 ┃ ┃ ┃ ┣ 📜responsive.css
 ┃ ┃ ┃ ┣ 📜responsive_rtl.css
 ┃ ┃ ┃ ┣ 📜rtl.css
 ┃ ┃ ┃ ┗ 📜widgets.css
 ┃ ┃ ┣ 📂fonts
 ┃ ┃ ┃ ┣ 📜LICENSE.txt
 ┃ ┃ ┃ ┣ 📜README.txt
 ┃ ┃ ┃ ┣ 📜Roboto-Bold-webfont.woff
 ┃ ┃ ┃ ┣ 📜Roboto-Light-webfont.woff
 ┃ ┃ ┃ ┗ 📜Roboto-Regular-webfont.woff
 ┃ ┃ ┣ 📂img
 ┃ ┃ ┃ ┣ 📂gis
 ┃ ┃ ┃ ┃ ┣ 📜move_vertex_off.svg
 ┃ ┃ ┃ ┃ ┗ 📜move_vertex_on.svg
 ┃ ┃ ┃ ┣ 📜LICENSE
 ┃ ┃ ┃ ┣ 📜README.txt
 ┃ ┃ ┃ ┣ 📜calendar-icons.svg
 ┃ ┃ ┃ ┣ 📜icon-addlink.svg
 ┃ ┃ ┃ ┣ 📜icon-alert.svg
 ┃ ┃ ┃ ┣ 📜icon-calendar.svg
 ┃ ┃ ┃ ┣ 📜icon-changelink.svg
 ┃ ┃ ┃ ┣ 📜icon-clock.svg
 ┃ ┃ ┃ ┣ 📜icon-deletelink.svg
 ┃ ┃ ┃ ┣ 📜icon-no.svg
 ┃ ┃ ┃ ┣ 📜icon-unknown-alt.svg
 ┃ ┃ ┃ ┣ 📜icon-unknown.svg
 ┃ ┃ ┃ ┣ 📜icon-viewlink.svg
 ┃ ┃ ┃ ┣ 📜icon-yes.svg
 ┃ ┃ ┃ ┣ 📜inline-delete.svg
 ┃ ┃ ┃ ┣ 📜search.svg
 ┃ ┃ ┃ ┣ 📜selector-icons.svg
 ┃ ┃ ┃ ┣ 📜sorting-icons.svg
 ┃ ┃ ┃ ┣ 📜tooltag-add.svg
 ┃ ┃ ┃ ┗ 📜tooltag-arrowright.svg
 ┃ ┃ ┗ 📂js
 ┃ ┃ ┃ ┣ 📂admin
 ┃ ┃ ┃ ┃ ┣ 📜DateTimeShortcuts.js
 ┃ ┃ ┃ ┃ ┗ 📜RelatedObjectLookups.js
 ┃ ┃ ┃ ┣ 📂vendor
 ┃ ┃ ┃ ┃ ┣ 📂jquery
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LICENSE.txt
 ┃ ┃ ┃ ┃ ┃ ┣ 📜jquery.js
 ┃ ┃ ┃ ┃ ┃ ┗ 📜jquery.min.js
 ┃ ┃ ┃ ┃ ┣ 📂select2
 ┃ ┃ ┃ ┃ ┃ ┣ 📂i18n
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜af.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ar.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜az.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜bg.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜bn.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜bs.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ca.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜cs.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜da.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜de.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜dsb.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜el.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜en.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜es.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜et.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜eu.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜fa.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜fi.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜fr.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜gl.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜he.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜hi.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜hr.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜hsb.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜hu.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜hy.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜id.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜is.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜it.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ja.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ka.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜km.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ko.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜lt.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜lv.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜mk.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ms.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜nb.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ne.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜nl.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜pl.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ps.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜pt-BR.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜pt.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ro.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ru.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜sk.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜sl.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜sq.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜sr-Cyrl.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜sr.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜sv.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜th.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜tk.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜tr.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜uk.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜vi.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜zh-CN.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜zh-TW.js
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LICENSE.md
 ┃ ┃ ┃ ┃ ┃ ┣ 📜select2.full.js
 ┃ ┃ ┃ ┃ ┃ ┗ 📜select2.full.min.js
 ┃ ┃ ┃ ┃ ┗ 📂xregexp
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LICENSE.txt
 ┃ ┃ ┃ ┃ ┃ ┣ 📜xregexp.js
 ┃ ┃ ┃ ┃ ┃ ┗ 📜xregexp.min.js
 ┃ ┃ ┃ ┣ 📜SelectBox.js
 ┃ ┃ ┃ ┣ 📜SelectFilter2.js
 ┃ ┃ ┃ ┣ 📜actions.js
 ┃ ┃ ┃ ┣ 📜autocomplete.js
 ┃ ┃ ┃ ┣ 📜calendar.js
 ┃ ┃ ┃ ┣ 📜cancel.js
 ┃ ┃ ┃ ┣ 📜change_form.js
 ┃ ┃ ┃ ┣ 📜collapse.js
 ┃ ┃ ┃ ┣ 📜core.js
 ┃ ┃ ┃ ┣ 📜inlines.js
 ┃ ┃ ┃ ┣ 📜jquery.init.js
 ┃ ┃ ┃ ┣ 📜nav_sidebar.js
 ┃ ┃ ┃ ┣ 📜popup_response.js
 ┃ ┃ ┃ ┣ 📜prepopulate.js
 ┃ ┃ ┃ ┣ 📜prepopulate_init.js
 ┃ ┃ ┃ ┗ 📜urlify.js
 ┃ ┣ 📂drf-yasg
 ┃ ┃ ┣ 📂redoc
 ┃ ┃ ┃ ┣ 📜LICENSE
 ┃ ┃ ┃ ┣ 📜redoc-logo.png
 ┃ ┃ ┃ ┣ 📜redoc.min.js
 ┃ ┃ ┃ ┗ 📜redoc.standalone.js.map
 ┃ ┃ ┣ 📂redoc-old
 ┃ ┃ ┃ ┣ 📜LICENSE
 ┃ ┃ ┃ ┣ 📜redoc.min.js
 ┃ ┃ ┃ ┗ 📜redoc.min.js.map
 ┃ ┃ ┣ 📂swagger-ui-dist
 ┃ ┃ ┃ ┣ 📜LICENSE
 ┃ ┃ ┃ ┣ 📜NOTICE
 ┃ ┃ ┃ ┣ 📜absolute-path.js
 ┃ ┃ ┃ ┣ 📜favicon-32x32.png
 ┃ ┃ ┃ ┣ 📜index.js
 ┃ ┃ ┃ ┣ 📜oauth2-redirect.html
 ┃ ┃ ┃ ┣ 📜swagger-ui-bundle.js
 ┃ ┃ ┃ ┣ 📜swagger-ui-bundle.js.map
 ┃ ┃ ┃ ┣ 📜swagger-ui-es-bundle-core.js
 ┃ ┃ ┃ ┣ 📜swagger-ui-es-bundle-core.js.map
 ┃ ┃ ┃ ┣ 📜swagger-ui-es-bundle.js
 ┃ ┃ ┃ ┣ 📜swagger-ui-es-bundle.js.map
 ┃ ┃ ┃ ┣ 📜swagger-ui-standalone-preset.js
 ┃ ┃ ┃ ┣ 📜swagger-ui-standalone-preset.js.map
 ┃ ┃ ┃ ┣ 📜swagger-ui.css
 ┃ ┃ ┃ ┣ 📜swagger-ui.css.map
 ┃ ┃ ┃ ┗ 📜swagger-ui.js.map
 ┃ ┃ ┣ 📜README
 ┃ ┃ ┣ 📜immutable.js
 ┃ ┃ ┣ 📜immutable.min.js
 ┃ ┃ ┣ 📜insQ.js
 ┃ ┃ ┣ 📜insQ.min.js
 ┃ ┃ ┣ 📜redoc-init.js
 ┃ ┃ ┣ 📜style.css
 ┃ ┃ ┗ 📜swagger-ui-init.js
 ┃ ┗ 📂rest_framework
 ┃ ┃ ┣ 📂css
 ┃ ┃ ┃ ┣ 📜bootstrap-theme.min.css
 ┃ ┃ ┃ ┣ 📜bootstrap-theme.min.css.map
 ┃ ┃ ┃ ┣ 📜bootstrap-tweaks.css
 ┃ ┃ ┃ ┣ 📜bootstrap.min.css
 ┃ ┃ ┃ ┣ 📜bootstrap.min.css.map
 ┃ ┃ ┃ ┣ 📜default.css
 ┃ ┃ ┃ ┣ 📜font-awesome-4.0.3.css
 ┃ ┃ ┃ ┗ 📜prettify.css
 ┃ ┃ ┣ 📂docs
 ┃ ┃ ┃ ┣ 📂css
 ┃ ┃ ┃ ┃ ┣ 📜base.css
 ┃ ┃ ┃ ┃ ┣ 📜highlight.css
 ┃ ┃ ┃ ┃ ┗ 📜jquery.json-view.min.css
 ┃ ┃ ┃ ┣ 📂img
 ┃ ┃ ┃ ┃ ┣ 📜favicon.ico
 ┃ ┃ ┃ ┃ ┗ 📜grid.png
 ┃ ┃ ┃ ┗ 📂js
 ┃ ┃ ┃ ┃ ┣ 📜api.js
 ┃ ┃ ┃ ┃ ┣ 📜highlight.pack.js
 ┃ ┃ ┃ ┃ ┗ 📜jquery.json-view.min.js
 ┃ ┃ ┣ 📂fonts
 ┃ ┃ ┃ ┣ 📜fontawesome-webfont.eot
 ┃ ┃ ┃ ┣ 📜fontawesome-webfont.svg
 ┃ ┃ ┃ ┣ 📜fontawesome-webfont.ttf
 ┃ ┃ ┃ ┣ 📜fontawesome-webfont.woff
 ┃ ┃ ┃ ┣ 📜glyphicons-halflings-regular.eot
 ┃ ┃ ┃ ┣ 📜glyphicons-halflings-regular.svg
 ┃ ┃ ┃ ┣ 📜glyphicons-halflings-regular.ttf
 ┃ ┃ ┃ ┣ 📜glyphicons-halflings-regular.woff
 ┃ ┃ ┃ ┗ 📜glyphicons-halflings-regular.woff2
 ┃ ┃ ┣ 📂img
 ┃ ┃ ┃ ┣ 📜glyphicons-halflings-white.png
 ┃ ┃ ┃ ┣ 📜glyphicons-halflings.png
 ┃ ┃ ┃ ┗ 📜grid.png
 ┃ ┃ ┗ 📂js
 ┃ ┃ ┃ ┣ 📜ajax-form.js
 ┃ ┃ ┃ ┣ 📜bootstrap.min.js
 ┃ ┃ ┃ ┣ 📜coreapi-0.1.1.js
 ┃ ┃ ┃ ┣ 📜csrf.js
 ┃ ┃ ┃ ┣ 📜default.js
 ┃ ┃ ┃ ┣ 📜jquery-3.5.1.min.js
 ┃ ┃ ┃ ┗ 📜prettify-min.js
 ┣ 📜.git
 ┣ 📜.gitignore
 ┣ 📜Dockerfile
 ┣ 📜README.md
 ┣ 📜manage.py
 ┗ 📜requirements.txt
```
  
## API


### swagger
<div markdown="1">

![image](https://user-images.githubusercontent.com/112836685/215753323-26257498-ce14-435b-9bd6-def0dc1f64f7.png)

Swagger를 통해 API 명세서를 작성하였습니다.

</div>

## Celery

![image](https://user-images.githubusercontent.com/112836685/216561527-76405ebd-7106-484e-a951-109bbe986fe7.png)

Celery를 활용해 비교적 오래걸리는 독초 판별 서비스를 비동기로 처리하였습니다. 또한 Polling 방식을 활용해 celery가 요청처리중에도 다른 요청들을 받을 수 있게 구현하였습니다.

## DataBase

![image](https://user-images.githubusercontent.com/112836685/216560324-b395023a-3dcd-4029-93a1-889efc53d3c8.png)

MongoDB Atlas Search를 사용하여 꽃 이름 유사어 검색 및 다중검색이 가능하도록 검색엔진을 구현하였습니다.또한 Scheduler 를 활용하여 1시간 단위로 Database의 값을 update 해주는 Ranking System을 구현하였습니다.

## Monitoring
Grafana + Prometheus, ELK

|**Django** |**Node exporter**|
|-----|-----|
<img src = "https://user-images.githubusercontent.com/112836685/215755917-d95d1f67-284e-46bc-bb1a-4b4d60d0248d.png" width="500px" height="300px">|<img src = "https://user-images.githubusercontent.com/112836685/215756393-afd0c358-198c-475b-afc4-2a61ef44a20d.png" width="500px" height="300px">


|**cAdvisor** |**ELK**|
|-----|-----|
<img src = "https://user-images.githubusercontent.com/112836685/215756456-c339b819-463f-4b1b-9434-075df74f3684.png" width="500px" height="300px">|<img src = "https://user-images.githubusercontent.com/112836685/216101722-55819672-9a8e-4165-b45e-6b42f7b3f101.png" width="500px" height="300px">
  
Django에서 Prometheus를 통해 request,response에 대한 정보를 수집을 한 후 Grafana를 통해 시각화 하였습니다.
Slack과 Grafana를 연동하여 설정한 CPU 사용량 범위를 벗어날 경우 Slack에 경고 알림이 오도록 구현하였습니다.
CAdvisor를 활용해 각 컨테이너의 cpu, memory사용량등을 알수 있게 하였고, 컨테이너별 네트워크 사용량을 알수있게하였습니다.
node exporter를 통해 서버의 메모리, cpu 사용량, network traffic 등을 알수있게 하였습니다.

ELK 스택을 활용하여 nginx log를 모니터링하고, 시간대, 사이트별 응답코드, 응답코드 비율등을 모니터링 할 수 있게 설계하였습니다.
</details>  



  
<details>
<summary><h3>AI</h3></summary>

## File Directory
 
```
📦AI
 ┣ 📂.github
 ┃ ┣ 📂ISSUE_TEMPLATE
 ┃ ┃ ┣ 📜error-report.md
 ┃ ┃ ┣ 📜feature-request.md
 ┃ ┃ ┣ 📜refactoring-report.md
 ┃ ┃ ┗ 📜setting-report.md
 ┃ ┗ 📜PULL_REQUEST_TEMPLATE.md
 ┣ 📜.git
 ┣ 📜.gitignore
 ┣ 📜Dockerfile
 ┣ 📜README.md
 ┣ 📜app.py
 ┣ 📜lb6.pickle
 ┣ 📜p6flower.model
 ┗ 📜requirements.txt
```

## Model

![image](https://user-images.githubusercontent.com/112836685/216560396-24ca23a8-fd15-45af-a03c-4e681da66d04.png)

카카오 오픈 api인 crawling과 Kaggle을 통해 데이터셋을 확보하였고 MobileNet V2 모델을 학습 시켰습니다.

![image](https://user-images.githubusercontent.com/112836685/216560570-0b780ca7-d0ee-4f34-92f3-960a4472f53f.png)

해당 이미지는 학습된 모델의 평가 지표입니다. 약 90%의 정확도와 꽤 낮은 손실값을 가지고 있는 것을 확인할 수 있고 모델이 over fitting 되지 않은 것을 확인 할 수 있습니다.

</details> 
 

  
<details>
<summary><h3>Devops</h3></summary>


## HTTPS

![image](https://user-images.githubusercontent.com/112836685/216560063-cbd003b8-e160-488a-a6ba-ffc83c925f18.png)

SSL인증서를 발급받아 Https를 적용하여 웹사이트의 무결성을 보호하도록 하였습니다.

## Github Actions

Github Actions를 통해 CI/CD 파이프라인을 구축하여 코드 변경사항을 서버에 원할하게 반영할 수 있게 하였습니다.

</details>
  
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
  
## Our Team

| Name    | <center>이상민</center>|<center>한정욱</center> |<center>강석규</center> | 
| ------- | --------------------------------------------- | ------------------------------------ | --------------------------------------------- | 
| Profile | <center> <img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/83197138?v=4" /> </center>|<center><img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/101189924?v=4" /></center>|<center><img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/8746067?v=4" /></center>|
| role    | <center>Team Leader<br> Frontend, DevOps</center>   | <center>Frontend, <br> DevOps</center>    | <center>Frontend ,<br> DevOps</center>  | 
GitHub | <center>[@sangminlee98](https://github.com/sangminlee98)</center> | <center>[@nowrobin](https://github.com/nowrobin) </center>| <center>[@AlgeMoya](https://github.com/AlgeMoya) </center>|



| Name    | <center>강기환</center> | <center>이준우</center> | <center>박영식</center> | <center>정동훈</center>
| ------- | --------------------------------------- | --------------------------------------- | --------------------------------------- | --------------------------------------- |
| Profile |<center><img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/100124081?s=400&v=4" /></center>|<center><img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/107318116?v=4" /></center>|<center><img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/99026631?v=4" /></center>|<center><img width="110px" height="110px" src="https://avatars.githubusercontent.com/u/112836685?s=400&v=4" /></center>|
| role    | <center>Bakcend ,<br> DevOps, <br> AI</center> | <center>Backend,<br> DevOps</center> | <center>Backend,<br> DevOps</center> | <center>Backend,<br> DevOps</center> |
GitHub | <center>[@GiHwan2](https://github.com/GiHwan2)</center> | <center>[@JunRain2](https://github.com/JunRain2) </center>| <center>[@0sik](https://github.com/0sik) </center>| <center>[@jjeongdong](https://github.com/jjeongdong)</center>





</div>
