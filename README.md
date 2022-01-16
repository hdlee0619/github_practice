# 깃 허브 연습을 위해서 만든 래퍼지 스토리
## 파이썬으로 계산기에 사용되는 간단한 함수들을 만들어 커밋하고 깃허브에 푸쉬, 풀 할 때 사용할 것임

** git command 다양하게 사용해보기
* 첫 push에 사용해봤던 명령어들
1. git init
    - 로컬 디렉토리를 working directory(work tree)로 만들어줌
2. git --global user.name "name", git --global user.email
    - 사용자 이름과 이메일을 설정해줌
    - global 옵션을 통해서 시스템 전체에 설정함 
    - 프로젝트마다 다른 이름과 이메일을 사용하려면 --global 옵션 빼주기
3. git branch -M main
    - branch의 이름을 main으로 설정
4. git remote add origin (주소)
    - 로컬 레포지스토리와 리모트 레포지스토리를 연결
    - origin 말고 다른 이름도 가능하지만 처음 래포지스토리를 만들때의 근원이라는 의미를 가지고, 관례(?)라고 함
5. git status
    - 현재의 상태(tracked, untracked)를 보여줌
    - add, commit 여부와 새파일의 생성을 확인 할 수 있음
6. git add .
    - 모든 변경사항을 staging area로 보냄
    - add를 하고 commit을 하면 파일들이 tracked, Unmodified 상태가 되고 수정이 된다면 Modified 상태가 됨
7. git commit -m "massage"
    - 파일들에 massage를 남기면서 commit함
    - staging area에 있던 파일들이 최신 commit이 되면서 Unmodified 상태가 됨
8. git push -u origin main
    - 로컬에서 리모트로 푸쉬해줌
    - 이 명령을 처음 해주고 난 뒤에는 그냥 git push 명령만 해도 push 할 수 있음