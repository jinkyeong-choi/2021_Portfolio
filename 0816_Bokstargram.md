# Bok stargram
<br><br>
<img src="https://user-images.githubusercontent.com/92618553/138406279-accebf90-7992-4dc7-a85c-e0c1f99d603d.PNG" width="30%" height="30%"><br><br><br>

소개
---
게시글을 올리고 댓글을 달아 SNS 유저들과 소통하는 SNS 프로그램.<br>
프로필을 편집하고 게시글도 올린다. 홈에서 출력되는 다른 회원들의 게시글을 보고 댓글을 달거나, 좋아요를 누르고, 해당 게시글 작성자의 프로필을 확인할 수 있다.<br><br><br>



개발환경
---
서버 : Windows 10 / Visual Studio community 2019 16.11.3 / C# / DBeaver 21.1.3 / MySQL 8.025(Win64 on x86_64)<br>
클라이언트 : Windows 10 / WinForm .Net Framework 4.7.2 / C#<br><br><br>



담당 파트
---
C# 클라이언트 작성 및 UI 구현<br><br><br>


프로젝트 기간
---
2021.08.13 ~ 2021.08.16 (2명)<br><br><br>


주요 기능
---
**1. 이미지 송수신**<br>
 -C# 서버와 C# 클라이언트 간 이미지 송수신<br>
 -서버에서 받아온 이미지를 게시글과 프로필사진 칸에 넣는다.<br><br>
**2. 페이지 넘기기**<br>
 -게시글을 넘길 때 다음 순서의 게시글의 정보를 받아 출력한다.<br>
 -다음페이지나 이전페이지로 넘어갈 때 본인의 게시글이 아닌 다른 회원의 게시글을 순서대로 가져온다.<br><br><br>



사전조사 및 소감
---
<img src="" width="50%"  height="50%"><br><br><br>



개발완료보고서
---
<img src = "https://user-images.githubusercontent.com/92618553/138406286-f34cac30-d338-48e0-80fa-d365464bf890.PNG" width="70%" height="70%"><br><br><br>



UI 흐름
---
<img src = "https://user-images.githubusercontent.com/92618553/138406301-1a79ffba-6234-48b6-89db-61248b0e1856.PNG" width="60%" height="60%"><br><br><br>



요구사항 분석서
---
<img src = "https://user-images.githubusercontent.com/92618553/138406308-3304c6ba-a9c6-43f3-b8ed-a2aa3ae2dcb2.PNG" width="80%" height="80%"><br><br><br>


작동 영상
---
https://user-images.githubusercontent.com/92618553/138409582-0bed4f3a-2f2d-4d1b-9d5f-7a0ba9b3a61d.mp4

https://user-images.githubusercontent.com/92618553/138409588-f8fc8e3b-3d8e-4f05-945e-6e47b3e8f378.mp4

<br><br><br>


작동 사진
---
> ### 로그인<br> 
 : 아이디와 비밀번호를 입력하는 텍스트박스의 테두리를 없애고, 색상을 변경해 깔끔하게 표현했다.<br>
<img src = "https://user-images.githubusercontent.com/92618553/138406343-9be415a8-6f21-47ae-a44b-2afa30dc89d3.PNG" width="50%" height="50%"><br><br><br>

> ### 회원가입<br> 
<img src = "https://user-images.githubusercontent.com/92618553/138406357-e387ede0-69c0-41ed-95c4-ef4dce4dc179.PNG" width="50%" height="50%"><br><br><br>

> ### 홈<br> 
 : 본인을 제외한 다른 유저들의 최근 게시글을 보여준다.<br>
<img src = "https://user-images.githubusercontent.com/92618553/138406371-8d69685a-126f-4294-8ef5-45d51e502e87.PNG" width="50%" height="50%"><br><br><br>

> ### 마이페이지<br> 
<img src = "https://user-images.githubusercontent.com/92618553/138406398-a1c6cf24-acca-410d-8d59-3e349e5a8cc3.PNG" width="50%" height="50%"><br><br><br>

> ### 게시글 작성<br> 
 : 게시글을 작성하면 서버를 통해 DB에 게시글이 저장된다.<br>
<img src = "https://user-images.githubusercontent.com/92618553/138406417-21bbfe1e-d441-4b08-969e-f521fdb18961.PNG" width="50%" height="50%"><br><br><br>

> ### 친구 검색<br> 
 : 이름을 검색하면 서버를 통해 검색되는 회원의 프로필을 가져온다.<br>
<img src = "https://user-images.githubusercontent.com/92618553/138406442-0d30d554-63fa-490b-bf5e-15067cf480e6.PNG" width="50%" height="50%"><br><br><br>


