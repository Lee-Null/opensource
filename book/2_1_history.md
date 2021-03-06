## 개괄

### Q. 오픈 소스는 어떻게 도입되었나요?

 A. 처음에 모든 소프트웨어는 오픈 소스였어요. 주로 프로그래머들이 시스템을 더 발전시키려는 목적으로 기술, 응용 프로그램 등을 개발하고 이를 공유했죠. 초기에는 자원이 부족했기 때문에 사람들은 소프트웨어를 공유하는 것이 당연하다고 여겼어요. 그리고 이들은 스스로 조직화하기 위해서 커뮤니티를 만들었는데 대표적으로 IBM의 쉐어(1967)와 DEC의 DECUS(1961)가 있어요.
 시간이 흘러 1970년대 사유 소프트웨어가 등장하기 시작했는데, 그 이유에는 크게 2가지 사건이 있어요. 우선 1970년대까지의 소프트웨어는 하드웨어 제조업자들에 의해 무료로 배포되고 있었어요. 초기에는 소프트웨어의 개발비용이 그렇게 비싸지 않았기 때문에 하드웨어에 소프트웨어를 끼워서 팔 수 있었기 때문이에요. 하지만 소프트웨어의 개발비용이 상승함에 따라서 소프트웨어를 독립적으로 판매하려는 기업이 많아지고, 1969년 미국 법무부에서 하드웨어에 소프트웨어를 끼워팔던 IBM을 상대로 반독점 소송을 제기했어요. 두 번째로는 마이크로소프트의 빌 게이츠가 개발자 커뮤니티에서 한 통의 편지를 공개했어요. 이 편지에서 오픈 소스를 비난하며 독점 소프트웨어라는 새로운 개념을 제시했어요. 이러한 사건들을 계기로 상용 소프트웨어는 급격하게 늘어났어요.
 그 후 AT&T라는 회사의 두 직원은 C언어를 개발하고, UNIX라는 운영체제를 만들었어요 이는 기존의 운영체제에 비해 좋은 점이 많았고, 무상이었기 때문에 많은 사람들이 이용했죠. 하지만 시간이 흘러 AT&T에서 UNIX를 상용화했고, 대학이나 연구소에서도 사용할 수 없게 됐어요. 그 외에도 1980년대 상업화하기 시작한 UNIX는 점차 폐쇄적으로 변해갔죠. 그래서 같은 뿌리를 가진 UNIX라도 호환되지 않기 시작했어요. 또한, 기업들은 점차 오픈 소스에 대해 반감을 품게 됐죠. 그러던 중 MIT 연구소의 리처드 스톨만이 폐쇄적인 소프트웨어에 대해 불만을 품기 시작하면서 오픈 소스 운동을 시작했죠.

## 초기

### Q. 해커 문화와 오픈 소스는 어떤 관계인가요?

 A. 초기의 해커 문화는 MIT에서 시작했어요. 1961년 DEC에서 PDP-1을 MIT대학에 기부하면서 처음 컴퓨터를 접한 MIT의 취미 동아리였던 테크 모델 철도 클럽(TMRC)의 학생들은 그걸 새로운 장난감으로 인식하고, 오늘날 우리가 인식하는 프로그래밍 도구와 관련된 은어, 그리고 주변 환경을 만들어 냈어요. 그리고 '해커'라는 단어가 이들의 해커 문화에서 부터 시작했죠. 그리고 이들은 MIT 인공 지능연구소 해커 문화의 중심이었어요. 다른 연구소와 함께 멀틱스라는 운영체제를 개발하는 중 개발 방향이 맞지 않아 1960년대 후반부터 자신들이 새롭게 ITS(Incompatible Time Sharing System)라는 운영 체제를 개발했어요. 당시 ITS 운영체제에서는 기존과는 다른 사용자 환경을 제공했어요. 그것은 누구나 시스템에 암호 없이 로그인하고, 문서나 소스 코드 같은 모든 파일을 누구나 편집할 수 있게 만들었던 점에서 말이죠. 또한 이것은 MIT 내부뿐만이 아니라 다른 기관에서도 아파넷을 통해 ITS에 접속할 수 있었어요. 이러한 ITS의 개방적인 부분은 해커 문화에 큰 영향을 주었고, 오픈 소스에도 영향을 주었어요. 대표적으로 당시 MIT 소속이던 리처드 스톨만은 지금 오픈 소스의 선두주자로 있어요.

### Q. 마이크로소프트는 오픈 소스에 대해 어떻게 생각했나요?

