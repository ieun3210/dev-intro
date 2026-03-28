옛날에는 인터넷으로 텍스트 기반으로 정보를 공유함. 하지만 각자 정보를 저장하는 시스템이 다라서 연구가 힘들었음. 정보의 검색, 교환을 조금 더 쉽게 하려면? -> 양식을 통일하자! 이 양식을 HTML이라고 함.
HTML = HyperText MarkupLanguage

# MarkupLanguage
컴퓨터와 읽는 사람에게 이 부분은 제목이고, 여기는 시인 이름, 저기부터 내용이라고 알려줘야했다.
우리는 텍스트 외에도 부가적인 정보가 필요한데 이런 의도를 전달하는 언어가 마크업 언어이다.
=> 위계, 텍스트 외의 정보를 주자! 구조적인 문서를 만들자! 태그를 사용해서!

h1은 가장 큰 제목, h2는 두번쨰로 큰 제목, p는 단락이고 title에는 페이지 제목을 쓴다.

# 내가 쓴 코드를 github에 업데이트 하는 방법
1. 내가 하고 있는 파일에 우클릭해서 git bash를 누른다.
2. git status를 쳤을 때 modified가 써있으면 저장되어있는 코드가 최신화가 안되어 있다는 뜻
3. git add <파일 이름>
   git commit -m "<메시지>" -> 
   git push
하면은 github에 최신화가 된다.
github에 <파일 이름> <메시지> <수정된 시간>으로 뜬다.
git(컴퓨터프로그램) -> Github(웹 플랫폼)

# vercel로 배포하는 방법
1.github로 로그인
2. 오른쪽 상단 Add New -> Project 선택
3. 우리의 레포지토리를 찾아서 import -> Deploy 끝

#배포한 링크
https://dev-intro-g1y3.vercel.app/
