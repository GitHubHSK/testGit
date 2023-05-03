1. Git이란? 

(참고 : https://git-scm.com/book/ko/v2 (공식 Site 한글 매뉴얼))



1.1 형상 관리 도구(Configuration Management Tool) 중 하나.

 - 참고로 형상 관리 도구는 버전 관리 시스템이라고도 한다.

 - Git은 소프트웨어를 개발하는 기업의 핵심 자산인 소스코드를 효과적으로 관리할 수 있게 해주는 무료, 공개소프트웨어.

 - SVN보다 여러 장점이 있어 SVN을 쓰던 개발 조직들은 하나둘씩 Git으로 갈아타고 있다.



1.2 SVN과 Git의 차이점

 - Git이 SVN과 다른 점은 분산형 관리 시스템이라는 것이다.

 - SVN : 중앙 서버에 소스코드와 히스토리를 저장하는 과 달리

   Git :  소스코드를 여러 개발 PC와 저장소에 분산해서 저장

   그렇기 때문에 중앙 서버에 장애가 발생해도 로컬 저장소에 커밋을 할 수 있으며, 로컬 저장소들을 이용하여 중앙 저장소의 복원도 가능하다.

 - 사본을 로컬에서 관리하기 때문에 GIT이 SVN에 비해 훨씬 빠르다.(SVN은 변경 로그 하나 보는 것도 인터넷을 경유해야 한다.)