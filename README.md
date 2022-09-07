# petSitter
# - 기술 소개서

팀 명 : 세나개(세상에 나쁜 개발자는 없다.)

팀 원 : 이예선, 노승민, 박주완, 김준혁

### 프로젝트 소개 – 누구나 돌봄요청을 할 수 있고, 누구나 돌봄 매니저가 될 수 있는 양방향 서비스 행복하개 돌볼고양입니다.

- 기획 의도 : 바쁜 현대 사회의 1인 가구와 반려동물을 키우는 사람들이 많아짐으로서 빠르고 쉽게 반려동물 돌봄 서비스를 제공하는 웹 사이트를 기획하였습니다.

# - DB ERD
##### Table : 8개
##### 컬럼 : 총 98개

- SITTER_INFO(매니저매칭정보) : 컬럼 14개
- TBL_CHARGE(결제) : 컬럼 4개
- TBL_MEMBER(고객) : 컬럼 15개
- TBL_MEMBER_AUTH(관리자) : 컬럼 2개
- TBL_REQUEST(돌봄요청하기 게시판) : 22개
- TBL_REQUEST_REPLY(돌봄요청하기 리플) : 컬럼 6개
- TBL_SITREQUEST(돌봄매니저소개 게시판) : 컬럼 14개
- TBL_SITREQUEST_REPLY(돌봄매니저소개 리플) : 컬럼 21개
<img src="https://user-images.githubusercontent.com/109937482/180920735-d3cf3c5e-f44a-4d8d-8b0d-5a226033849b.png">



### 회원가입
- 유효성 검사 : 컴퓨터 시스템에서 오류가 발생하지 않도록 처리하기 전에 모든 데이터가 올바른지 확인하는 것.

- 양식이 틀린 ID
<img src="https://user-images.githubusercontent.com/109937482/180906914-5a01ff06-b284-4bd6-90bd-782db921de8b.png">

- 존재하는 ID
<img src="https://user-images.githubusercontent.com/109937482/180906702-e956d29f-3a9c-45ec-81ef-6b9ebf45a5d1.png">

- 양식에 맞는 ID
<img src="https://user-images.githubusercontent.com/109937482/180907263-490ad321-78fe-4519-a425-ccc46bd4edbf.png">



### 비밀번호, 비밀번호 확인.
- 비밀번호가 틀릴 경우
<br>
<img src="https://user-images.githubusercontent.com/109937482/180907529-28a53881-5ee3-4406-9e5e-6d718dbce139.png"
     style="width:300px">

- 비밀번호 확인.
<img src="https://user-images.githubusercontent.com/109937482/180907714-08185092-05e4-405d-a7fb-9411aba9b31a.png">
<img src="https://user-images.githubusercontent.com/109937482/180907877-6e956745-3f6b-4182-9719-9fd0cbd8ef27.png">

### 주소찾기는 api는 Kakao Developers를 통해 사용하였습니다.
<img src="https://user-images.githubusercontent.com/109937482/180908513-e2e4b17b-961f-4408-9831-df30eb068145.png" style="width:300px">



### 이메일 인증(I'm port에서 api를 사용하였습니다.)
- 회원가입의 인증키를 받고 아이디 찾기, 비밀번호를 찾을 때 사용되며 자신의 메일로 인증키를 받을 수 있다.


- 양식에 맞지 않는 이메일
<img src="https://user-images.githubusercontent.com/109937482/180910070-7ce45b17-70f2-4de1-bf73-e58f2daec3f5.png">
<br>

- 존재하는 이메일
<img src="https://user-images.githubusercontent.com/109937482/180910308-a8d5a9df-048c-4f6b-adfe-890be264f71f.png">
<br>

- 사용 가능한 이메일
<img src="https://user-images.githubusercontent.com/109937482/180910403-1717833f-9be2-490b-b1a4-de992e7e124c.png">
<br>

