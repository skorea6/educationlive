# 프로젝트 제목
교육 생방송 플랫폼
(고등학교 프로젝트용)

# 프로젝트 제작 이유 / 설명
친구들이나 모르는 사람들에게 자신이 아는 내용을 실시간으로 알려주고 서로 긴밀하게 소통할 수 있는 ‘교육에 특화된 플랫폼’이 없는 것 같아 제작하게 되었다. 실시간으로 올라오는 채팅과 질문을 분리하여 보여주고, 특정 사람들만 생방송을 시청할 수 있게끔 호스트가 비밀번호를 설정하는 기능이 있다는 점이 내 프로젝트 플랫폼의 가장 큰 장점이라 할 수 있다.

# 연관 Github 바로가기
* 프론트앤드 : https://github.com/skorea6/educationlive_frontend
* 백엔드: https://github.com/skorea6/educationlive
* 채팅서버: https://github.com/skorea6/educationlive_chat

# 프로젝트 활동 기간
1달

# 프로젝트 기능
* 로그인/회원가입(+ 이메일인증)/로그아웃
* 회원탈퇴/회원수정
* 현재 방송중인 모든 방송 목록
* 방송 시작/종료하기
* 방송 비밀번호 설정하기
* 실시간 질문하기
* 실시간 채팅방 (각 방마다 다른 채팅방, 과거 채팅 최대 7개까지 표시)
* 실시간 생방송 시청 (JW 플레이어, AWS Cloudfront 사용으로 몇십만명 시청가능)

# 사용한 언어
* 프론트엔드: Html, CSS, Javascript (Bootstrap 4 템플릿 이용)
* 백엔드: 파이썬 Fast API, Node.js (Socket Io 채팅방)
* 추가적인 툴: Redis(JWT Token 로그인 시스템 구현), Wowza Streaming Engine(스트리밍 서버 구현), AWS Cloudfront (스트리밍 CDN 구현)

