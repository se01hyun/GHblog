#### 0. Git 설치 및 환경설정 🔍

Git 설치 https://git-scm.com/

-   설치 완료 후 Git bash 열어 환경설정

    **git config --global user.name "your_name"**: 유저 이름 설정

    **git config --global user.email "your_email"**: GitHub 가입 시 사용한 이메일

    **git config --list**: 정보 확인

#### 1. 초기화 및 기본 설정

**git init**: 새 깃 저장소를 초기화

**git branch**: 현재 브랜치 확인 및 브랜치 설정 방법

**git checkout main**: main으로 브랜치 변경

**git branch main**: main 브랜치 생성

#### 2. 변경 사항 추가 및 커밋

**git status**: 현재 작업 상태 및 변경된 파일을 확인

**git add src/index/index.html**: 특정 파일을 스테이지에 추가

**git add .**: 또는 변경된 모든 파일을 추가

**git status**: 상태 확인 (선택사항)

**git commit -m "추가사항"**: 커밋을 수행하고 메시지를 추가

#### 3. 원격 저장소와 연결 및 푸시

**git remote add origin (Codee URL 복붙)**: 원격 저장소 추가

**git remote -v**: 원격 저장소 확인 (추가한 원격 저장소의 URL이 든다면 성공)

**git remote set-url origin (Codee URL 복붙)**: 원격 저장소 URL을 설정 (URL 변경 시 사용)

**git push origin main**: main 브랜치로 원격 저장소에 푸시

#### 4. 동기화 및 기록 확인

**git pull origin main**:원격 저장소(GitHub)의 최신 변경사항을 로컬 저장소(내 컴퓨터)에 반영

ex. 다른 사람이 원격 저장소에 커밋을 했다면, git pull 명령어를 통해 그 변경사항을 내 로컬 저장소로 가져올 수 있음

즉, git fetch(원격 저장소에서 변경사항을 가져오는)와 git merge(가져온 변경사항을 내 로컬 브랜치에 합치는) 작업을 동시에 수행하는 명령어

= 원격 저장소와 내 로컬 저장소를 동기화하는 명령어

**git log**: 커밋 기록 확인

#### 5. 파일 및 폴더 목록 확인 (Windows 명령어)

**dir**: 현재 디렉토리 내의 파일 및 폴더 목록을 표시
