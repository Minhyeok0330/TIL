# Git 기본 개념

## 분산 버전 관리 시스템
    - 클라이언트(로컬)와 서버 모두가 똑같은 데이터를 유지하여 버전을 관리하는 시스템

## 파일의 세가지 상태

![areas](../assets/areas.png)

- 영역
    - working directory :작성하고 있는 코드, 파일
    - staging area : add 명령어로 무대 위로 올라간 파일들
    - .git directory : commit 명령어로 스냅샷을 찍은 파일

![lifecycle](../assets/lifecycle.png)

- Tracked(관리대상), Untracked(비관리대상)
   - Tracked 파일: 이미 스냅샷에 포함돼 있던 파일
        - Unmodified(수정되지 않음), Modified(수정됨), Staged(저장됨)
    - Untracked : 워킹 디렉토리에 있는 파일 중 스냅샷에도 Staging Area에도 포함되지 않은 파일이다.

 - Unmodified 파일은 add 할 수 없음.

 ## Branch
- 안정성 좋은 현 개발 과정을 건드리지 않고 갈래를 나눠 개발을 진행, merge 하기 위한 개념