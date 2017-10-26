# LostFound : 온라인 분실물센터
온라인으로 분실물과 습득물을 등록할 수 있는 웹사이트입니다.
분실물을 잃어버릴 경우 어디서 잃어버린지도 잘 모르는 경우와 분실물을 주워도 찾아줄 방법이 없는 경우를 생각하며 웹사이트를 제작 했습니다.

# 개발 환경
운영체제 : CentOS 7 <br/>
서버 : Apache<br/>
데이터베이스 : MySQL<br/>


# 웹사이트 기능
 
<h2>1. 로그인/회원가입  </h2>
- 회원가입 : 아이디, 닉네임 중복검사를 통해 회원가입 합니다.<br/>
- 로그인/로그아웃 : 세션 기능을 이용하여 사용자의 로그인/로그아웃 상태를 저장합니다. <br/>
- 회원 정보 수정 : 로그인한 상태에서 사용자의 비밀번호, 닉네임 등을 수정할 수 있습니다. <br/>

<h2>2. 게시판 </h2>
- 리스트 : 페이징을 사용하여 한 페이지에 10개의 글을 보여줍니다. </br>
- 검색 : 제목, 닉네임 등을 기준으로 검색 결과를 가져옵니다. <br/>
- 글 추가/수정/삭제 : 제목, 내용, 장소, 이미지 등을 등록합니다. 사용자는 글을 수정하거나 삭제할 수 있습니다. <br/>
- 댓글 추가/수정/삭제 : 해당 글에 댓글을 추가, 수정, 삭제합니다. <br/>
