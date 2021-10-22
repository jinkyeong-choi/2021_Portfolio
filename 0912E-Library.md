# E-Library
<br><br>
<img src="https://user-images.githubusercontent.com/92618553/138402052-05b88d2a-4157-424f-aee2-24ee4e624b2b.PNG" width="40%" height="40%"><br><br><br>


목표
---
TCP/IP로 서버와 사서, 유저용 프로그램간 회원정보 및 도서정보를 송수신한다. 로그인된 계정에 따라 사서, 유저로 나뉜다.<br><br><br>


개발환경
---
서버 : Windows 10 / Visual Studio 2019 16.11.3 / C++ / DBeaver 21.1.3 / MySQL 8.025(Win64 on x86_64)<br>
클라이언트 : Windows 10 / WinForm .Net Framework 4.7.2 / C#<br><br><br>



담당 파트
---
C++ 서버 구현 및 DB 핸들링<br><br><br>


프로젝트 기간
---
2021.09.07 ~ 2021.09.12 (4명)<br><br><br>


주요 기능
---
**1. TCP/IP**<br>
 -스레드로 클라이언트 다중 연결<br>
 -데이터 및 이미지 송수신<br>
**2. DB**<br>
 -회원정보 및 대여정보 저장<br>
 -특정 조건으로 검색 후 원하는 개수만큼 데이터 취득<br><br>
**3. 맞춤도서추천**<br>
 -유저가 선택한 관심분야에 맞는 도서 3종 추천<br><br>



개발완료보고서
---
<img src = "https://user-images.githubusercontent.com/92618553/138402093-f73637c5-227b-4ae1-8779-4d6f3e3de079.PNG" width="60%" height="60%"><br><br><br>



UI 흐름
---
<img src = "https://user-images.githubusercontent.com/92618553/138402111-83311e3b-fb8c-4b41-9875-4f20d5efe1f1.PNG" width="70%" height="70%"><br><br><br>



요구사항 분석서
---
<img src = "https://user-images.githubusercontent.com/92618553/138402121-b2536fb4-2443-4f39-89b9-b0ab115e25d7.PNG" width="80%" height="80%"><br><br><br>


작동 영상
---

<br><br><br>



작동 사진
---
> ### 메인화면<br> 
 : <br>
<img src = "https://user-images.githubusercontent.com/92618553/138402649-253665c4-fb5f-4487-93fd-8f1c3e51d9d5.PNG" width="70%" height="70%"><br><br><br>

> ### 로그인화면<br> 
 : <br>
<img src = "https://user-images.githubusercontent.com/92618553/138402652-ff118379-9a9e-426b-9d5e-0066f06f8b10.PNG" width="70%" height="70%"><br><br><br>

> ### 회원가입<br> 
 : <br>
<img src = "https://user-images.githubusercontent.com/92618553/138402664-fda125ff-f184-4d84-afee-d7675266e7f4.PNG" width="80%" height="80%"><br><br><br>

> ### 로그인 후 메인화면<br> 
 : <br>
<img src = "https://user-images.githubusercontent.com/92618553/138402679-61480a8b-a1a1-472f-bb25-c2d183037323.PNG" width="70%" height="70%"><br><br><br>

> ### 도서대여<br> 
 : 대출가능여부가 대출붕가능일 때 '대여하기' 버튼 클릭 불가<br>
<img src = "https://user-images.githubusercontent.com/92618553/138402697-b9ebd6e8-55d1-4132-9c0f-621bc3153519.PNG" width="70%" height="70%"><br><br><br>

> ### 마이페이지<br> 
 : 마이페이지에서 대여 중인 도서 확인 가능<br>
<img src = "https://user-images.githubusercontent.com/92618553/138402704-34d9a2db-f23d-4b08-8af0-e93b4d5397a4.PNG" width="40%" height="40%"><br><br><br>

> ### 사서 - 유저 검색 및 대여목록 확인<br> 
 : <br>
<img src = "https://user-images.githubusercontent.com/92618553/138402726-bb631e4f-8d98-4416-bac8-04fefbe8115d.PNG" width="70%" height="70%"><br><br><br>

> ### 사서 - 신규도서 추가<br> 
 : 사서가 신규도서를 추가하면 DB의 도서 목록에 추가<br>
<img src = "https://user-images.githubusercontent.com/92618553/138402734-f2a57078-6c0a-4690-a402-373663eadb30.PNG" width="70%" height="70%"><br><br><br>

> ### 이미지 저장<br> 
 : 신규도서의 이미지는 서버 컴퓨터에 저장한다. 이 때 이미지의 제목은 ISBN을 기준으로 저장한다.<br>
<img src = "https://user-images.githubusercontent.com/92618553/138402744-7708b5fe-9af8-4ea4-912c-4ce3bec5515a.PNG" width="70%" height="70%"><br><br><br>

> ### DB - 도서목록 및 도서대출내역<br> 
<img src = "https://user-images.githubusercontent.com/92618553/138402768-d336413d-10d8-4cbf-ad4d-8728bdd3a50a.PNG" width="70%" height="70%"><br><br><br>



