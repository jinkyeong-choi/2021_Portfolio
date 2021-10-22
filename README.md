# 20211008_Carrot_Streaming_Market
### 당근 스트리밍 마켓
<br><br>
<img src="https://user-images.githubusercontent.com/92618553/138397148-70867060-456e-4cef-9e1f-9c76a37abf63.PNG" width="30%" height="30%"><br><br><br>
목표
---
번호를 직접 교환하지 않고도 실시간 스트리밍으로 물품 인증할 수 있다. 구매할 때 경매기능을 넣어 중고거래에 재미를 추가했다.<br><br><br>



개발환경
---
서버 : Windows 10 / Visual Studio community 2019 16.11.3 / C++  / DBeaver 21.1.3 / MySQL 8.025(Win64 on x86_64)<br>
클라이언트 : Windows 10 / WinForm .Net Framework 4.7.2 / C#<br><br><br>



담당 파트
---
C# 클라이언트 작성 및 UI 구현<br><br><br>


프로젝트 기간
---
2021.09.27 ~ 2021.10.08 (4명)<br><br><br>


주요 기능
---
**1. 물품 인증을 위한 스트리밍 서비스**<br>
 -UDP와 FFmpeg, VLC를 이용해 채팅방에 접속한 사람에게 실시간 화면 전송<br><br>
**2. 경매판매**<br>
 -입찰하면 최고가 갱신<br><br>
**3. 판매완료 및 리뷰 작성**<br>
 -판매자는 구매자를 선택하고 리뷰 작성<br>
 -구매자는 본인이 구매완료한 물품에 대해 리뷰 작성<br><br><br>



사전조사 및 소감
---
<img src="https://user-images.githubusercontent.com/92618553/138396576-2b5c0e3f-e94c-4cd8-b959-dfda98ba485d.PNG" width="50%"  height="50%"><br><br><br>



개발완료보고서
---
<img src = "https://user-images.githubusercontent.com/92618553/138397318-525b5bdc-175b-412a-a0bd-fb6070e4534e.PNG" width="70%" height="70%"><br><br><br>



UI 흐름
---
<img src = "https://user-images.githubusercontent.com/92618553/138397434-5ed496d2-1123-4871-9010-e4ee2b4a1896.PNG" width="60%" height="60%"><br><br><br>



요구사항 분석서
---
<img src = "https://user-images.githubusercontent.com/92618553/138397601-dd4cd01a-f296-4313-a3c1-3aeaaaecfda7.PNG" width="80%" height="80%"><br><br><br>



작동사진
---
> ### 홈<br> 
 : 회원가입, 로그인 후 홈화면<br>
<img src = "https://user-images.githubusercontent.com/92618553/138397687-c37606d2-e95c-4143-9be8-bad50b11fc17.PNG" width="50%" height="50%"><br><br><br>

> ### 일반판매 게시글 작성<br>
 : 게시글을 작성하면 바로 서버로 전송<br>
<img src = "https://user-images.githubusercontent.com/92618553/138397692-e82ff4f5-7dcd-4827-8fd4-a1e0320ab603.PNG" width="50%" height="50%"><br><br><br>

> ### 경매판매 게시글 작성<br>
: 경매판매 게시글은 제한시간 적용<br>
<img src = "https://user-images.githubusercontent.com/92618553/138397703-3f437b3c-4b5d-4d9f-bde8-8c32e76ba94d.PNG" width="50%" height="50%"><br><br><br>

> ### 경매판매 게시글 페이지<br>
: 본인 게시글에 입찰 불가, 최고가보다 높아야 입찰 가능<br>
<img src = "https://user-images.githubusercontent.com/92618553/138397713-1c875667-ed29-42fe-8385-46593da9a1d0.PNG" width="40%" height="40%"><br><br><br>

> ### 채팅방<br>
: 상대방과 실시간으로 채팅 가능<br>
<img src = "https://user-images.githubusercontent.com/92618553/138398670-b52cfa39-95da-4ab1-942c-6c3a9455fa4f.PNG" width="50%" height="50%"><br><br><br>

> ### 채팅방에서 실시간 스트리밍<br>
: 채팅과 실시간 스트리밍 동시에 진행<br>
<img src = "https://user-images.githubusercontent.com/92618553/138397768-322c551f-d4ac-4d33-b6e2-0abb1f9aa9a2.PNG" width="50%" height="50%"><br><br><br>

> ### 마이프로필<br>
: 상대방의 리뷰를 기반으로 신뢰도 설정<br>
<img src = "https://user-images.githubusercontent.com/92618553/138397815-ca3d87b9-c625-4886-bdb3-9493080b5fd9.PNG" width="50%" height="50%"><br><br><br>

> ### 판매내역 및 구매내역<br>
: 판매자는 판매완료를 눌러 구매자 선택 후 리뷰 작성 가능, 구매자는 구매내역에서 리뷰 작성<br>
<img src = "https://user-images.githubusercontent.com/92618553/138397799-a12e5854-593d-4608-8ff4-1f5900e623de.PNG" width="50%" height="50%"><br><br><br>






