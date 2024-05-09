## DaliyTracks
* 개발시작:2024-05-02
* 예상마감일:2024-05-31
* 개발인원:2명
  * 강태현
  * 최효진
  
### 프로젝트 개요
DailyTracks는 지도 위에 사람들의 일상을 기록하는 라이프 로깅 플랫폼입니다. 사용자는 지도를 클릭하여 해당 지역의 일상 기록을 확인할 수 있습니다. 지도는 실시간으로 해당 지역의 인기도에 따라 색상이 변경됩니다.

### 개발 일정
![image](https://github.com/DailyTracks/.github/assets/126179088/d5585b84-be14-40cd-b447-0da7bc534303)

### 예상 설계안(feat. 최효진)
![image](https://github.com/DailyTracks/.github/assets/126179088/38d95831-be49-420e-9f7f-1b859554cc63)

### ERD
<img src="https://github.com/DailyTracks/.github/assets/126179088/79d1e14b-f727-4d7e-8fc4-58cb8f405860" width="600px"/>

### 엔드포인트 명세서
> BASE URL : http://host:port/api
<img src="https://github.com/DailyTracks/.github/assets/126179088/b881c8c7-000e-40ff-ad9e-3458f53e7ef1" width="500px"/>

<img src="https://github.com/DailyTracks/.github/assets/126179088/1d9d5830-e020-4e38-9ba7-7ee069127108" width="500px"/>


### 개발 환경
* backend
  * infra
    * AWS EC2 (계획중)
    * AWS RDS
  * database
    * mysql
    * redis 
  * framework
    * express
  * library usage
    * auth service
      * passport-naver-v2
      * passport-kakao
      * express-session
    * chat service
      * socket.io
    * ORM
      * sequelize-auto
      * sequelize
    * end-point docs
      * swagger
    * logging
      * winston
* frontend
  * infra
    * AWS EC2 (계획중)
  * framework : react
  * library usage : leaflet

> 추후 변경 될 예정





