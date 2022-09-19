#몽고DB 맥M1 터미널 명령어
 
--서버시작

brew services start mongodb-community@5.0

--서버중지

brew services stop mongodb-community@5.0

--서버 실행시 mongodb 주소
http://localhost:27017/

#몽고DB Node.js 연동

cd 연결할 프로젝트 위치로 이동

아래의 명령어를 입력하여 연결환경을 구축한다.

npm install mongodb --save

아래의 명령어로 프로젝트를 실행한다.

node server.js

