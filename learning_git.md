

### git bash

~: home directory

- 절대 경로: root directory -> 목적파일 (모든 경로가 전부 포함)
- 상대 경로: 현재 작업중인 directory 기준으로 계산한 상대적 표시
- ./자신과 같은 폴더
- ../자신보다 상위폴더

ex) C:/users/SSAFY/sky/a.txt

​      C:/users/SSAFY/earth/b.txt -> ../earth/b.txt

- touch:파일 생성(여러개 가능)
- start .: 폴더 열기
- mkdir: 폴더 만들기(단. 띄어쓰기 하고싶으면`''(따옴표)안에 넣어서 하면됨 `)
- ls: 현재 폴더 리스트
  - ls --help: 명령어 확인
  - ls -a: directory의 숨김 파일과 directory까지 출력
  - ls -l:directory의 폴더 상세 정보까지 출력
- pwd: 현재 폴더 위치
- cd ..: 상위 폴더로 이동
- cd (폴더이름): 폴더 변경
- mv: (같은파일에서)이름변경 (다른파일에)위치변경
- rm: 파일 제거

### git

- git init:저장소 만들기
- git add: 현재 상태 추적
- git commit:현재 상태 저장


- git config --global `user.name`
- git config --global `user.email`
- git status: 현재 상태 확인