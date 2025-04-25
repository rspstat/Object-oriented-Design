Use Case #1: Upload Photo

Use Case Name: Upload Photo

ID: UC-1

Importance Level: High

Use Case Type: Detail, Essential

Primary Actor: 인증된 학교 구성원

Stakeholders and Interests:

학교 구성원 – 교내 경험을 기록하고 공유하고자 함

시스템 관리자 – 부적절한 사진 방지 및 시스템 신뢰성 유지

Brief Description: 사용자가 애플리케이션을 통해 사진을 업로드하고, 서버는 사진을 위치 정보와 함께 저장하며 필터링을 수행한다.

Trigger: 사용자가 사진을 업로드함

Type: External

Relationships:

Association: 인증된 학교 구성원

Include: 위치 정보 확인, 파일 포맷 변환, 인증 확인

Extend: 사진 신고하기

Use Case #2: View and Sort Photos

Use Case Name: View and Sort Photos

ID: UC-2

Importance Level: Medium

Use Case Type: Detail, Essential

Primary Actor: 인증된 학교 구성원

Stakeholders and Interests:

사용자 – 인기 있는 사진을 열람하고 싶어함

관리자 – 공개 사진에 대한 사용자 접근 허용

Brief Description: 사용자는 사진을 추천 수 또는 댓글 수 순으로 정렬해서 열람할 수 있다.

Trigger: 사용자가 사진 열람 기능 실행 시

Type: External

Relationships:

Association: 인증된 학교 구성원

Include: 서버로부터 사진 목록 불러오기

Use Case #3: Recommend and Comment

Use Case Name: Recommend and Comment on Photos

ID: UC-3

Importance Level: Medium

Use Case Type: Detail, Essential

Primary Actor: 인증된 학교 구성원

Stakeholders and Interests:

사용자 – 다른 사용자의 사진에 반응하고 피드백을 주고자 함

시스템 – 부정 행위 방지

Brief Description: 사용자가 다른 사용자의 사진에 추천을 누르거나 댓글을 작성할 수 있다.

Trigger: 사진 열람 중 추천/댓글 클릭 시

Type: External

Relationships:

Association: 인증된 학교 구성원

Include: 사용자 인증

Use Case #4: View Photos on Map

Use Case Name: View Photos on Map

ID: UC-4

Importance Level: Medium

Use Case Type: Detail, Essential

Primary Actor: 사용자

Stakeholders and Interests:

사용자 – 사진의 시간대별, 위치별 기록 열람을 원함

Brief Description: 사용자는 지도에서 핀을 클릭하여 사진을 열람하고 위치, 날짜, 시간 정보를 확인할 수 있다.

Trigger: 사용자가 지도 상 핀을 클릭함

Type: External

Relationships:

Association: 사용자

Include: 위치기반 사진 필터링

Use Case #5: Report Photo Issues

Use Case Name: Report Photo Issues

ID: UC-5

Importance Level: High

Use Case Type: Detail, Essential

Primary Actor: 인증된 사용자

Stakeholders and Interests:

사용자 – 부적절하거나 잘못된 정보의 사진을 신고하고 싶어함

관리자 – 사진 관리 필요

Brief Description: 사용자가 사진의 위치, 시간 오류 또는 부적절한 사진을 신고할 수 있으며, 특정 수 이상의 신고 시 사진은 비공개 처리된다.

Trigger: 사용자가 사진 열람 중 신고 클릭

Type: External

Relationships:

Association: 사용자

Extend: 관리자 수동 조치 기능

Use Case #6: Request Route

Use Case Name: Request Route

ID: UC-6

Importance Level: Medium

Use Case Type: Detail, Essential

Primary Actor: 사용자

Stakeholders and Interests:

사용자 – 최단 경로로 건물을 이동하고자 함

Brief Description: 사용자가 출발지와 도착지를 선택하면 시스템이 교내 샛길 포함 최단 경로 및 예상 소요시간을 제공한다.

Trigger: 사용자가 경로 안내 요청 버튼 클릭 시

Type: External

Relationships:

Association: 사용자

Include: 사용자 위치 확인

Use Case #7: View Building Information

Use Case Name: View Building Information

ID: UC-7

Importance Level: Medium

Use Case Type: Detail, Essential

Primary Actor: 사용자

Stakeholders and Interests:

사용자 – 각 건물에 대한 정보 탐색

Brief Description: 사용자가 지도의 핀을 클릭하여 해당 건물의 행사, 평면도, 호실, 편의시설, 교수진, 랩실 등의 정보를 확인할 수 있다.

Trigger: 사용자가 건물 클릭 시

Type: External

Relationships:

Association: 사용자

Use Case #8: Post to Anonymous Board

Use Case Name: Post to Anonymous Board

ID: UC-8

Importance Level: Medium

Use Case Type: Detail, Essential

Primary Actor: 인증된 사용자

Stakeholders and Interests:

사용자 – 익명 커뮤니케이션 원함

Brief Description: 사용자가 익명으로 글 작성, 댓글 작성, 사진 공유가 가능한 커뮤니티 기능을 사용한다.

Trigger: 사용자 커뮤니티 접근 시

Type: External

Relationships:

Association: 인증된 사용자

Use Case #9: Authenticate and Login

Use Case Name: Authenticate and Login

ID: UC-9

Importance Level: High

Use Case Type: Detail, Essential

Primary Actor: 사용자

Stakeholders and Interests:

사용자 – 개인 계정 보호와 권한 접근

관리자 – 비인가 사용자 접근 차단

Brief Description: 사용자는 학생증/교직원 카드 또는 PIN을 통해 본인을 인증하고 로그인할 수 있다.

Trigger: 애플리케이션 실행 후 로그인 화면 진입

Type: External

Relationships:

Association: 사용자

Include: 인증서버 확인, 계정 정보 확인

