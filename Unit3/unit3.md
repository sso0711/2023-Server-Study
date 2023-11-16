### ⭐️ 3주차 과제 제출 ⭐️

## ❗️ 강의 수강 여부
수강한 강의에 체크표시 해주세요~

- [x] 리눅스
- [x] URL,URI
- [x] AWS
- [x] 프록시 서버
- [x] HTTPS

<br>

## ❗️ notion에 키워드 정리 완료 여부
내가 notion에 키워드를 정리를 완료한 경우 체크표시 해주세요~

- [ ] 키워드 정리 완료

<br>

## ❗️ 3주차 과제
1. AWS EC2 인스턴스 생성
   - 수행한 화면 혹은 내용을 작성해 주세요

<br/>

2. ssh 사용하여 ubuntu 인스턴스 외부 접속
   - 수행한 화면 혹은 내용을 작성해 주세요

<br/>

3. Nginx 패키지 설치 후 http 외부 접속
   - 수행한 화면 혹은 내용을 작성해 주세요
  
3-1. 
먼저 `sudo yum update`명령어를 통해 패키지들을 최신 상태로 업데이트 해준다.

3-2.
![image](https://github.com/sso0711/2023-Server-Study/assets/74605283/296802af-29c7-4fb7-9c4d-cbe89b872a59)
(vscode에서 ssh접속오류를 해결하지 못해 일단은 aws 웹 상에서 인스턴스에 연결하여 진행하였다.)
nginx를 인스턴스에 설치하였다.

3-3.
![image](https://github.com/sso0711/2023-Server-Study/assets/74605283/8eecf98b-63e8-4f86-9195-527395df3d50)
`sudo ufw allow 'Nginx HTTP'` 명령어로 방화벽 설정을 해주려 하였으나, Amazon linux에서는 ufw 사용이 불가능해서 대신 보안그룹의 인바운드 규칙에 직접 추가해주었다.

3-4.
![image](https://github.com/sso0711/2023-Server-Study/assets/74605283/c00f2723-9ce7-4a7b-8339-fc0a6369e277)
명령어로 nginx를 실행시키면
로 active(running)상태임을 확인할 수 있다.
<br/>

4. 가비아 or 후이즈에서 domain 연결 (.shop 도메인)
   - 수행한 화면 혹은 내용을 작성해 주세요

<br/>

5. 가비아 or 후이즈에서 domain 연결 (.shop 도메인)
   - 수행한 화면 혹은 내용을 작성해 주세요

<br/>

6. Sub Domain 적용 (test)
   - 수행한 화면 혹은 내용을 작성해 주세요

<br/>

7. Redirection 적용 (IP to Domain)
   - 수행한 화면 혹은 내용을 작성해 주세요

<br/>

