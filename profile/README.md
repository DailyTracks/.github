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
![image](https://github.com/DailyTracks/.github/assets/126179088/9d8b0f86-c379-4ad3-9d6f-07abc1951582)


### 엔드포인트 명세서
> BASE URL : http://host:port/api
![image](https://github.com/DailyTracks/.github/assets/126179088/7f3cd865-885a-4d9c-8a6a-7ecac4508154)
![image](https://github.com/DailyTracks/.github/assets/126179088/82df5b26-957f-453a-8593-e8fb95e3c354)
![image](https://github.com/DailyTracks/.github/assets/126179088/5d634ec9-18a8-45bf-b7ea-74fbcea0e3f0)

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





