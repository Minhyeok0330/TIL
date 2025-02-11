# 명령어 정리

## `git init`
- 현재 디렉토리에 `.git` 폴더를 생성하여 새로운 Git 저장소를 생성함

##  `git config --global user.name` 
- 모든 코드가 name git에 커밋된다.

## `git clone`
- 현재 디렉토리에 원격저장소(github 주소) 폴더를 복제

```
git clone {remote_url}
git clone {remote_url} {directory_name}
```

## `git status`
 - 현재 git의 상태를 확인
    - tracked, untracked로 파일을 구분하여 표시

## `git add`

- working directory에서 변경된 파일을 staging area에 이동
```
git add {file_name/directory_name}
git add . => 현재 나의 위치 기준 모든 파일과 폴더
```

## `git commit` 
- staging area에 있는 변경사항을 커밋하여 스냅샷을 찍는 명령어

dd