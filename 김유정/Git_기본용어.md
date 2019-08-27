# Git

**※ 학습용으로 작성한 문서이므로 오류가 있을 수 있습니다.**

-  컴퓨터 파일의 변경사항을 추적하기 위한 분산 버전 관리 시스템

#### Git을 사용하는 이유

- 어떠한 집합의 파일의 변경사항을 지속적으로 추적하여, 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기에 용이하다.



# Git 용어

#### 영역

- **working directory**
  - 현재 작업하고 있는 공간
  - Git이 관리하고 있지만, 아직 track하고 있지 않은 상태
- **index**
  - stage 또는 staging area라고 하며, 준비 공간
  - Git이 track하고 있으며, 버전으로 등록되기 전 상태
- **repository**
  - 저장소
    - 본인 PC에 존재하는 local repository
    - Github, Gitlab 같은 원격 저장소인 remote repository



#### Flow

- **git init**
  - .git 폴더를 생성
- **git add**
  - working directory의 변경된 작업 파일을 staging area로 추가
- **git commit**
  - staging area의 내용을 local repository에 확정
- **git push**
  - local repository의 내용을 remote repository로 업로드
- **git pull**
  - local repository의 내용을 remote repository에서 가져옴
- **git clone**
  - .git을 포함한 remote repository의 파일들을 local repository에 복사



#### 협업 - 병합

- **git branch**
  - 독립된 working directory를 의미
  - 브랜치를 통해 프로젝트 참여자마다 브랜치를 가져서 독립된 작업 공간을 갖는다.
  - 테스트 및 백업으로 사용 가능
- **head**
  - 포인터를 의미하며, 지금 작업하고 있는 branch를 가르킨다
- **marge**
  - 2개의 branch에서 작업한 다른 내용을 하나로 합치는 것을 말하며, 현재 브랜치를 기준으로 병합됨
  - 만약 두 branch가 같은 파일의 같은 곳을 수정했다면, 충돌( merge conflict )이 발생





##### 출처 :

https://victorydntmd.tistory.com/72?category=682764

https://git-scm.com/book/ko/v1/%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0