![11](https://i.imgur.com/FY5vliJ.jpg)![22](https://i.imgur.com/NExBvq7.jpg)
> 1. 취미로 소프트웨어를 개발하는 개발자들에게 보내는 공개 서한(1976)
> 2. 마이크로소프트 핼러윈 문서(1998)

 A. 마이크로소프트는 오픈 소스에 대해 무척 부정적으로 생각했어요. 왜냐하면 마이크로소프트는 독점 소프트웨어를 기반으로 만들어진 회사였기 때문이에요. 그리고 이전에는 마이크로소프트가 컴퓨터 시장을 독점하고 있었는데, 어느 날 오픈 소스로 만들어진 리눅스의 등장으로 밥그릇을 나눠 먹어야 하기 때문이에요. 그래서 마이크로소프트를 창업한 지 얼마 안 되었던 빌 게이츠는 '홈브루 컴퓨터 클럽'에서 '취미로 소프트웨어를 개발하는 개발자들에게 보내는 공개 서한'(An Open Letter to Hobbyists)이란 편지를 썼어요. 이 편지는 커뮤니티를 통해 일어나는 소프트웨어의 만연한 저작권 침해에 대해 좌절감을 표현하는 편지였어요. 글의 내용을 보면 "당신들 대부분은 소프트웨어를 훔치고 있다.", "어떤 취미가 들이 3명의 프로그래머가 1년 동안 작업하고, 디버깅하고, 문서화한 제품을 무료로 배포할 수 있겠는가?" 등 오픈 소스에 대한 원색적인 비난을 했어요. 또한, 마이크로소프트의 CEO였던 스티브 발머는 리눅스는 지적 재산권에 있어서 암같은 존재라고 언급했어요. 이는 오픈 소스를 이용하면 이후 개발하는 소프트웨어도 모두 오픈 소스로 내놓아야 하는 게 업체들의 지적 재산권을 침해한다는 주장이었어요. 마지막으로 1998년 11월 1일 에릭 S. 레이먼드에 의해 공개된 핼러윈 문서에는 리눅스나 오픈 소스 운동이 마이크로소프트에 독점적인 시장에 위협을 가하고 있다는 점을 인정하면서 견제하고 있다는 게 서술되어 있어요.

### Q. AT&T에서 만든 UNIX는 무엇인가요?

 A. 캔 톰슨이란 사람 AT&T 벨 연구소의 직원이었어요. 1960년대 중반 벨 연구소와 제너럴 일렉트로닉, GE, MIT에서는 ITS와 같은 시분할 운영체제인 멀틱스(Multics)의 개발을 진행하고 있었어요. 하지만 벨 연구소에서는 멀틱스의 거대한 크기와 복잡성에 좌절해 점차 프로젝트에서 손을 떼 버렸어요. 하지만 톰슨은 멀틱스의 환경을 그리워해서 쓰레기가 되어버린 PDP-7에 자기 생각을 구현해보기로 했죠. 멀틱스의 말장난을 이용해 UNICS라는 이름으로 1970년 프로젝트를 제안했고, 브라이언 커니핸이란 사람에 의해 UNIX라고 철자가 바뀌게 됐어요.
 UNIX 개발 당시에 PDP-11으로 컴퓨터가 업그레이드되었기 때문에 어셈블리어로 작성했던 UNIX의 코드를 다시 작성해야 했어요. 그래서 데니스 리치와 톰슨은 함께 개발한 B언어로 UNIX를 다시 개발하려고 했었죠. 그러던 중 B언어를 수정하여 C언어로 재탄생 시키고 이로 1972년 UNIX를 다시 개발했어요. 이것은 기계 종속적이지 않기 때문에 어느 장치에나 사용할 수 있었고, 이 도구에 대한 관심은 벨 연구소 내에 퍼졌어요. 그렇게 탄생한 UNIX의 공식적인 법인체인 AT&T에게 전화 사업 이외의 사업에 대해 양보 명령이 내려졌고, UNIX는 어떠한 지원 없이 무상으로 제공됐어요. 그리하여 수많은 대학과 연구소에서 사랑을 받게 됐죠.
 UNIX는 AT&T의 공식적인 지원이 없었기 때문에 학생이나 연구자 같은 사용자들은 발생한 문제를 직접 해결해야 했어요. 이 과정에서 서로 간의 아이디어, 정보, 프로그램 및 버그 수정본을 공유하였죠. 또한, 사용자들이 더 편하게 개발하도록 커니핸과 플라우거는 몇몇 핵심 유틸리티의 구현을 쉽게 이해할 수 있는 책을 소스 코드와 함께 출판하였고, 사용자들은 각 유틸리티를 강화하고 다양한 아키텍처에 이식하기 위해 공동으로 협력하였어요. 1978년에 그들은 공식적으로 STUG라는 사용자 그룹을 구성하였어요. 사용자 그룹도 형성되고, 책도 발간되는 등의 발전을 이루지만, AT&T가 UNIX를 상용화함에 따라 1979년에 시스템 소스 코드에 접근 제한을 두는 라이선스를 가진 버전 7을 배포하였어요. 이로 인해 UNIX는 대학 교육과정에서 사용할 수 없었고, 오픈 소스 소프트웨어 운동에 자극을 주게 되었죠.
