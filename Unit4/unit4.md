### ⭐️ 4주차 과제 제출 ⭐️

## ❗️ 강의 수강 여부
수강한 강의에 체크표시 해주세요~

- [o] 데이터베이스
- [o] 데이터베이스_MySQL
- [o] 리눅스에 MySQL 설치하기

<br>

## ❗️ 3주차 과제
1. 관계형 데이터베이스 이론적으로 이해하기
   - 간단히 여러분이 공부한 내용을 적어주세요.


<br/>
데이터 베이스는 여러 사람이 공유하여 사용하기 위해서 데이터를 체계화해서 통합,관리하는 데이터 집합이다. 엑셀과 다른 점은 여러 사람이 동시에 공유할 수 있고, 중복된 데이터를 삭제할 수 있다는 점이다. 세개이 데이터베이스 종류가있는데, 지금 상용화된건 관계형 데이터베이스다. 그 예시가 MySQL.

2. 원하는 서비스(당근마켓, 인스타그램 등) 분석하기
   - 원하는 서비스를 하나 타겟팅 후 페이지 4장가량을 선정하고 (캡쳐본 올리기) 데이터베이스에 들어갈 내용을 적어주세요.


<br/>
![image](https://github.com/hyeeey/2024_Server_study_Basic/assets/145014275/e927a438-b436-4a26-b463-b6d015946e73)
![image](https://github.com/hyeeey/2024_Server_study_Basic/assets/145014275/3c8ed5a1-0e82-4d67-a704-4c9a1c4c1e6e)
![image](https://github.com/hyeeey/2024_Server_study_Basic/assets/145014275/02cc6df6-977c-4dc6-90a5-12a685e9e7c5)
![image](https://github.com/hyeeey/2024_Server_study_Basic/assets/145014275/f52d78e0-b300-4fb6-9329-5adc69677526)
일단 entity 유저, 게시글, 댓글, 이미지,해시태그, 게시글 좋아요, 댓글 좋아요, 팔로우로 잡았당 
유저 속성에는 pk로 회원 id 넣고 나머지는 캡쳐본에 있는 이메일, 비밀번호, 휴대폰번호, 성별, 생일, 이름, 닉네임, 웹사이트, 소개, 프로필이미지를 넣었다 
게시글에는 pk로 게시글 id넣고/ 캡쳐본에 있는 본문, 위치태그, 회원 id를 넣고 회원 id를 FK로해서 유저에서 가져오게끔 했당 
이미지를 올려야하는데 pk로 이미지, 이름 넣고, 게시글 id를 fk로 넣어서 연결 해시태그는 pk로 해시태그id, 해시태그이름을 속성으로 넣었다.
나머지도 비슷하게 했다. 테이블 id를 pk로 가져오고 나머지는 fk로 위에 자세히 써놓은 entity랑 연결했다.

3. ERD 설계하기
   - 2번에서 진행한 내용을 바탕으로 직적 ERD 제작 툴을 사용해 작성해봅시다. (완성 후 캡쳐본 올리기)
![image](https://github.com/hyeeey/2024_Server_study_Basic/assets/145014275/847940cd-73ab-4d35-9566-ed5cfa6cd68b)


<br/>

4. AWS RDS 구축하기
   - ERD를 바탕으로 내가 기존에 만들어둔 AWS에서 RDS를 만들어 봅시다. (완성 후 캡쳐본)

<br/>
![image](https://github.com/hyeeey/2024_Server_study_Basic/assets/145014275/c8836f73-8e95-4807-8787-fc4e47dc5db0)
