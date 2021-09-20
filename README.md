# Nest
# 프로젝트 실행 방법

Example of file: 

    DATABASE_URL=<your url>  
    JWT_SECRET=123123124124

## .env 파일을 추가한 후 개발 모드에서 백엔드 시작
`cd api`  
`npm install`  
`npm run start:dev`  
  
## .env 파일을 추가한 후 개발 모드에서 프론트엔드를 시작합니다.
`cd frontend`    
`npm install`  
`ng serve`  

## e2e 테스트 시작
`cd e2e`    
`npm install`  
`npm run cypress:open`
### e2e 리포트 생성 (html)
`npm run cypress:report`
