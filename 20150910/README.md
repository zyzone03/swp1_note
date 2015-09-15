#2강 - 개발 환경 구축
c9에 프로젝트 작성하는 하나의 웹 서비스
git은 버전 관리가 쉽도록 하는 서비스(내가 수정한 부분만), 이전으로 돌릴 수도 있음
리눅스의 명령어들(dir, ls, cd ...)

git init으로 선언 -> git status(Untracked는 git에서 관리를 하지 않음) -> git add 파일명(git에 추가, README.md)
git commit -m “first” : fisrt라는 글자를 처음으로 저장(-m은 어떤 메시지를 줄 것인지)
git diff : 어떤 것이 수정되었는지 알려줌 -> 수정 후에도 git add . ( . 을 이용하면 모두 저장)
 수정 사항을 모두 올리는 것이 아니라 원하는 부분을 stage에 올려서 따로 저장 가능
git에서 commit은 프로젝트 전체 상태를 저장하는 것

c9에서 만든 것을 github의 repository에 저장할 수 있음(원격저장소) : 안전한 백업, 개발자들과의 공유
리눅스에서는 비밀번호 아무 반응 없음

html에서 ‘m'은 mark-up(nav, div 등의 마크)
md는 mark-down으로 간단하게 꾸밀 수 있도록

이상 2강 노트