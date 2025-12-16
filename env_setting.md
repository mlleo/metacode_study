개발 환경 세팅
기본적으로 아래의 항목들이 설치되어 있어야 합니다
git
vscode 설치 (extenstion으로 python, jupyter, black formatter 설치)
python (최신 버전 3.11 이상 권장)
poetry (파이썬 패키지 관리 도구, 버전 충돌 의존성 관리) -> pip3 install poetry==1.8.5
실습 레포 클론받기 : git clone https://github.com/mlleo/metacode_study.git
실습 레포의 루트에 .env 파일 생성
LangSmith key 발급 (smith.langchain.com -> settings -> create api key)
venv로 가상환경 생성 : python -m venv <env_name>
가상환경 생성 후 활성화 : source <env_name>/bin/activate
pip install -r requirements.txt
poetry shell && poetry update
pip list
