# Full Cycle Developer - [링크](https://medium.com/netflix-techblog/full-cycle-developers-at-netflix-a08c31f83249)

 개발자로 14년차를 일하면서 이제 40대가 되었습니다. 이제 회사에서나 사회적으로 더 이상 쥬니어가 아닌 나이가 되었습니다. 한면으로는 서글프기도 하지만 이제는 회사에서도 어느 정도 먹고 살만한 자리에 있는 것 같습니다. 이제 와서 돌이켜 보니 쥬니어가 아닌 시니어로서도 해야 할 일이 있다고 생각이 어느날 문득 생각이 들게 되었습니다. 
 
 회사와 밖에서 많은 쥬니어 개발자들을 만나면서 느낀 것은 많은 개발자들은 자기 개발을 위한 노력을 하지 않는 다는 것입니다. 생각보다 많은 부류의 개발자들이 자기 개발에 소홀한 것 같습니다. 두번째 부류는 열심히 공부하려고는 하지만 무엇을 어떻게 공부할지 모르는 개발자가 많다는 것입니다. 사실 혼자서 공부해서 어느 경지에 오른다는 것이 경험상으로는 쉽지 않은 일이었던 것 같습니다. 
 
 그리하여 지금까지 제가 공부해 왔던 것들은 도움이 될지도 모르는 분들과 공유하고 발전시켜 보려고 합니다. 저는 전자전기공학부에서 4년 동안을 공부했고, 동아리에서 임베디드로 프로그램을 처음 접했던 것 같습니다. 그리고 대기업 입사 후에는 13년 동안 한 직장에서 인프라 운영 / 인프라 관련 어플리케이션 운영 / 인프라 관련 어플리케이션 개발 / 어플리케이션 설계등의 경험했습니다. 운 좋게도 폭 넓은 경험을 한 것 같습니다. 스프링을 아무도 가르쳐 주지 않았고 독학으로 익혔던 것 같습니다. @이가 도통 무슨 뜻인지도 모르겠고 했던 시절도 있었던 것 같습니다. 
 
 이제는 답답한 그 대기업을 떠나서 레알 개발회사로 왔습니다. 여기서 하는 일은 주로 팀 리딩 / 팀 관리 / 어플리케이션의 설계입니다. 14년 간의 경험을 뒤돌아 보고 많은 사람들을 접해보았을 때 사실 생각보다 어플리케이션 설계에 있어서 한국에 있는 개발자들이 관심이 적다는 사실을 알게 되었습니다. 아무튼 이 글을 접하는 사람들이 본인들의 많은 경험을 공유하고 쥬니어들이 다 같이 성잘할 수 있는 계기가 되었으면 하는 뜻에서 남겨보게 되었습니다.
 
요즘도 그러나 모르겠지만 많은 개발자들이 Full-Stack 개발자가 되기를 원하지만 실제로 그렇게 되기도 어려울 뿐만 아니라 실제 거의 불가능한 것 같습니다. 없다는 것은 아니지만 실제 정말 어려운 것 같습니다. Front/Backend를 다 잘하는 것이 쉽지 않는 것 같습니다. 그래서 그것보다는 Full Cycle 개발자가 더 의미가 있다고 생각이 되어 넷플릭스의 블로그 글을 참고하여 스터디 가이드를 만들어 보려고 합니다.

아래와 같이 책을 중심으로 정리해보려고 합니다. 책을 중심적으로 정리하는 이유는 최근 인터넷을 활용해서 공부하시는 분들이 많으면서 전체적인 맥락을 공부하고 어떠한 내용을 적용하기보다는 부분 부분을 차용해서 적용하는 개발자분들이 많다보니 어떤 기술과 내용에 대한 깊은 이해가 부족하신 분들이 많이 있습니다. 책은 지루하기는 하지만 전체적인 내용을 다루고 있기 때문에 보다 더 깊은 이해와 통찰을 가질 수 있는 것 같습니다. 인터넷에 비해...

