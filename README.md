# YourTube_client

코드 스테이츠의 팀 프로젝트 YourTube 입니다.

사용자의 유튜브 좋아요 리스트 내에서의 검색기능을 제공하는 SPA 입니다.

2주간 진행되었고 총 4명의 팀원이 팀을 이뤄 프로젝트를 진행했습니다.

<br>

개요

- 프론트엔드는 React.js, OAuth 2.0, 백엔드는 Express, MySQL, Node.js기반으로 진행되었습니다
- 사용자가 구글 로그인을 하면, 백엔드는 구글 OAuth 인증을 통해 유튜브 좋아요 데이터를 크롤링합니다.
- 크롤링한 유튜브 좋아요 데이터를 기반으로 프론트엔드에서 리스트와 검색기능을 구현합니다.

<br>

역할

- 프로젝트 팀에서 팀장을 맡아 팀의 미션을 부여하고 커뮤니케이션을 담당했습니다. 
- 구글 OAuth 인증을 사용한 로그인 구현을 담당했습니다.

<br>

진행 순서

  1. 작업환경 셋팅

   - Node.js를 기반으로 진행했습니다. npm을 사용하여 필요한 패키지를 설치합니다.
   - 코드 내 각종 오류를 방지하기 위해 ESLint를 사용했습니다.  

  2. 기능 구현

   - React를 사용하여 로그인 컴포넌트를 구현하고 라우터로 App.js와 연동합니다.
   - 구글 OAuth 인증 방식을 사용하여 구글 계정 로그인 기능을 구현합니다.
   - 구글 OAuth 인증으로 받은 인증 토큰으로 서버와 연동합니다.

프로젝트 진행의 기준이 되었던 와이어프레임입니다. 모든 컴포넌트 간의 커뮤니케이션을 표현했습니다.

![YourTube_와이어프레임](https://user-images.githubusercontent.com/55314087/88186444-22c59900-cc70-11ea-97cf-27b4b12b4812.png)

