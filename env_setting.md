## 개발 환경 세팅
기본적으로 아래의 항목들이 설치되어 있어야 합니다
- git
- vscode 설치 (extenstion으로 python, jupyter, black formatter 설치)
- python (최신 버전 3.11 이상 권장)
- git bash (윈도우 운영체제 사용자의 경우 리눅스 커맨드 이용을 위해)

위 설치가 완료되었으면 아래 순서대로 개발 환경을 세팅해주세요

1. 실습 레포 클론받기 : git clone https://github.com/mlleo/metacode_study.git
2. venv로 가상환경 생성 : python -m venv <env_name>
3. 가상환경 생성 후 활성화 : source <env_name>/bin/activate
4. pip install -r requirements.txt
5. pip list로 패키지들 설치되었는지 확인
6. 실습 레포의 루트에 .env 파일 생성
7. LangSmith key 발급 (smith.langchain.com -> settings -> create api key)

