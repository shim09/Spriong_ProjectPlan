# Spriong_ProjectPlan

- 작성일 : 2021.12.14
- 작성자 : 심형철

 1. ProjectName : Health Gallery
 

 2. 기획 의도

  i. 어떠한 목적을 구현하는 프로그램인가?
  - 당일 운동 메모와 함께 서로의 운동 방법, 자세를 비롯한 루틴 등을 공유할 수 있는 사이트 이다.

  ii. 왜 이런 프로그램을 구상하게 되었는지?
  - 덤벨 이코노미(dumbbell economy)라는 말이 있다.
  - 아령을 의미하는 dumbbell과 경제를 의미하는 economy를 합쳐 만든 용어다. 
  - 건강과 체력 관리에 대한 소비자들의 소비가 늘어나면서 스포츠 서비스업, 스포츠 시설업, 스포츠용품 판매업과 같은 시장이 
  - 큰 호황을 누리는 경제 현상을 일컫는 말이다.
  - 이렇게 최근들어 헬스가 유행하는 지금, 헬스에도 방대한 정보량이 있지만, 자신의 스킨에 맞는 트레이닝 방법을 찾기란 정말 힘든 일이다.
  - 그만큼 헬스에 입문하는 사람들이 보다 쉽고 재밌게 헬스에 입문을 하였으면 하는 바람에 만들어본다..
  
  iii. 어떤 것들을 할 수 있는지?
  - 전체적인 틀을 잡고 봤을때 구현하고 싶은 기능은 기본적인 게시판을 틀로 잡아
  - 1. 회원가입,로그인,로그아웃,회원탈퇴,회원삭제(관리자) 등
  - 2. 글작성,글삭제,글수정 등
  - 3. 댓글작성,댓글삭제 등을 기반으로 서로의 운동정보 공유 및
  - 유튜브 영상,도서정보,사진 등으로 정보를 공유하고 어떤 보충제가 좋은지
  - 운동 장비(리프팅벨트,스트랩,손목.팔꿈치.무릎 보호대 등)추천 등의 정보를 공유한다.
  (해당 프로젝트 계획안이 승인되면 기초적인 게시판의 시작은 전체적으로 3대 운동을 기반으로 한 대근육(대퇴근,대흉근,광배근)을 토대로
  소근육(이,삼두,삼각근,전거근,복직근 등) 운동 영상 링크 및 사진 설명을 올릴 예정이고, 자주 운동에 대한 정보를 공유하는 유튜버에게 연락하여
  영상 사용 가능여부를 허락받을 예정이다.)
  
  3. 벤치마킹
  - 참고 사이트 : https://www.monsterzym.com/ 몬스터짐
  - 운동용품,식단,보충제를 비롯한 에너지드링크,비타민 등을 판매하고 운동정보 공유,질문답변,대회정보 등을 상세하게 알려주는
  - 매우 유익한 사이트 이며, 해당 사이트의 몇몇 기능만 따라 오마주 하여 만들어 보고 싶다.
 
  4. 주요 기능
  - 1. 회원(Member) 게시판을 이용한 회원가입,로그인,로그아웃,회원탈퇴,회원삭제(관리자) 등의 기능 구현
  - 회원 가입 시 ajax를 이용한 아이디 및 휴대폰번호 중복체크와 함께 휴대폰 인증 API를 사용해 인증기능을 구현해 볼 생각이다.
  - 2. 글작성(Board) 게시판을 이용한 글작성,글수정,글삭제 등과 함께 글머리를 만들어 글 작성 시 선택해 볼 수 있게 해준다.
  - 여러개의 게시판을 만드는것보다는 글머리를 만들어서 맨몸운동 정보인지,어떤 운동에대한 자세 정보 공유인지 등을 구현해 볼 생각이다.
  - 3. 댓글 기능(Comment) 을 이용한 댓글 작성 및 삭제도 함께 구현을 해 볼 예정이다.
  - 4. (기능구현 예정인것들) 몬스터짐 처럼 간단한 쇼핑 시스템도 구현을 해보고 싶지만, 해당 사이트처럼 하려면 굉장히 오랜 시간이
  - 걸릴 듯 하여 위 기능을 모두 구현한 뒤 시간이 남을 경우 쇼핑 시스템도 구현을 해보려고 한다.

5. 기타(부가 성명)
 - 관리자는 기본적으로 사이트 제작이 완료되면 대표 운동들에 대한 정보들을 공유하는 글을 작성한다.
 - (등,가슴,어깨,하체,팔 등의 운동방법)
 - 관리자는 공지 사항으로 주의사항 등을 공지하며 해당 글은 페이징처리하여 화면을 넘겨도 게시판 상단에 고정되는 방법을 사용해 볼 예정이다.  
