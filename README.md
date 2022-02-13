# Chat Demo

### Setup
1. node.js 설치 후

2. npm init -y : package.json 생성

3. npm install express socket.io moment : 소켓, 시간을 위한 라이브러리 설치

4. npm install -g nodemon : js 파일에 변경이 있을때마다 서버를 재실행
    ```
    PS D:\VanillaJS\chat> npm init -y
    PS D:\VanillaJS\chat> npm install express socket.io moment
    PS D:\VanillaJS\chat> npm install -g nodemon
    ```
5. app.js 생성 : 서버를 구동하는 파일
6. src폴더 생성 : HTML, CSS, JS 포함
 
* * *
### Etc

- socket.emit() : 보냄, socket.on() : 받음

- vscode 확장메뉴 : Liver server 설치

- nodemon 실행
  ```console
  PS D:\VanillaJS\chat> nodemon app.js 
  ```

package.json 에서 start 로 명령어 추가
```json
  "scripts": {
    "start": "nodemon app.js"
  },
```
```
PS D:\VanillaJS\chat>npm start
```
* * *
