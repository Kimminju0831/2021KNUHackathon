# 2021KNUHackathon
기억해조 경북대학교 해커톤 레포지토리

# 1. 제안 배경
<br>  코로나-19로 인해 경북대학교의 대부분의 수업은 대부분 비대면으로 전환되었다. 새로운 수업 형태로 인해 학우들은 다양한 어려움을 겪게 되었지만, 그 중에서도 학우들이 가장 체감하기 쉬운 고충은 학우들간의 교류가 전혀 없다는 점이다. 기존의 상황처럼 대면 수업을 들을 경우 다양한 오프라인 활동을 통해 다른 학우들과 교류하고 그 과정에서 필요한 정보를 얻어가기도 했었지만, 현재 코로나-19로 인해 서로간의 접촉이 최소화된 만큼 기존의 소통을 기대하기는 어려운 상황이다. 실제로 이 어플을 개발하기로 한 팀 ‘기억해조’의 경우에도, 동아리 활동이나 수업 중 팀프로젝트처럼 한정적인 기회를 통해 서로를 알게 되었으니 이러한 경험이 없었던 학우들은 더더욱 다른 학우들과 교류를 기대하지 못하리라 생각했다. 
 
 특히 신입생의 경우, 만남을 주선하는 활동 없이는 좀처럼 친해지기 어려운 것이 사실이다. 학교 생활에 대해 궁금한 점이 많은 신입생들이 코로나-19로 인해 선배들과 학우들에게 궁금한 점을 해소하지 못하는 상황이 자주 벌어지고는 한다. 이를 해결하기 위해 학교 측에서는 다양한 멘토링 시스템과 같은 형태로 지원하고 있지만, 팀 ‘기억해조’는 좀 더 간편한 형태로 학교 생활에 익숙하지 않은 신입생들과 학우들을 지원할 수 있기를 바랐다.

 때문에 팀 ‘기억해조’는 이러한 난관에 봉착한 ‘다른 학우들과 소통하지 못함으로 인해 불편함을 겪고 있는 신입생이나 재학생’을 위해 [같은 강의를 듣는 학우들과의 커뮤니티] 서비스를 기획하게 되었다.

<br><br>

# 2. 주제

<br>
 ‘우리끼리’ 어플은 일종의 커뮤니티 서비스로서, 기존의 커뮤니티 서비스인 ‘에브리타임’과 달리 ‘같은 강의를 듣는 학생들끼리 모일 수 있게 해준다’ 는 특징이 있다. 에브리타임 어플의 경우 한 캠퍼스를 사용하는 학우라면 모두 자유롭게 글을 올릴 수 있다는 장점이 있지만, 반대로 필요한 정보를 얻어야 할 때 해당 정보만 얻어내는 것이 어렵다는 단점이 있었다. 때문에 “우리끼리 어플”은 [같은 강의를 듣는 사람끼리 모이다]라는 서비스 취지에 따라  학우들이 한결 간편하게 소통할 수 있도록 하였다. 
 
 이 외에도 “우리끼리”는 간단한 일정 관리 기능과 팀플/스터디를 함께할 사람을 구하는 모집 기능 등 비대면 기조에 들어선 학생들이 꼭 필요로 할만한 기능을 지원하고 있다. 


<br><br>

# 3. 목적

<br>
 ‘우리끼리’ 어플은 ‘코로나-19’로 인한 언택트 생활 방식에 발맞추어, 학교의 다양한 정보를 얻기 원하는 경북대 신입생의 학교 적응을 돕고 재학생의 편의를 지원하는 것이 주 목적이다. 

<br><br>

# 4. 용도

