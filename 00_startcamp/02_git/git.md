# GIT 이란...
> 분산 버전 관리 시스템

## Git 의 3가지 영역
1. Working Directory
    - 실제 작업 영역

### git 초기화
```bash
$ git init
```

### 상태 확인 명령어
```bash
$ git status
```

### staging area에 추가
```bash
$ git add {path}<folder_name>/{file_name}
```

### Repository에 저장하기
```bash
$ git commit -m "commit message"
```

### git 기초 설정
```bash
$ git config --global user.email "viktor@forestsoft.co.kr"
$ git config --global user.name "김구현 전임강사"

$ git config --global --list
```

### 커밋 기록 확인하기
```bash
$ git log
```

### 직전 커밋 수정하기
```bash
$ git commit --amend
# vim에서 커밋 내용 수정하기 
# 1. insert를 눌러서 - 삽입 상태로 만든다.
# 2. 커밋 메시지를 수정한다.
# 3. esc를 눌러서 - 삽입 상태를 종료한다.
# 4. :wq 를 입력해서 저장하고 종료한다.
```