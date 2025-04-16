---
title: 모두의 투표, DO표
summary: 2023년 9월 - 2024년 6월
date: 2024-06-23
type: docs
math: false
---

### 개요

'모두의 투표, DO표'는 투표를 기반으로 소통할 수 있는 커뮤니티입니다.

- 문서: [{{< icon name="hero/document" >}}](구해줘!룸메.pdf)
- 코드: [{{< icon name="brands/github" >}}](https://github.com/l0o0lv/DoVote-MSA) 
- 사용 기술: {{< icon name="devicon/csharp" >}}| WPF | {{< icon name="devicon/microsoftsqlserver" >}}
- 개발 환경: {{< icon name="devicon/windows8" >}}
- 개발 기간: 2023년 9월 - 2024년 6월

{{<youtube lsNVNiEflqA>}}
{{<youtube zsOx-2iT_Bk>}}


<!-- ### 개발 동기

DO표는 일상 속에서 말하기 애매했던 고민이나 생각들을 부담 없이 투표를 통해 공유할 수 있는 커뮤니티입니다.  
유튜버들이 커뮤니티 탭의 투표 기능을 활용해 구독자들과 가볍게 소통하는 모습에서 아이디어를 얻어 만들게 되었습니다.
사용자들은 자유롭게 투표 게시글을 작성하고, 투표에 참여한 뒤 댓글을 통해 서로의 생각을 나눌 수 있습니다.

### <u>내가 기여한 점</u>

1. MVVM 디자인 패턴 적용
    - Data Binding을 통해 UI와 사용자 입력을 분리함으로써 DB 데이터 변경과 디자인 요소를 각각 관리하도록 했습니다.
2. 기능 구현
    ![screen reader text](회원가입.png)
    - 이메일 인증: 랜덤 생성해 발송한 코드와 사용자 입력이 일치하는지 확인함으로써 회원가입 시 교내 학생임을 보장했습니다.
    ![screen reader text](프로필.png)
    - 프로필: 임시 객체에 DB 정보를 파싱한 후, 사용자가 값을 수정했을 때 DB 정보를 갱신하도록 했습니다.
    ![screen reader text](검색.png)
    - 검색: 사용자 입력으로 DB에서 탐색한 데이터를 ListView로 표시하도록 했습니다.
    ![screen reader text](채팅.png)
    - 채팅: 전송 버튼을 클릭했거나 서버에서 상대가 전송한 메시지를 확인했을 때 채팅 메시지 ListView를 갱신하도록 했습니다.

### 한계

1. 비동기 통신의 부재
    - 소켓 기반의 실시간 채팅만 구현했다는 점이 아쉬움으로 남습니다.
2. UI
    - 사용자 친화적인 인터페이스를 제공하지 못했습니다.