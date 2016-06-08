github 와 gitlab ssh key 추가하기

1. 터미널에서 ssh-keygen 명령어 입력
   완료 될때까지 엔터
   
2. 우분투:cat ~/.ssh/id_rsa.pub  키를 보여줌 복사해서 깃허브, 깃랩에 ssh key에 붙여넣기
2. 맥 : cd ~/.ssh	ls -al 리스트에 파일 있음	 
      : cat id_rsa.pub   이렇게 키가 출력되면 복사해도 되고 우분투 처럼 해도 됨


현재 vim으로 편집중
첫 시작하면 i 를 클릭하면 insert 삽입으로 
글을 쓸수 있다

다시 수정했다 
그러면 git add 파일이름 해서 수정하고
git status 를 입력하면 해당 파일이 수정되어 있다는 문구가 뜸

그러면 커밋을 해야 함
git commit -am "change Readme.txt"
위 명령어 입력을 하면 완전히 수정이 됨

맥에서 내용을 수정했다
우분투에서 제일 먼저 해야 하는게 git pull 명령어를 치면 끝나는지 한번 보자 

커밋을 할때 "" 안에 커밋한 내용을 작성하고 엔터
git commit -m "add insert"