책을 구입하는 것은 나에 대한 투자라고 생각하면 좋을 것 같습니다. 한달에 5만원 주식 투자한다 생각하시고 책을 구매하고 읽다보면 아마도 월급상승률이 주가 상승률을 초월할 것이라고 확신합니다. 책에 투자를 아끼지 마십시요.

물론 백퍼센트 저의 주관적인 생각이며 중간 중간 바뀔 수도 있습니다. 그냥 저의 가이드라고 보시면 됩니다. 대부분은 제가 읽어본 책들 위주로 채워질 내용이며 해당 내용들에 대한 보충의견은 언제나 환영입니다. JAVA SCRIPT 부분은 심근우 님께 도움을 구하며, Deploy 부분, DATABASE, DATA처리 부분에 대해서는 경식님께도 도움을 구합니다. 

| 연차           | Design        | Develop    | Test    | Deploy  | Operate  | Support |
| ------------- |:-------------:|:----------:|:-------:|:-------:|:--------:|:--------:
| 0 ~ 3년차      | 1, 2          | 10         |
| 4 ~ 6년차      | 4, 5          | 7,8        |
| 7 ~ 10년차     | 6, 3          | 9          |13 | | 21,22 | 

[Career Path Sample](http://www.nextree.co.kr/content/images/2016/other/Nextree-Role-based-roadmap-for-SW-engineers-version-KR-SI-1401_A3.pdf)

## DESIGN

### PATTERN 
    1. 자바 객체지향 디자인 패턴 UML과 GoF 디자인 패턴 핵심 10가지로 배우는 - 정인상, 채홍석
    실제 UML에 대한 기본적인 설명과 함께 추상화에 대한 개념과 각 패턴들이 예제와 함께 나와 있습니다. 실제 프로젝트
    구현에 있어서도 많은 도움이 되었습니다.
    20. Head First Design Patterns
    객체 지향을 공부 한 이후 이책을 통해 디자인 패턴을 공부하면 객체지향 프로그래밍을 구체적으로 어떻게(패턴) 해야하는지를 다룹니다.
    OOP를 공부하고 나서 보는걸 추천합니다.
### OOP
    2. 객체지향의 사실과 오해 - 조영호 저
    사실 객체지향 설계의 시작이라고 보면 됩니다. 소설가를 지망하셨다는 저자분께서 그냥 시작하면 끝날 때 까지 잘 읽어지도록
    책을 레알 잘 쓰셨습니다.
    19. Head First Object Oriented Analysis & Design
    객체지향으로 분석 설계 하는 기본 입문서. 어떻게 분석하고 어떻게 해야 유연한 구조로 설계할 수 있는지를 공부하기에 너무 좋은 책입니다.
### MSA
    3. 스프링 5.0 마이크로서비스 스프링 부트와 스프링 클라우드, 스프링 리액티브로 배우는 
    라세지 RV : 기본적인 아키부터 Spring을 잘 활용하는 방법이 나와 있습니다. MSA에 대해서 어설프게 알고 있다면 꼭 
    읽어보아야 하는 책 이론적인 내용과 예제가 다 나와 았습니다.
### DDD
    4. DDD Start! - 도메인 주도 설계 구현과 핵심 개념 익히기 - 최범균 저 : 시작은 이 책 부터
    5. Domain Driven Design - 에릭 에반슨 : 무조건 읽어야 함 첨부터 읽기 어려우니 DDD Start!를 먼저 읽으세요.
    6. Implementing Domain-Driven Design 1st Edition - Vaughn Vernon : 한국어 번역서는 매우 매우 한국말이 아님. 
### EVENT STORMING
### CRC

## DEVELOP

### JPA
    7. 자바 ORM 표준 JPA 프로그래밍 - 김영한
    한동안 우리 나라에 거의 유일무이한 JPA책이었습니다. 레퍼런스라고 보시면 됩니다. JPA에 대해서는 정리하겠지만, 
    Mybaits를 쓰는 것보다 장점이 많이 있습니다. 잘 알고 쓴다면 말이지요.
    8. JPA 프로그래밍 입문 - 최범균
    위의 책보다는 조금 더 실무적인 내용들이 수록되어 있는 책입니다. 위의 책이 너무 방대하다고 느끼시면 이 책으로 
    JPA를 시작해 보는 것도 나쁘지 않은 것 같습니다. 
### Spring
    9. 토비의 스프링 3.1 세트 - 이일민
    사실 자바 ORM 표준 JPA 프로그래밍 책과 같은 완전 바이블 같은 내용입니다. 그러나 사실 초급서적이라고 보기보다는
    중급 이상 독자들에게 읽힐 만한 내용인 것 같습니다. 
    10. 실전 스프링 부트 워크북 - 펠리페 구티에레스
    멕시코 아저씨가 쓴 부트 워크북입니다. 스프링 부트 기반의 많은 서비스들은 단시간 내에 써볼 수 있도록 구성이 되어 
    있고 실제 잘 동작하는 내용들로 구성이 되어 있습니다.
### JAVA
    16. 자바의 정석
    수학에는 수학의 정석이 있다면 자바에는 자바의 정석!
    이름만 자바의 정석이라 생각할 수 도 있지만 실제 입지 또한 수학의 정석 만큼 좋습니다.
    입문용으로 많이 보며 세부적인 것까지 배울 수 있어 중급이상 개발자도 주기적으로 보면 좋은 책입니다.
    17. 자바의 신
    자바의 정석보다는 조금더 쉬운 책입니다. 쉬운책이라고 좋은것은 아니고 조금더 가벼운마음으로 볼 수 있습니다.
    구매전에 서점에 가서 한번 읽어보고 선택하는 것을 추천하며 자바의 신을 구매하더라도 자바의 정석은 꼭 보는걸 추천합니다.
    18. 이펙티브 자바 (Effective Java) - Joshua Bloch
    사실 자바 진영의 필독서라 할 수 있습니다. 3판이 나왔는데 자바 7,8,9 관련이 추가되었고 최근 번역본이 18.11 출간했습니다.
    중급 이상의 개발자들이 보기 좋은 책이고 여러가지 사례들을 보며 개발의 길잡이가 되어주는 책입니다.
### DATABASE
### QUERY
### VUE.JS
    11. Vue.js quick start - 원협섭
    이분은 자비스크립트와 jquery에 대해서도 상당히 많은 내공을 가진 분이십니다. 이분이 지으신 Vue.js 
    Vue.js에 대한 이해와 탄탄한 기본을 가질 수 있도록 도와줍니다.
### JAVASCRIPT
### HTML/CSS
    12. 세르게이의 HTML5&CSS3 퀵레퍼런스 - 세르케이 마브로디
    저는 정말 잘 참고하고 있습니다. 굳이 HTML/CSS에서 대해서 인터넷 검색을 하지 않아도 되게 만들어 주는 책

## TEST
    13. Test-Driven Development:By Example - 켄트벡
    사실 TDD는 언제나 누구나 쉽지 않습니다. 습관을 기르고 될때까지 해보는 것이 매우 중요합니다. 
    이 책에서는 TDD에 대한 기본을 예제와 함께 익힐 수 있습니다. 단 그 후에 실제 적용하는 것은 언제나 그렇듯이 나의 몫

## DEPLOY

## OPERATE
    21. The DevOps Handbook - Gene Kim, Jez Humble, Patrick Debois, John Willis
    많은 사람들이 devops를 운영과 개발을 같이 하는 것이라든지, 혹은 jenkins을 이용한 배포 파이프라인 구축이라든지라고 생각하는 경우가 있는데요. 이 책을 읽어보시면 많은 생각이 바뀔 것이라고 생각이 됩니다. 물론 영어라서 읽기는 매우 어렵습니다. 
    22. Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations
    이 책도 위의 책과 마찬가지이지만 좀더 큰 주제를 다방면에서 다룬다고 보시면 될것 같습니다. 지금 읽고 있는 중이고 아직은 1CH기 때문에 자세한 내용은 추후에 더 추가하도록 하겠습니다.
    

## SUPPORT
