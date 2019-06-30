# ROS_server

* turtlebot3와 app을 연동해주는 server입니다.

```
운영체제 : ubuntu 16.04, ROS
프레임워크 : flask 
```

* **주의사항**  
server 실행 전 ```roscore``` 먼저 실행할 것


### server 실행 방법
1. git clone 
2. cd turtlebot3_flask/scripts 경로로 
3. 실행 명령어 "python turtlebot3_flask" 

### fuse 연동
1. ngrok 에 나오는 http 부분 url 복사
2. fuse에 pages 폴더의 js 파일
3. fetch 부분 url 변경 후 실행

### ngrok 설치 및 실행 방법
1. ngrok 설치 => https://ngrok.com/download
2. 설치 단계중 "sign up for free" 회원가입
3. 이후 3번 단계에 나오는 명령어 입력 
4. 4번 실행 하면 "./ngrok http 5002"


