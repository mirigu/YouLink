## YOULINK

내가 직접 만들어가는 유튜브링크 사이트! <br>
나만의 유튜브 취향을 모두와 공유하고 <br>
나와 취향이 같은 사람들의 유튜브 리스트를 확인할 수 있는 플랫폼 입니다.

<br>

## 1. 제작 기간 & 팀원 소개
- 2021년 11월 10일 ~ 2021년 11월 13일
- 4인 1조 팀 프로젝트

<br>

## 2. 사용 기술
`Back-end`
- Python 3
- Flask 2.0.2
- MongoDB 4.0.1
- bs4 0.0.1

`Front-end`
- JQuery 3.5.1
- Bulma 0.9.3

`deploy`
- AWS EC2 (Ubuntu 18.04 LTS)

<br>

## 3. 실행화면

자세한 영상 : https://www.youtube.com/watch?v=J_VsdLSu-Nw

<br>

## 4. 핵심기능

+ **로그인, 회원가입 기능**   
  : JWT를 이용, 로그인과 회원가입 구현
  : 아이디, 닉네임 중복확인 가능
  : hash로 비밀번호 암호화

+ **로그아웃 기능**   
  : removecookie 코드를 이용해 로그아웃 기능 구현
  
+ **메인페이지 jinja 언어 사용**   
  : 로그인시 메인페이지 사용자 닉네임 보이게 구현

+ **유튜브 채널**      
  : JWT를 이용, 사용자별 게시 내용 확인 가능
  : youtube 채널 url을 입력시 채널의 프로필 이미지, url을 웹스크래핑

<br>

## 5. 개인 회고