![image](https://user-images.githubusercontent.com/72423836/126736548-2e150776-b11a-4612-a42d-9240439f4b38.png)<br>
### 모든 화면의 하단에 ‘우리끼리’의 주요 기능으로 바로 이동할 수 있는 5개의 버튼을 배치하였다. 왼쪽부터 차례로 ‘게시판’, ‘일정’, ‘홈’, ‘알람’, ‘설정’ 화면으로 이동하는 버튼이다.<br>

### __로딩화면__ 
![loading](https://user-images.githubusercontent.com/72423836/126732612-2693ecee-d3b2-4897-bdae-f13a925e41b3.jpg)
프로토타입<br>

구현화면<br>
로딩 화면엔 코끼리가 학사모를 쓴 로고와, 기억해조의 어플리케이션 이름인 '우리끼리'를 보여주었다.
<br><br>
### __로그인 및 회원가입 화면__

구현화면<br>회원가입 시 아이디, 패스워드와 함께 이름, 나이, 학번, 학과의 정보를 수집하였고, 아이디는 중복 확인이 가능하도록 하였다.
### __홈 화면__
![image](https://user-images.githubusercontent.com/72423836/126736452-92b869c0-51c1-4f34-bc50-cd5383764569.png)
프로토타입<br>

구현화면<br>
'우리끼리' 어플의 주요 기능을 한 눈에 볼 수 있게 하였다. 제일 위에는 학사 일정과 사용자가 입력한 일정 중 임박한 일정을 한 눈에 볼 수 있도록 하였고, 그 아래에 사용자가 가입한 스터디나 팀프로젝트 팀의 과제를 정리할 수 있도록 하였다.
<br><br>
### __게시판 화면__
![게시판](https://user-images.githubusercontent.com/72423836/126732791-7a92bee7-7298-43c0-b70c-11e0cda60bbf.jpg)
프로토타입<br>

구현화면
<br>각각의 수업을 터치하면 해당 수업의 게시판으로 화면이 이동한다. 이때, 편집하기를 눌러 게시판을 편집할 수 있다.  각 과목의 게시판에는 '질문' 탭과 '팀플 및 스터디' 탭이 존재한다. 두 개의 탭은 좌우로 스와이프하여 이동 가능하다.<br> '질문' 탭에서는 학생들끼리 강연 일정에 관련한 질문을 주고받을 수 있으며, 익명으로 게시물과 댓글을 작성할 수 있다. '팀플 및 스터디' 탭에서는 해당 과목에서 진행하는 팀프로젝트의 팀을 구성할 수 있으며 해당 과목 관련한 공부를 함께 하는 스터디 모집도 진행할 수 있다.

<br><br>
### __게시판 편집 화면__
![게시판편집](https://user-images.githubusercontent.com/72423836/126732812-d1f7d673-fc14-4728-87bb-7bd73b059844.jpg)
프로토타입<br>

구현화면
<br>하나의 강의마다 하나의 게시판이 존재하므로 학생들은 매 학기마다 본인이 듣는 수업에 따라 활동할 게시판을 편집할 수 있다. 과목 이름 좌측의 ‘-’ 버튼을 누르면 해당 과목의 게시판을 삭제할 수 있으며, 게시판 추가하기 버튼을 누르면 과목코드 혹은 과목이름을 검색하여 원하는 과목을 찾을 수 있다.

<br><br>
### __질문 게시판 화면__
![질문게시판](https://user-images.githubusercontent.com/72423836/126732825-1c911cb2-1d84-4be6-917b-fd37af08186d.jpg)
프로토타입<br>

구현화면
<br>같은 수업을 수강하는 학생들끼리 시험 일정 등의 간단한 질문을 주고받을 수 있는 게시판 화면이다. 각 게시글의 제목과 작성자, 댓글 수, 추천 수와 본문 일부를 간략히 표시하였고, 각각의 게시물을 최신순, 좋아요 순으로 정렬하여 볼 수 있다. <br><br>
### __질문 게시판의 게시글 화면__
![질문게시판_게시글](https://user-images.githubusercontent.com/72423836/126732839-1c002004-b474-45a7-b65d-5ae833416497.jpg)
프로토타입<br>

<br>구현화면<br>
게시글에 달린 댓글을 확인할 수 있으며 댓글을 작성할 수 있다.
<br><br>
### __질문 게시판의 내용 입력 화면__
![질문게시판_내용입력](https://user-images.githubusercontent.com/72423836/126732856-59e4546e-3783-4640-8d82-56e3c7cb719c.jpg)
프로토타입<br>

구현화면
제목과 내용을 입력할 수 있으며, 질문 게시판의 경우 ‘익명으로 작성하기’ 버튼을 통해 익명으로 게시글을 작성할 수 있다. 작성이 끝나면 작성 완료 버튼을 눌러 글을 게시할 수 있다.

### __'팀플 및 스터디' 게시판 화면__
![팀플및스터디 게시판](https://user-images.githubusercontent.com/72423836/126732867-7e49a4c5-6ca6-4b45-9d28-949a9727ab35.jpg)
프로토타입<br>

구현화면<br>
해당 과목에서 진행하는 팀프로젝트의 팀을 구성할 수 있으며 해당 과목 관련한 공부를 함께 하는 스터디 모집도 진행할 수 있다

### __'팀플 및 스터디' 게시판의 게시글 화면__
![팀플및스터디게시판_게시글](https://user-images.githubusercontent.com/72423836/126732874-7b3711c0-416f-4f5e-b403-2356636d20f3.jpg)
프로토타입<br>

구현화면
<br>모집인원과 분야를 명시하도록 하였고, 댓글과 덧글을 통하여 간단한 의사소통이 가능하도록 하였다. 또한 비밀 댓글 기능 추가하였다.
### __'팀플 및 스터디' 게시판의 내용 입력 화면__
![팀플및스터디게시판_내용입력](https://user-images.githubusercontent.com/72423836/126732883-649fc34c-1304-406b-8a5a-64fd0dc3df8e.jpg)
프로토타입<br>

구현화면<br>
‘팀플 및 스터디’ 게시판은 익명으로 글을 작성할 수 없도록 하여 게시글의 신뢰도를 높였다. 모집 인원을 작성하도록 하였고, 팀플과 스터디 중 하나의 분야를 선택할 수 있도록 하였다. 또한 간단한 설명을 덧붙일 수 있도록 하였다.
### __일정 화면__
![일정](https://user-images.githubusercontent.com/72423836/126732891-3d9bc89b-5517-4847-b661-4460d6fa51c6.jpg)
프로토타입<br>

<br>구현화면
<br>달력을 상단부에 배치하고 날짜를 터치하면 달력 아래에 해당 날짜의 일정을 알려준다. 사용자가 직접 자신의 일정을 달력에 저장할 수도 있으며, 해당 일정은 수정 가능하다. 

### -__일정 수정 화면__
![일정수정](https://user-images.githubusercontent.com/72423836/126732904-4a5cbf83-d7c8-4210-b74c-afd2a1930612.jpg)
프로토타입<br>

<br>구현화면
<br>
사용자가 일정을 직접 수정할 수 있도록 하였다.
<br><br>

# 5. 영향
<br>
 ‘우리끼리’ 어플을 개발하는 단계에서 팀 ‘기억해조’는 크게 세 가지 효과를 기대했다.

 첫째, 학생들간의 소통이 원활해지면서 소외되는 학생이 줄어든다. 코로나-19 상황으로 인해 사람들이 고립감을 느끼게 되면서 코로나 블루라는 새로운 사회적 현상이 대두되고 있는 지금, 우리끼리 어플은 새로운 사람들과의 부담없는 소통 창구로 기능하며 학우들이 혹여 느낄 수 있는 소외감이나 고립감을 해소시켜줄 것이다.

 둘째, 정보가 필요한 학생들에게 든든한 가이드 앱이 될 수 있다. 특히 학교 생활이 처음인 신입생의 경우 공지 사항이나 수강 신청, 수강 꾸러미, 레포트 작성법에 이르기까지 학교에서 정보를 제공하지만 찾기 힘들거나, 재학생들의 노하우가 필요한 순간이 있기 마련이다. 여기서 ‘우리끼리’ 어플은 게시판에 글을 쓸때 익명, 실명 기능을 추가하여 정보를 제공하는 쪽에서도 부담없이, 정보를 찾는 쪽에서도 부담없이 어플을 이용할 수 있도록하여 친절한 가이드 역할을 하는 어플이라는 인상을 심어줄 것이다.

 셋째, 코로나-19 상황에서 대면 활동을 최소화함을 통해 방역에 도움이 될 것이다. 시시각각 급변하는 정보들이 재난문자를 통해 날아오는 요즘, 이러한 커뮤니티 서비스는 사람들로 하여금 ‘굳이 만나지 않아도 된다’는 인식을 갖게 한다. 언택트 문화권을 살고 있는 요즘, 우리끼리 어플은 신입생과 재학생들의 비대면 활동을 적극적으로 지원할 것이다.
 

<br><br>

# 6. 피드백
<br>
안드로이드 스튜디오의 경우 보안상의 이유로 외부 라이브러리와의 직접 연동이 불가능했다. 그래서 데이터베이스와 안드로이드 스튜디오 사이에서 매개 역할을 하는 웹서버를 통해 데이터베이스의 데이터를 사용해야 하는 점이 구현하기 까다로웠다. 

이 외에도, 기존에 기획해 두었던 ui ux 를 그대로 구현하고자 했던 목표 때문에 필요한 기능이 굉장히 많았는데, 안드로이드 스튜디오라는 툴 자체가 익숙하지 않아 자유롭게 구현하기가 어려웠던 점이 아쉽다.

<br><br>

# 7. 앞으로
<br>
 ‘우리끼리’의 주요한 목적 중 하나는 신입생의 적응을 돕는 것이다. 때문에 향후 학사, 기숙사 공지와 같이 다양한 정보를 직접 추가하거나, 관련 질문을 할 수 있는 질문용 게시판을 추가함을 통해 더욱 쉽고 빠르게 정보를 얻을 수 있도록 할 예정이다.

 또한 기획 단계에 있던 레벨 기능의 개발을 통해 질문의 답변에 대한 신뢰도를 높이고, 이러한 레벨을 이용해 또 다른 컨텐츠를 추가할 것이다.

<br><br>


