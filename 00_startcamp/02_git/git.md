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