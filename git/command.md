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

## `git log`
- 커밋의 히스토리를 조회
    - option
        - `--oneline`
        - `--graph`

## `:q`
- 모드 종료(터미널)
   
## `:sq`
- 저장 후 종료(터미널)

## `git commit --amend`
- 커밋된 깃의 메시지 변경

## `git remote`
- 원격저장소 관리 명령어
    - {-v}로 실제주소 확인가능

- 원격저장소 추가
    - 일반적으로 remote_name은 origin 사용
```
git remote add {remote_name} {remote_url}
```

- 원격저장소 확인
```
git remote -v
```

- 원격저장소 삭제
```
git remote remove {remote_name}
```