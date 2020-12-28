# Git

- Source Code Management (SCM) : 코드 관리 도구 (버전을 통해 관리)

- Version Control System(VCS) : 버전 컨트롤 시스템



## 주요사항

### (1) `git`은 폴더를 기준으로 프로젝트(코드)를 관리한다.

### (2) `git init`

- 현재 폴더에서 코드 관리를 시작 (init) 한다.
- `.git` 폴더 생성 == git으로 폴더가 관리되고 있다.
  - ls -a :  .git/
- `.git` 폴더 삭제 == git으로 폴더 관리를 중지한다.
  - rm -rf .git/
    ls -a : x

### (3) `git status` (**) : 변경사항 확인

- 현재 상태(status)를 출력한다.햣 

```
On branch master (master 브랜치에 있음)

No commits yet (아직 commit이 없음)

nothing to commit (create/copy files and use "git add" to track)
(commit 할 게 없음)
```

- 새로운 파일을 생성한 경우

``` 
On branch master (master 브랜치에 있음)

No commits yet (아직 commit이 없음)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        a.txt

nothing added to commit but untracked files present (use "git add" to track)
(git add 하고 파일명 쳐줘)
```

![](C:\Users\rini9\Desktop\마크다운\캡처.JPG)

### (3) `git add [파일명]`

- 버전을 만들(Commit 할/스냅샷을 찍을) 파일을 추가
  - ex) git add a.txt
- git add 이후 git status

```
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   a.txt
```

### (4) `git commit -m "메세지"` 

- 버전을 만든다(commit, snapshot)
- message를 필수적으로 입력한다
  - message 집어넣을 화면에서 나오는 방법 : `Esc 여러번 + :q!` 



### (5) `git log`

- 현재까지의 버전(스냅샷)