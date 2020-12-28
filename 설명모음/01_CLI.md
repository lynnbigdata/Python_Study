# CLI(Command Line Interface)

- 커맨드(명령어)를 통해 작동하는 인터페이스

<--> GUI(Graphic User Interface) : 일반적인 프로그램

- `ctrl+l` : 커맨드 창 깔끔하게 만들기

- `git --version`, `git -V`

## 기초 명령어

### (1) `pwd`

- `pwd` (print working directory) : 현재 위치(경로 출력)
- `~`(home directory) :  git bash를 처음 열면 나오는 폴더 



### (2) `ls`

- `ls`(list) : 내용물 출력(list)
- `ls -a` : 숨김파일까지 포함하여 모든 내용물 출력



### (3) `cd[폴더명]`

- `cd`(change directory) : 폴더를 변경
  
- down + tab = downloads
  
- `cd..` : 상위 폴더 이동 (.. = 상위폴더)

  `cd ~` 

- `cd.` : 현재 폴더로 이동 (. = 현재폴더)



### (4) `mkdir[폴더명]` 

- `mkdir`(make directory) : 폴더를 생성



### (5) `rm[파일명]`

- `rm`(remove) : 파일을 삭제



### (6) `rm -r[폴더명]`

- `-r` (recursive,재귀적으로) :  폴더 안에 있는 하위 폴더, 파일까지 다 삭제한다.
- ex) rm -r a b : a와 b 폴더를 삭제한다.



### (7) `touch [파일명]`

- `touch`  : 파일 생성
- ex) touch a.txt : a 텍스트파일을 만든다.



### (8) `cp[파일명] [위치]`

-  `cp` (copy) : 파일 복사
- ex) cp a ./b : a 폴더의 파일을 복사해서 b 폴더에 넣는다.



### (9) `cp -r [폴더명] [위치]`

- 폴더를 복사
- ex) cp -r a . : a 폴더를 복사한다.



### (10) `mv [파일/폴더명] [바꿀파일/바꿀폴더명]`

- `mv`(move) : 파일/폴더명 변경
  - ex)  mv  a.txt  b.txt
    ex)  mv  aa/    b.txt
- `mv [ 파일/폴더명] [위치] ` : 파일 또는 폴더를 **이동**
  - ex)  mv  b.txt  bbc