- 이메일 인증
<img src="https://user-images.githubusercontent.com/109937482/180916132-469a4678-a8b7-4196-ba4a-ef944b6e65b4.png">
<img src="https://user-images.githubusercontent.com/109937482/180916784-70db6cc8-1e3c-446f-b03a-5b4de0a96ad5.png">
<br>

- 회원가입 완료
<img src="https://user-images.githubusercontent.com/109937482/180916952-0e06b264-56a4-4b69-99ad-faf708b21797.png">
<br>


### 아이디 찾기 : ID는 이메일로 찾을수 있습니다.
- 아이디 찾기
<img src="https://user-images.githubusercontent.com/109937482/180917093-428e966c-0675-4094-9fdb-e9b9f085f047.png"
     style="width:400px">
<br>

- 가입된 이메일이 없을때
<img src="https://user-images.githubusercontent.com/109937482/180917534-817dee1e-8697-40a8-b0b6-bff1171a74f2.png"
      style="width:400px">
<br>

- 양식에 맞지않는 이메일
<img src="https://user-images.githubusercontent.com/109937482/180918328-1e37fcd7-2371-4bc5-b304-ae1e53976b7f.png"
      style="width:400px">
<br>


### 비밀번호 찾기
- 아이디가 잘못 입력된 경우
<img src="https://user-images.githubusercontent.com/109937482/180918725-82a2cf47-3db5-47b6-be47-5a4fe528fa4c.png">
<br>
<br>

- 이메일이 잘못 입력된 경우
<img src="https://user-images.githubusercontent.com/109937482/180918928-5e08f3bc-05c8-41c4-8e5e-7fd007815eb3.png">
<br>
<br>

- 임시 비밀번호 발급 확인
<img src="https://user-images.githubusercontent.com/109937482/180919032-5aa2fa72-f29d-454d-9586-4272da7d69de.png">
<br>
<br>

- 임시 비밀번호 발급
<img src="https://user-images.githubusercontent.com/109937482/180919131-c266233d-5dc7-4dcb-b227-d0be2b006fbf.png">
<img src="https://user-images.githubusercontent.com/109937482/180919245-a97e0cad-0a95-4852-8385-41e8fa6b3a6c.png">
<br>
<br>

### 비밀번호 변경
- 마이페이지
<img src="https://user-images.githubusercontent.com/109937482/180919555-e511252d-53b9-4c73-9ebc-74f83154561f.png">
<br>

- 비밀번호 변경 페이지
<img src="https://user-images.githubusercontent.com/109937482/180919861-8ccda165-7941-4cf5-9193-47b9a46c6182.png">
<br>


### 돌봄페이 충전
<img src="https://user-images.githubusercontent.com/109937482/180920170-b012878c-2655-4bfc-9b54-1a06ebb772a2.png">
<br>


### 돌봄요청하기 게시판 : 서비스 이용자가 원하는 날짜, 시간, 페이를 등록하고 매니저들이 댓글을 등록하여 매칭이 이루어진다.
- 글목록, 글등록, 검색, 쪽번호 기능이 있다.
<img src="https://user-images.githubusercontent.com/109937482/180921294-aff91c52-0214-4adf-8f9c-af67264cf9be.png">

<br>

- 글등록
<img src="https://user-images.githubusercontent.com/109937482/180921726-a1b99c2f-7903-4362-ba04-f8f93b879ff1.png">
<br>

### 댓글
- 돌봄매니저가 댓글을 등록하였을때
<img src="https://user-images.githubusercontent.com/109937482/180922538-f2e0d9ef-5587-4821-96f4-c7b7253d7ed2.png">
<br>

- 이용자가 글작성 페이지에서 댓글을 봤을때
<img src="https://user-images.githubusercontent.com/109937482/180923254-f7309ab1-db0a-443f-9e4b-70b0a09bd08b.png">
<br>

- 매니저 정보 보기 : 별점, 리뷰 확인가능.
<img src="https://user-images.githubusercontent.com/109937482/180923379-97daf1f8-9ef8-4a6a-af53-1ee465ac4a0e.png">
<br>

### 요청자매칭정보 게시판 - 요청자가 매칭된 글을 확인하는 게시판입니다.
- 이 게시판은 이용자와 매니저가 매칭이 이루어진 정보가 확인 가능합니다. 하지만 다른사람의 글을 보는 것이 아니라 이용자 자신의 요청한 정보만 확인이 가능합니다.(마이 페이지처럼.)
- 이 게시판은 왼쪽과 오른쪽으로 나뉘며 왼쪽은 돌봄요청하기 게시판에서 매칭된 글의 정보가 보이고 오른쪽에서는 돌봄매니저소개 게시판에서 매칭된 글의 정보가 보입니다.
- 매칭이 이루어 지면 고객의 연락처를 카드안에서 확인할 수 있습니다.
<img src="https://user-images.githubusercontent.com/109937482/180924931-88b3f567-11f5-4e7c-850c-3742968baac6.png">


### 돌봄매니저소개 게시판 – 돌봄 서비스를 제공하는 매니저들의 서비스 지역 주소, 돌봄횟수, 별점을 확인하여 이용자에게 원하는 매니저를 선택할 수 있습니다.
<img src="https://user-images.githubusercontent.com/109937482/180925545-ee31453c-7ebc-4933-98be-61858fba392c.png">

<br>

- 원하는 매니저에게 요청할 수 있다.
<img src="https://user-images.githubusercontent.com/109937482/180926147-9f78912d-f77f-4f6c-b541-37c48fe9498b.png">
<br>

- 매니저에게 요청하면 댓글형식으로 남는다.
<img src="https://user-images.githubusercontent.com/109937482/180926215-51d93433-d1f4-40f3-8528-65cafbd1e876.png">
<br>

- 매니저에게 보이는 고객 정보
<img src="https://user-images.githubusercontent.com/109937482/180926382-c3f7d820-1531-4573-ad08-9aa127d4e9f9.png">
<br>

### 매니저매칭정보 게시판 : 이 게시판은 매니저들이 매칭된 정보들을 확인하는 게시판입니다. 
- 돌봄매니저소개에서 매칭된 정보가 매니저매칭정보로 넘어옵니다. 매니저의 개인매칭 정보만 확인이 가능하며 다른 매니저의 매칭 정보를 확인 할 수 없습니다.
- 요청자매칭정보 게시판과 같이 돌봄요청하기에서 매칭이 이루어진 것은 왼쪽에 정렬되어 보여지며 돌봄매니저소개에서 댓글로 매칭이 이루어진 것은 오른쪽에 정렬되어 보여집니다.
- 카드안에는 간단한 정보들을 볼 수 있으며 카드를 클릭하면 좀 더 자세한 내용을 확인할 수 있습니다.
<img src="https://user-images.githubusercontent.com/109937482/180926747-468c4c10-97f7-4f2d-a070-e2ba0d84db01.png">
<br>

### 리뷰기능 요청자매칭정보 게시판에서만 가능합니다.
- 이용자는 돌봄 서비스가 종료되어 요청자매칭정보에서 완료를 누르면 리뷰를 작성할 수 있습니다.
- 리뷰에는 이용자가 매니저에게 별점을 줄 수 있으며 서비스에 대한 후기를 작성할 수 있습니다.
<img src="https://user-images.githubusercontent.com/109937482/180927323-815ee75e-2bdb-43dc-add5-bf980d2e3948.png">
<br><br><br>

### 오류 경험
1. img 파일 업로드 오류
- 처음 교육원에서 진행한 세미 프로젝트에는 img파일을 스프링 폴더 안에 직접 저장해서 올렸으므로 글 등록시에 img오류가 없었다.
- 팀 프로젝트에서 진행한 img 업로드는 내 컴퓨터 경로를 servlet-context.xml에서 지정하여 올리기로 하였는데 팀원이 Export한 파일을 Import 하였을때 오류가 생겼다.

##### 해결
- 구글 검색을 통해 비슷한 오류를 알게 되었고 내 컴퓨터의 경로를 따로 저장하여 그때마다 servlet-context.xml에서 경로를 변경하였다.

